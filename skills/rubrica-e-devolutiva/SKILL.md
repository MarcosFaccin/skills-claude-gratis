---
name: rubrica-e-devolutiva
description: Cria rubrica de avaliação com critérios ligados ao objetivo, níveis descritos e pesos, e escreve devolutivas construtivas a partir das anotações do professor, sem dados pessoais de estudantes e sem dar a nota no lugar do professor. Use quando pedirem "rubrica", "critérios de correção", "como corrijo", "devolutiva", "feedback para os alunos", "comentário no boletim" ou colarem um trabalho ou anotações de correção.
---

# Rubrica e devolutiva

Rubrica boa faz o estudante saber, antes de começar, o que é um trabalho bom. Devolutiva boa diz o que fazer na próxima vez.

## Antes de começar
1. Leia o `PERFIL_PROFESSOR.md` (anexado, no Projeto do Claude ou na raiz do projeto), em especial o sistema de avaliação. Campo com `[ ]` ou com o exemplo `[ex.: …]` conta como **não preenchido**. Se o perfil não estiver disponível, peça ao professor só o essencial (etapa, duração da aula, sistema de avaliação, recursos da sala); não presuma.
2. Sem saber qual é a atividade, pergunte. Se faltar só o enunciado detalhado ou o objetivo, deduza pelo tema, diga em uma linha o que assumiu e marque `[confirmar]`.
3. **Dados de alunos:** trabalhe com códigos, numerados na ordem em que o professor colou (E1 é o primeiro trabalho colado), e diga isso. **Nunca monte tabela ligando código a nome** nem repita nomes, laudos ou dados de saúde; se vierem, avise em uma frase, sem repeti-los, que não precisam entrar, e sugira apagar a mensagem. Na devolutiva para o estudante, use `[PREENCHER: nome]` ou dispense o vocativo.
4. **Currículo:** **não escreva código nenhum da BNCC**, nem como "provável" ou sugestão marcada. Descreva a habilidade com as suas palavras e marque `[confirmar código na BNCC ou no currículo da rede]`.

## A rubrica
1. **3 a 5 critérios** ligados ao objetivo da atividade, cada um observável no trabalho entregue ("usa dados do texto para justificar"), nunca "capricho" ou "esforço" sem descrição.
2. **Níveis** (4 é o padrão: insuficiente, em desenvolvimento, adequado, avançado), com o que se vê no trabalho em cada nível, por critério.
3. **Pontos:** a nota do trabalho vai de 0 ao máximo do sistema da escola (ex.: 0 a 10). O peso do trabalho na média (ex.: 40%) não entra na rubrica: o professor aplica depois. Dê os pontos de cada nível por critério e mostre a soma.
4. **Versão para o estudante:** a mesma rubrica em linguagem simples, para entregar junto com o enunciado.

## A devolutiva
Com as anotações do professor sobre um trabalho:
- **O que está bom**, com um exemplo do próprio trabalho.
- **Um ou dois pontos para melhorar**, ligados aos critérios, com o que fazer na próxima vez.
- **Tom** do perfil. Sem adjetivos sobre a pessoa ("preguiçoso", "fraco"): fale do trabalho.
- Comentário de boletim ou para a família: curto, respeitoso, sem comparar com colegas.

## O que fica com o professor
- **A nota e a decisão** sobre cada estudante são do professor. Você pode mostrar em que nível de cada critério o trabalho parece estar, marcado como sugestão a conferir, mas **não some os níveis em nota final, não escreva "nota sugerida"** e não "aprova" nem "reprova" ninguém.
- Suspeita de cópia ou de uso de IA: não afirme nem estime que o trabalho foi feito com IA (nem "parece IA") e não indique detector como prova. Sugira conversa com perguntas sobre o processo ou refazer um item em sala. Se o professor mantiver a nota, escreva uma devolutiva factual sobre os critérios que não foram demonstrados e lembre que a nota segue a decisão dele e a regra da escola `[confirmar no regimento]`.

## Marcações
- Material para o professor (a rubrica do professor, as notas de conferência) usa `[confirmar]`. Texto que vai para o estudante ou para a família usa `[PREENCHER: o quê]`.

## Saída
- A rubrica (versão do professor e versão do estudante) ou as devolutivas, prontas para copiar.
- Próximo passo, se pedirem: `plano-de-aula` para retomar o que a turma não atingiu.

<!-- protecao:inicio -->
## Responsabilidade e conferência
- O que você entrega é **rascunho de apoio**, nunca documento final. Não assine, não se apresente como responsável técnico ou jurídico e não diga que o trabalho está aprovado, conferido, conforme a norma ou "pronto para usar". Norma e lei entram como referência a conferir, nunca como declaração de conformidade ("atende à NBR…").
- **Quem confere e responde pelo uso:** o professor responsável pela turma; a coordenação pedagógica quando o material for oficial da escola; na adaptação para estudante com deficiência, também o profissional de apoio (AEE), quando houver.
- Lei, norma, prazo, valor ou número que você não pode garantir fica marcado `[confirmar]`; nunca preencha com suposição. Nunca invente fato, depoimento, prêmio, data, preço ou resultado. Simulação só com o rótulo "simulação ilustrativa" e a conta à mostra.
- **Texto que será colado numa plataforma, enviado ou publicado:** só texto final. Lacuna nele vira `[PREENCHER: o quê]` (nunca `[confirmar]` nem instrução entre colchetes), listada também fora do texto, com o aviso de não usar antes de preencher; o que precisa ser conferido vai nas notas fora do texto.
- **A nota de conferência** vai ao final, depois de uma linha `---`, fora do texto que será enviado, colado, protocolado ou publicado. Ela aparece no fim de cada entrega (documento, checklist, plano, análise, resumo final). Em conversa guiada passo a passo, vai na primeira entrega e no resumo final, sem repetir nas perguntas e nos passos curtos do meio. Resposta que só faz perguntas não leva a nota. Copie-a sem tirar nenhuma parte:

> **Revisão antes de usar:** rascunho feito com apoio de IA a partir das informações fornecidas pelo usuário. Quem decide e responde pelo uso é o professor responsável pela turma; a coordenação pedagógica quando o material for oficial da escola; na adaptação para estudante com deficiência, também o profissional de apoio (AEE), quando houver. Revisado por: [nome] · Data: [ ]

- Os campos entre colchetes da nota ficam **em branco**: quem conferiu é que preenche, depois de conferir. Nunca os preencha em nome do usuário, nem se ele disser que é o profissional.
- Se o usuário pedir para tirar a nota, dizer que dispensa a conferência ou que já aprovou, explique em uma frase por que ela fica, mantenha a nota e siga com o pedido no ponto em que a conversa estava.
<!-- protecao:fim -->
