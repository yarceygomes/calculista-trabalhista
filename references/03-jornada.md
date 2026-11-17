# Jornada e descansos

Referência da skill calculista-trabalhista. Base de pesquisa: 29/10/2026. Leia apenas os módulos pertinentes. Verifique a aplicabilidade temporal e o título antes de usar regras ou fórmulas. Exemplos são didáticos.

### 19. Motor de apuração de jornada

Representar cada intervalo por data e hora completas, inclusive trabalho atravessando meia-noite. Separar presença, trabalho, intervalo, tempo à disposição e tempo excluído.

Trabalhar internamente em minutos ou segundos. `8h30 = 8,5 horas`; `8,30 horas = 8h18`. Arredondar somente nos pontos definidos. Horas noturnas reduzidas e horas de relógio devem ocupar campos diferentes.

A jornada arbitrada judicialmente deve ser implementada como regra explícita de calendário. Feriados, férias e afastamentos precisam de tratamento próprio, sem apagar dias que o título incluiu.

### 20. Horas extras diárias e semanais

`HE integral = quantidade × salário-hora × (1 + adicional)`.

`somente adicional = quantidade × salário-hora × adicional`.

Quando deferidas excedentes diárias e semanais sem cumulação, uma lógica possível é: calcular excedentes diárias; calcular excesso semanal; acrescentar apenas a parcela semanal ainda não contada. Essa lógica depende da jornada, compensação e comando do caso.

Separar faixas de 50%, 100% e percentuais convencionais. Não transformar todas as horas trabalhadas em feriado em “hora extra de 100%” sem analisar o pagamento da jornada normal e a dobra.

### 21. Compensação e banco de horas

Reconstruir saldo inicial, créditos, débitos, limite, janela de compensação, expiração e saldo rescisório. Comprovar autorização e validade do regime no período.

Compensação semanal e banco de horas não são a mesma operação. Invalidade pode gerar hora integral em uma faixa e apenas adicional em outra; a consequência jurídica deve preceder a fórmula. Não aplicar entendimento anterior à reforma a todos os períodos sem exame.

Auditar horas “compensadas” em férias, afastamentos ou dias que já eram de folga; conversões por fatores convencionais; saldos transferidos sem lastro; descontos de saldo negativo sem autorização aplicável. [CLT, arts. 59 e 59-B](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm).

### 22. Minutos residuais e tempo à disposição

Conferir tolerâncias legais, limite diário, deslocamentos internos obrigatórios, uniformização obrigatória, espera e atividades particulares. Tolerância de registro não é autorização para excluir qualquer período pequeno.

Não descontar automaticamente cinco minutos de cada marcação como franquia. Aplicar a regra de tolerância ao conjunto relevante e a consequência fixada no título. Separar regime anterior e posterior à reforma; verificar cancelamento de enunciados antigos.

Horas de deslocamento residência-trabalho exigem exame histórico e normativo; não presumir direito atual geral a horas in itinere. [CLT, arts. 4º e 58](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm).

### 23. Adicional noturno

No regime urbano comum: período de 22h às 5h, adicional mínimo de 20% e hora reduzida de 52min30s. Categorias e normas podem alterar o tratamento.

`horas noturnas fictas = minutos noturnos computáveis ÷ 52,5`.

`adicional noturno = horas noturnas fictas × salário-hora × percentual`.

Na HE noturna, verificar integração do adicional na base da HE e eventual pagamento separado já realizado. A prorrogação após as 5h requer análise da jornada, norma coletiva, regime 12×36 e título. Não reduzir novamente uma quantidade já convertida. [CLT, art. 73](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm).

### 24. Intrajornada

Registrar duração exigível, duração concedida e supressão efetiva. Jornada superior a seis horas e jornada entre quatro e seis têm regras distintas; negociação e situações especiais precisam de exame.

Para fatos posteriores à reforma, o art. 71, § 4º, prevê pagamento do período suprimido, com acréscimo de 50% e natureza indenizatória. Para fatos anteriores, estudar o regime histórico e o título, inclusive pagamento integral e reflexos quando cabíveis.

Não usar a antiga Súmula 437 como se permanecesse vigente: ela integra os cancelamentos de 2025. Cancelamento não dispensa reconstrução da disciplina histórica. [CLT, art. 71](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm); [TRT2, cancelamentos](https://ww2.trt2.jus.br/noticias/noticias/noticia/tst-cancela-sumulas-e-ojs-remete-dez-temas-para-irr-e-suspende-um-tema-saiba-mais).

### 25. Interjornada, repouso semanal e pausas especiais

No regime comum, confrontar intervalo entre jornadas com as 11 horas do art. 66 e repouso semanal de 24 horas do art. 67. Identificar separadamente violações e evitar somar duas vezes o mesmo déficit sem base jurídica.

Consequência remuneratória, natureza e reflexos do descumprimento devem ser validados por período e título; não copiar automaticamente a regra da intrajornada. A OJ 355 também foi objeto de cancelamento em 2025.

Pausas de digitação, mecanografia, frigorífico, recuperação térmica, teleatendimento e outras dependem de enquadramento e fonte específica. Apurar quantidade de pausas devidas, concedidas e suprimidas; presença do trabalhador em atividade não prova por si só enquadramento técnico. [CLT, arts. 66, 67, 72 e 253](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm).

### 26. Domingos, feriados e calendário

Manter calendário de feriados nacionais, estaduais e municipais do local efetivo de trabalho. Ponto facultativo não é automaticamente feriado no setor privado. Escalas podem deslocar o repouso.

Distinguir: trabalho em repouso sem compensação; horas extras no mesmo dia; remuneração normal já incluída no mensal; adicional convencional. O valor ainda devido depende do que foi pago e de como o título determinou a dobra.

Não contar feriado que coincide com domingo duas vezes no multiplicador do RSR. Não presumir que todo sábado é repouso. Guardar a lei local ou a cláusula usada. Referência normativa: Lei 605/1949 e regime contratual aplicável.

### 27. RSR sobre parcelas variáveis

Esquema usual, quando adequado ao regime: `RSR variável = valor variável elegível ÷ dias úteis considerados × repousos/feriados considerados`.

Definir o tratamento dos sábados, faltas, feriados coincidentes, meses parciais e escalas. A fração 1/6 não é universal. Mensalista já tem o repouso da remuneração fixa incluído no salário; isso não afasta automaticamente RSR sobre verbas variáveis.

Guardar demonstrativo do calendário junto à conta. O erro no denominador pode se propagar para férias, 13º, aviso e FGTS.

### 28. Reflexos do RSR majorado pelas horas extras

O Tema 9 do TST alterou o tratamento da repercussão do RSR majorado pelas horas extras habituais em férias, 13º, aviso e FGTS, com aplicação às horas extras trabalhadas a partir de **20/03/2023**. O critério temporal refere-se ao trabalho, não ao ajuizamento.

Operação: separar horas extras por período; calcular o RSR correspondente; permitir repercussão subsequente conforme título e modulação. O RSR majorado não pode voltar à base que o gerou, criando cálculo circular.

Fontes: [Informativo TST 269](https://juslaboris.tst.jus.br/handle/20.500.12178/213493?show=full) e [boletim oficial do TRT3 sobre o Tema 9](https://portal.trt3.jus.br/internet/jurisprudencia/boletim-de-precedentes-trt-mg/download/45___Boletim_de_Precedentes_Marco_2023.pdf).

### 29. Escala 12×36, turnos e jornadas especiais

Identificar autorização, período legislativo, efetiva escala, intervalo, trocas, plantões extras e norma coletiva. No 12×36, não aplicar automaticamente regras comuns de domingos, feriados e prorrogação noturna: o art. 59-A contém disciplina específica que precisa ser cotejada com o caso.

Turnos ininterruptos de revezamento: identificar alternância efetiva, limite reconhecido, negociação e divisor. Jornada especial não se define apenas pelo nome do cargo.

Evitar presumir validade ou invalidade global da escala porque houve uma ocorrência extraordinária. Quantificar o cenário determinado judicialmente. [CLT, art. 59-A](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm).

### 30. Sobreaviso, prontidão, externo e teletrabalho

Disponibilidade por telefone não basta, por si só, para configurar sobreaviso. Verificar restrição, escala, possibilidade de convocação e título. Quando aplicáveis os parâmetros ferroviários ou sua extensão reconhecida, sobreaviso e prontidão têm frações distintas; não usar percentuais sem confirmar base e enquadramento.

Separar horas de disponibilidade das efetivamente trabalhadas para evitar duplicidade. Trabalho externo e teletrabalho não implicam exclusão automática do controle de jornada: examinar requisitos do art. 62 e alterações da disciplina do teletrabalho. [CLT, arts. 62, 75-B e 244](https://www.planalto.gov.br/ccivil_03/decreto-lei/del5452compilado.htm).
