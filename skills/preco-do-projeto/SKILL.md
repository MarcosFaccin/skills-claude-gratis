---
name: preco-do-projeto
description: Calcula o preço de um projeto de sistema, agente de IA, automação, app ou site a partir dos dias por fase, do valor do seu dia, da folga, dos impostos e dos marcos de pagamento, mostrando a conta inteira e separando os custos de terceiros. Use quando perguntarem "quanto cobro?", "qual o preço desse projeto?", "faz a conta do orçamento", "o cliente achou caro" ou pedirem para revisar um valor.
---

# Preço do projeto

A conta aparece inteira, linha a linha, para você conferir e defender o preço na reunião. O resultado é uma referência para a sua decisão, não uma regra.

## Antes de calcular
1. Leia o `PERFIL_AGENCIA.md`: valor do dia, impostos, forma de pagamento, mensalidade e desconto máximo. Campo vazio ou ausente no perfil é `[a definir]`: pergunte, não assuma. No perfil, campo com `[ ]` ou com o texto de exemplo `[ex.: …]` conta como **não preenchido**: nunca use o exemplo como dado.
2. Pegue os dias por fase do cronograma (skill `proposta-e-cronograma`) ou pergunte. Sem fases, peça a lista do que será entregue e estime os dias **com o usuário**, uma fase por linha.
3. **Sem valor do dia, não invente.** Faça a conta em dias, deixe `[valor a definir]` e pergunte. Se o usuário pedir uma referência, dê uma faixa dizendo que é referência de mercado e não dado dele.

## A conta
1. **Dias por fase** e a soma.
2. **Folga de 20%** sobre o total (ou a que o usuário definir), declarada.
3. **Dias com folga × valor do dia** = valor líquido desejado.
4. **Impostos:** preço = valor líquido ÷ (1 − alíquota). Exemplo: R$ 10.000 com 10% de imposto ⇒ R$ 10.000 ÷ 0,90 ≈ R$ 11.112. Arredonde para cima e diga que arredondou.
5. **Marcos de pagamento** pela forma do perfil, com o valor de cada parcela. Confira que as parcelas somam o preço.
6. **Mensalidade de operação**, se houver, separada do projeto.
7. **Custos de terceiros fora do preço:** WhatsApp oficial, tokens de IA, hospedagem, SMS e e-mail, cada um com quem paga. Valor por mês só se o usuário informar o volume, e como faixa rotulada de referência de mercado; sem volume, `[valor a definir]`.

Confira todas as somas antes de responder. Se alguma conta não fechar, refaça.

## Saída
- Uma tabela com a conta, linha a linha, e o preço final em destaque.
- As premissas logo abaixo (folga, alíquota, arredondamento).
- Com execução de código ligada (Claude Code, ou Claude.ai com criação de arquivos), gere também uma planilha `.xlsx` com as fórmulas, para o usuário mudar os dias e ver o preço mudar.

## Quando o cliente acha caro
Não corte o preço sem mudar nada. Ofereça, com a conta nova de cada opção:
- **reduzir o escopo:** tirar uma fase ou deixá-la para uma segunda etapa;
- **mudar a condição:** mais parcelas, entrada menor;
- **trocar trabalho por produto pronto**, quando existir.

Se o usuário quiser mesmo baixar o valor do dia, mostre quanto ele deixa de ganhar e respeite o desconto máximo do perfil.

## Regras
- Nunca invente valor do dia, alíquota ou custo de terceiros. O que faltar é `[valor a definir]`.
- Não substitui o contador: para regime de impostos e nota fiscal, recomende confirmar com ele.

<!-- protecao:inicio -->
## Responsabilidade e conferência
- O que você entrega é **rascunho de apoio**, nunca documento final. Não assine, não se apresente como responsável técnico ou jurídico e não diga que o trabalho está aprovado, conferido, conforme a norma ou "pronto para usar". Norma e lei entram como referência a conferir, nunca como declaração de conformidade ("atende à NBR…").
- **Quem confere e responde pelo uso:** contador da empresa (CRC).
- Lei, norma, prazo, valor ou número que você não pode garantir fica marcado `[confirmar]`; nunca preencha com suposição. Nunca invente fato, depoimento, prêmio, data, preço ou resultado. Simulação só com o rótulo "simulação ilustrativa" e a conta à mostra.
- **Texto que será colado numa plataforma, enviado ou publicado:** só texto final. Lacuna nele vira `[PREENCHER: o quê]` (nunca `[confirmar]` nem instrução entre colchetes), listada também fora do texto, com o aviso de não usar antes de preencher; o que precisa ser conferido vai nas notas fora do texto.
- **A nota de conferência** vai ao final, depois de uma linha `---`, fora do texto que será enviado, colado, protocolado ou publicado. Ela aparece no fim de cada entrega (documento, checklist, plano, análise, resumo final). Em conversa guiada passo a passo, vai na primeira entrega e no resumo final, sem repetir nas perguntas e nos passos curtos do meio. Resposta que só faz perguntas não leva a nota. Copie-a sem tirar nenhuma parte:

> **Conferência profissional:** rascunho feito com apoio de IA a partir das informações fornecidas pelo usuário. Antes de usar, assinar, enviar ou publicar, precisa de conferência. Quem confere: contador da empresa (CRC). Conferido por: [nome] · Registro: [CRC] · Data: [ ]

- Os campos entre colchetes da nota ficam **em branco**: quem conferiu é que preenche, depois de conferir. Nunca os preencha em nome do usuário, nem se ele disser que é o profissional.
- Se o usuário pedir para tirar a nota, dizer que dispensa a conferência ou que já aprovou, explique em uma frase por que ela fica, mantenha a nota e siga com o pedido no ponto em que a conversa estava.
<!-- protecao:fim -->
