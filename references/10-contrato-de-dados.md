# Contrato de dados e memória de cálculo

Use este esquema como organização lógica. Para caso pequeno, tabelas no texto bastam; para muitos registros, prefira planilha, CSV ou banco de trabalho. Não crie campos com valores inventados para completar um esquema.

## 1. Identificação e estados

- `caso_id`, `trabalhador_id`, `contrato_id`: chaves estáveis internas; evite expor CPF sem necessidade.
- `versao`, `produto`, `data_base`, `moeda`, `responsavel`, `data_elaboracao`.
- Estado de informação: `comprovado`, `informado_pelo_usuario`, `arbitrado_no_titulo`, `hipotese`, `ausente`, `ilegivel`, `contraditorio`, `nao_aplicavel`.
- Use vazio/nulo para ausência e zero somente para valor conhecido igual a zero.

## 2. Documentos

`documento_id | nome | tipo | origem | pagina_ou_celula | inicio_cobertura | fim_cobertura | extracao_conferida | limitacao`

Mantenha original e transcrição separados. Se o usuário corrigir uma transcrição, registre a correção e a origem; não altere o documento original.

## 3. Parâmetros do título e regras

`parametro_id | verba | atributo | valor | unidade | inicio_vigencia | fim_vigencia | status | documento_id | localizacao | fundamento | validado_em`

Status: título, regra aplicável, hipótese ou pendência. Conserve valores antigos por vigência. Se duas decisões conflitarem, registre qual modifica a outra e o capítulo afetado.

## 4. Remuneração

`contrato_id | competencia | inicio_segmento | fim_segmento | rubrica_original | rubrica_padronizada | devido | pago | natureza | documento_id`

Guarde competência da prestação e data de pagamento em campos diferentes. Não agregue verbas de bases incompatíveis em uma rubrica genérica “remuneração”.

## 5. Jornada

`data | entrada | saida | inicio_intervalo | fim_intervalo | minutos_trabalho | minutos_noturnos_relogio | horas_noturnas_convertidas | extras_diarias | extras_semanais_residuais | feriado | afastamento | fonte`

Se houver várias entradas/saídas, use uma linha por intervalo e uma consolidação diária. Indique fuso quando necessário e trate datas completas ao atravessar meia-noite. Jornada arbitrada precisa de regra e período, não de falsas marcações documentais.

## 6. Memória por verba

`linha_id | contrato_id | competencia | verba | parametro_id | base | divisor | quantidade | unidade | percentual | valor_devido | valor_dedutivel | diferenca | vencimento | fonte`

Em reflexos, acrescente `linhas_origem`, `destino`, `janela_media`, `metodo_media` e `regra_temporal`. Verifique que nenhuma cadeia de referências retorne à própria linha.

## 7. Incidências e tributos

`verba | periodo | incide_fgts | incide_inss_segurado | incide_patronal | tratamento_ir | fundamento | pendencia`

Por competência previdenciária: base anterior, base adicional, base recomposta, teto, faixas, contribuição anterior considerada, diferença, regime patronal e encargos. Separe 13º.

Para IR: ano da prestação, mês do recebimento, tributável, isento, juros separados, deduções comprovadas, número de meses RRA sem duplicação, tabela/regime e resultado.

## 8. Atualização e pagamentos

`evento_id | data | tipo | valor | beneficiario | verba_destino | documento | tratamento_juridico`

Tipos distintos: pagamento direto, depósito de garantia, levantamento, recolhimento de tributo, depósito de FGTS e pagamento de honorários.

Por intervalo de atualização: saldo inicial, início/fim, índice, fator/taxa, fonte/versão da tabela, juros, pagamento imputado e saldo final. Armazene taxa e fator com unidade explícita: 1% não é fator 1,00.

## 9. Precisão e reconciliação

- Use decimal monetário ou representação exata adequada à ferramenta; documente arredondamento por linha, competência e total.
- Preserve precisão das quantidades até a valorização. Não arredonde 7,333333 horas para 7,33 antes de multiplicar sem regra que o exija.
- Não zere diferenças negativas sem analisar pagamentos e critério de compensação.
- Compare totais por verba e por competência com o resumo. Destinos devem recompor o total sem somas duplicadas.
- Não force diferença a desaparecer por lançamento de “ajuste” sem origem; identifique a causa e a regra de arredondamento.

## 10. Registro da revisão

`achado_id | camada | competencia | verba | criterio_original | criterio_revisado | fonte | impacto | correcao | abrangencia | status`

Compare cenários na mesma data-base. Se correções interagirem, recalcule o conjunto e explique por que a soma de impactos isolados pode diferir do impacto total.
