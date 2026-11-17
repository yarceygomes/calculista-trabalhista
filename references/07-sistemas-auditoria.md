# PJe-Calc, auditoria e entrega

Referência da skill calculista-trabalhista. Base de pesquisa: 29/10/2026. Leia apenas os módulos pertinentes. Verifique a aplicabilidade temporal e o título antes de usar regras ou fórmulas. Exemplos são didáticos.

### 59. Preparação do PJe-Calc

A página oficial consultada indicava **PJe-Calc Cidadão 2.16.0**, disponível desde 25/06/2026. Isso descreve a consulta, não garante que seja a versão vigente em uso futuro. Registrar versão instalada, tabelas auxiliares e data da atualização. [TRT8, PJe-Calc Cidadão](https://www.trt8.jus.br/pjecalc-cidadao).

Antes de atualizar o programa, fazer backup verificável. Tabelas do regional e versão do sistema são controles diferentes. Conferir calendário, índices, limites e tabelas fiscais efetivamente disponíveis.

O sistema executa parâmetros; não interpreta sozinho o título. Uma liquidação concluída sem aviso de erro pode continuar juridicamente incorreta.

### 60. Sequência de montagem e conferência

1. Cadastrar partes, contrato, local, ajuizamento e data-base.
2. Definir períodos exigíveis, prescrição e projeção do aviso.
3. Inserir histórico salarial e rubricas componentes.
4. Cadastrar faltas, férias e afastamentos.
5. Inserir jornada apurada ou quantidades reconhecidas.
6. Configurar verbas principais, bases, divisores e percentuais.
7. Configurar reflexos e suas dependências, sem circularidade.
8. Configurar FGTS, contribuições e imposto de renda.
9. Definir atualização, honorários, custas e pagamentos.
10. Liquidar, ler ocorrências, abrir relatórios analíticos e reconciliar.

Os nomes das telas podem mudar. Esta sequência é um método de trabalho, não transcrição de interface. Exportar o arquivo nativo e reimportar em cópia quando necessário para verificar integridade da entrega.

### 61. eSocial: S-2500 e S-2501

S-2500 registra informações do processo e efeitos sobre contrato/bases; S-2501 trata de tributos relacionados ao processo. Não confundir competência da prestação, referência judicial e mês de pagamento.

Verificar evento que gera obrigação, prazo, responsável, múltiplos vínculos, retificações, exclusões e regras de depósito judicial. Há hipóteses em que o depósito não gera envio de S-2501 da forma que seria esperada para pagamento direto; consultar o MOS e a FAQ, não apenas a data de saída financeira.

Guardar recibos, retornos e bases por competência. A escrituração deve reconciliar com a decisão e os valores finais, inclusive após impugnação. [Documentação técnica vigente](https://www.gov.br/esocial/pt-br/documentacao-tecnica); [FAQ de processos trabalhistas](https://www.gov.br/esocial/pt-br/empresas/perguntas-frequentes/perguntas-frequentes-producao-empresas-e-ambiente-de-testes).

Não adotar prazos de manual antigo como atuais. O PDF de 2024 localizado na pesquisa é histórico; o portal contém versões posteriores do MOS.

### 62. DCTFWeb e FGTS Digital

Decisões abrangidas pela transição de outubro de 2023 passaram a ser escrituradas no eSocial e confessadas em DCTFWeb Reclamatória Trabalhista, conforme enquadramento. Conferir o evento judicial determinante, não só a data de admissão. [Comunicado oficial da transição](https://www.gov.br/esocial/pt-br/noticias/receita-federal/reclamatoria-trabalhista-passa-a-ser-informada-na-dctfweb-a-partir-de-outubro-de-2023/).

**Atualização de 2026:** o MTE informa uso do FGTS Digital para processos alcançados pelo marco de 01/05/2026, observadas as datas de sentença/determinação judicial ou acordo definidas no comunicado. Casos anteriores permanecem na sistemática indicada de SEFIP/GFIP 660; há exceção para domésticos. Não escolher o canal apenas pela competência trabalhada. [Comunicado completo do MTE](https://www.gov.br/trabalho-e-emprego/pt-br/servicos/empregador/fgtsdigital/comunicados/em-producao-recolhimentos-de-fgts-em-processos-trabalhistas-devem-ser-efetuados-via-fgts-digital/).

A rotina deve reconciliar S-2500, totalizadores, bases, multa, guia e pagamento. Não prometer integração automática universal entre PJe-Calc e sistemas declaratórios. Cada etapa exige validação.

### 63. Auditoria em cinco camadas

| Camada | Pergunta | Evidência |
|---|---|---|
| Jurídica | Segue o título e o regime temporal? | Matriz do título e fontes |
| Documental | Dados correspondem aos documentos? | Rastreio por ID/página |
| Quantitativa | Dias, minutos, avos e bases estão corretos? | Memórias independentes |
| Financeira | Fórmulas, índices e abatimentos fecham? | Recálculo e conciliação |
| Operacional | Arquivos e declarações são utilizáveis? | Exportação, recibos e controles |

Escolher amostras por risco: primeiro/último mês, reajuste, férias, afastamento, maior HE, mês com feriado, transição legal, rescisão e pagamento parcial. Não se limitar a um mês “normal”.

Se a amostra revelar erro estrutural, ampliar a revisão para todas as competências afetadas. Pequena diferença final não significa ausência de erros: erros opostos podem se anular.

### 64. Erros recorrentes e testes de detecção

| Erro | Teste |
|---|---|
| Horas decimais confundidas com relógio | Recalcular um dia em minutos |
| HE diária somada novamente à semanal | Conferir união das faixas excedentes |
| RSR fixo duplicado | Comparar mensalista e rubrica adicionada |
| Reflexos circulares | Desenhar dependências de bases |
| Divisor único em contratos distintos | Cruzar jornada e período |
| Todo sábado tratado como repouso | Conferir título e CCT |
| Salário atual em todo o passado | Reconciliar histórico salarial |
| Meses sem documento lançados como zero | Revisar cobertura documental |
| FGTS sobre férias indenizadas por cópia | Revisar incidências por natureza |
| INSS sobre total acumulado | Recalcular por competência e teto |
| Maior alíquota progressiva sobre toda a base | Recalcular faixas |
| Selic com juros de 1% em paralelo | Inspecionar períodos de atualização |
| Pagamento histórico abatido do atualizado | Conferir data do abatimento |
| Honorários em duplicidade | Conciliar por beneficiário e espécie |
| Meses de RRA contados por rubrica | Unificar competências elegíveis |
| Multa de 40% sobre saldo após saques | Reconstruir base rescisória |
| Mudança jurídica aplicada ao mês inteiro | Conferir data exata do marco |
| Arquivo editável não corresponde ao PDF | Liquidar a cópia final e comparar |

### 65. Impugnação técnica

Estrutura por achado: item da conta → critério usado → critério correto proposto → fundamento → documento → exemplo → valor do impacto → pedido de ajuste.

Evitar “cálculo incorreto” sem demonstrativo. Separar erro de soma, erro de dado, divergência jurídica e falta de prova. Quantificar impacto no principal, reflexos, FGTS, encargos e saldo, quando aplicável.

Usar mesma data-base para comparação. Se houver vários erros interdependentes, mostrar a ordem de correção: a soma de impactos isolados pode não coincidir com o impacto conjunto.

Observar intimação e prazo processual. A CLT, art. 879, § 2º, prevê impugnação fundamentada com itens e valores; não inferir prazo concreto sem conhecer o ato e calendário processual. [CLT](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm).

### 66. Entrega e critérios de conclusão

Pacote recomendado: resumo executivo; matriz do título; critérios; memória analítica; quadro de bruto/líquido/custo; pendências; arquivo nativo; relatórios finais; documentos de suporte necessários; versão/data-base.

**Pronto para entrega quando:** parâmetros relevantes têm origem; diferenças estão explicadas; amostras críticas fecham; total e destinos conciliam; versão editável corresponde à versão apresentada; pendências materiais estão visíveis.

Nome de arquivo sugerido: `processo_parte_produto_database_versao`. Guardar versão anterior e registro de mudanças. Não alterar arquivo já protocolado sem gerar nova versão identificada.
