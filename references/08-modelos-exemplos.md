# Modelos e exemplos

Referência da skill calculista-trabalhista. Base de pesquisa: 29/10/2026. Leia apenas os módulos pertinentes. Verifique a aplicabilidade temporal e o título antes de usar regras ou fórmulas. Exemplos são didáticos.

### 67. Modelo de ficha de caso

```text
Identificação / processo / cliente:
Produto: estimativa | liquidação | auditoria | atualização | acordo
Juízo / TRT / responsável:
Trabalhador / empregadores / contratos:
Admissão / desligamento / projeção:
Ajuizamento / prescrição / data-base:
Decisões que formam o título, por ID:
Categoria / território / ACT-CCT por período:
Remuneração / jornada / afastamentos:
Documentos faltantes e impacto provável:
Parâmetros pendentes e quem deve resolvê-los:
Versão do sistema / tabelas / responsável pela revisão:
Escopo aprovado / data de entrega:
```

### 68. Modelo de ficha de verba

```text
Código / nome:
Fonte judicial (ID, página, trecho de comando):
Status: título | regra supletiva | hipótese | controvérsia
Período e marcos internos:
Documentos e cobertura:
Base / divisor / percentual / quantidade:
Fórmula e unidade:
Valores pagos e regra de dedução:
Reflexos diretos:
Reflexos sucessivos autorizados:
Incidência de FGTS / INSS empregado / patronal / IR:
Vencimento / correção / juros:
Configuração no sistema:
Exemplo de controle / resultado esperado:
Pendências / revisor / data:
```

### 69. Modelo de biblioteca de precedentes

Uma ficha por questão, não apenas uma pasta por tribunal:

```text
Questão jurídica e impacto no cálculo:
Tribunal / órgão / processo / tema:
Tipo: controle concentrado | repercussão geral | IRR | IAC | outro
Situação: afetado | julgado | publicado | embargos | trânsito | revisto
Tese em síntese própria:
Fatos aos quais se aplica:
Distinções e hipóteses excluídas:
Modulação / início dos efeitos:
Fonte oficial / data de consulta:
Regra operacional decorrente:
Casos internos afetados / responsável / próxima revisão:
```

Não tratar voto vencido como tese vencedora, proposta de cancelamento como cancelamento consumado ou tema afetado como tese já firmada. Usar notícias para localização e acórdão para aplicação.

### 70. Modelo de pendências e cenários

| Campo | Preenchimento |
|---|---|
| Pendência | Qual dado ou critério falta? |
| Origem | Documento ausente, contradição ou questão jurídica |
| Efeito | Verbas e competências afetadas |
| Materialidade | Impacto conhecido ou potencial; nunca inventar precisão |
| Cenário A/B | Premissas completas e mutuamente claras |
| Responsável | Quem pode resolver |
| Situação | Aberta, respondida, adotada provisoriamente ou encerrada |

Cenários devem variar apenas o que está em discussão. Se salário e jornada mudarem simultaneamente, não atribuir toda a diferença a um único parâmetro. Uma faixa de estimativa deve vir acompanhada da lógica que gera os extremos.

### 71. Exemplos numéricos de controle

**A — HE e RSR.** Hipóteses: base R$ 3.300,00; divisor 220; 20 HE a 50%; 25 dias úteis e 5 repousos elegíveis; nada pago. Hora = 3.300/220 = R$ 15,00. HE = 20 × 15 × 1,5 = **R$ 450,00**. RSR = 450/25 × 5 = **R$ 90,00**. Total dessas duas parcelas: **R$ 540,00**. Reflexos posteriores dependem de período, título e médias. Os 25/5 são dados do exemplo, não calendário universal.

**B — Férias proporcionais.** Hipóteses: base validada de R$ 3.000,00, 7/12, direito anual de 30 dias. Férias = 3.000 × 7/12 = R$ 1.750,00. Terço = R$ 583,33. Total = **R$ 2.333,33**, antes de considerar pagamentos e classificação da parcela.

**C — Hora noturna.** Hipóteses: sete horas de relógio integralmente computáveis no período noturno urbano, sem intervalo, base-hora de R$ 15,00 e adicional de 20%. Quantidade ficta = 420/52,5 = 8 horas. Somente adicional = 8 × 15 × 0,20 = **R$ 24,00**. Não representa a remuneração completa da jornada nem resolve horas extras.

**D — Intervalo pós-reforma.** Hipóteses: intervalo exigível de 60 minutos, 40 concedidos, 22 dias, salário-hora de R$ 15,00, adicional de 50%. Quantidade suprimida = 20 × 22/60 = 7,333333... horas. Valor = 7,333333... × 15 × 1,5 = **R$ 165,00**. Não arredondar a quantidade para 7,33 antes da multiplicação. Verificar norma e título.

**E — Diferença com reflexo.** Hipóteses: salário devido R$ 3.000,00, pago R$ 2.800,00; 10 HE a 50%, divisor 220, ambas as bases compostas apenas pelo salário. Diferença salarial = **R$ 200,00**. Diferença de HE = (3.000 − 2.800)/220 × 10 × 1,5 = **R$ 13,64**. Reprocessar RSR, médias e incidências cabíveis; não usar o percentual da diferença como atalho para parcelas com bases diversas.

**F — Conciliação de destinos.** Hipóteses meramente didáticas: crédito bruto de R$ 10.000,00, já incluindo R$ 800,00 de FGTS destinado à conta vinculada; INSS do empregado R$ 600,00; IR R$ 200,00. Líquido em dinheiro = **R$ 8.400,00**. Destinos: 8.400 + 800 + 600 + 200 = 10.000. Se encargos patronais forem R$ 2.000,00 e honorários separados R$ 1.000,00, total do devedor = **R$ 13.000,00**, sem somar novamente o FGTS ou o INSS retido.

### 72. Roteiro de revisão independente

Revisor recebe título, documentos essenciais e conta, mas refaz amostras antes de consultar as fórmulas do elaborador. Isso reduz reprodução do mesmo erro.

Conferir pelo menos: uma competência ordinária; uma com variável; uma com afastamento; uma em marco temporal; rescisão; atualização com pagamento; totais e destinos. A seleção real deve acompanhar o risco do caso.

Registro do achado: severidade, descrição, causa, abrangência, impacto, ação, responsável e confirmação de correção. Severidade não depende só de valor: extrapolação do título pode ser crítica mesmo com pequeno impacto imediato.

### 73. Perguntas para usar IA como apoio

Prompts de trabalho, sempre com revisão humana e documentos adequados:

- “Extraia os comandos de cada decisão em tabela, com ID/página e indicação de quais foram modificados posteriormente. Não complete lacunas.”
- “Liste contradições entre os parâmetros propostos e o título, separando certeza documental de interpretação.”
- “Identifique os períodos que exigem mudança de regra e informe a fonte oficial necessária para validá-los.”
- “Revise o calendário e as quantidades deste exemplo, mostrando a conta em minutos antes dos valores.”
- “Compare estas contas na mesma data-base e classifique divergências por dados, regra, fórmula, atualização e pagamento.”
- “Verifique se a memória contém duplicidade de reflexos ou destinos sem propor direitos não deferidos.”

IA não deve inventar salários, preencher cartões ausentes, criar precedentes, assumir trânsito, decidir controvérsia silenciosamente ou declarar que executou cálculo oficial quando apenas simulou fórmulas. Proteger dados pessoais e limitar o compartilhamento ao necessário.

### 74. Checklist final compacto

- [ ] Produto, escopo, versão e data-base identificados.
- [ ] Título completo e decisões modificadoras considerados.
- [ ] Cada parâmetro classificado como comando, regra ou hipótese.
- [ ] Prescrição e período contratual separados corretamente.
- [ ] Normas coletivas e marcos temporais documentados.
- [ ] Histórico salarial reconciliado.
- [ ] Jornada em unidade correta e sem duplicação diária/semanal.
- [ ] Férias, afastamentos e feriados tratados.
- [ ] Bases, divisores, percentuais e médias validados.
- [ ] Reflexos diretos e sucessivos sem circularidade.
- [ ] Pagamentos dedutíveis comprovados e classificados.
- [ ] FGTS e indenização rescisória conferidos.
- [ ] INSS por competência, teto e regime correto.
- [ ] IR/RRA, meses e deduções conferidos.
- [ ] Atualização sem sobreposição de índices/juros.
- [ ] Depósitos e pagamentos tratados nas datas apropriadas.
- [ ] Honorários e custas com bases próprias.
- [ ] Bruto, líquido, destinos e custo total conciliados.
- [ ] Arquivo nativo e relatório final correspondentes.
- [ ] Pendências materiais e limitações visíveis.
