# Calculista Trabalhista para IA

Uma *skill* (conjunto de instruções especializadas) que ensina um assistente de IA, como o Claude, a trabalhar como calculista trabalhista: elaborar, liquidar, atualizar e auditar cálculos da Justiça do Trabalho com método, fontes e conferência.

## O que ela faz

- Monta a memória de cálculo **competência por competência**, com reflexos e encargos.
- Exige **fonte** para cada critério: o trecho da sentença, do acordo ou da lei que o fundamenta.
- Separa o que o documento determina do que é padrão legal, e pergunta só o que for indispensável.
- Audita cálculos de terceiros e redige impugnações técnicas.
- Conversa com o PJe-Calc (veja o [PJe-Calc Studio](https://github.com/yarceygomes/pjecalc-studio)).

## Conteúdo

| Arquivo | Assunto |
|---|---|
| `SKILL.md` | Missão, escopo e fluxo de trabalho |
| `references/01-metodo-titulo.md` | Leitura do título executivo e método |
| `references/02-remuneracao.md` | Base de cálculo e evolução salarial |
| `references/03-jornada.md` | Horas extras, intervalos e adicionais |
| `references/04-verbas-rescisao.md` | Verbas rescisórias |
| `references/05-encargos-atualizacao.md` | Correção, juros, INSS, IR e FGTS |
| `references/06-casos-especiais.md` | Situações atípicas |
| `references/07-sistemas-auditoria.md` | PJe-Calc e auditoria de contas |
| `references/08-modelos-exemplos.md` | Modelos e exemplos |
| `references/09-fontes-manutencao.md` | Fontes oficiais e atualização |
| `references/10-contrato-de-dados.md` | Formato dos dados de entrada e saída |

## Como usar

No **Claude Code**, copie esta pasta para `~/.claude/skills/calculista-trabalhista/`. No **Claude Desktop** ou no claude.ai, adicione a pasta compactada em *Configurações › Skills*.

## Aviso

A skill organiza e confere o trabalho; não substitui a análise de um profissional. Confira sempre os critérios e o resultado oficial antes de usar um cálculo em processo.

---

Autor: **Yarcey Gomes**, advogado (OAB/PA 40.438) · [Portfólio](https://yarceygomes.github.io) · Licença MIT
