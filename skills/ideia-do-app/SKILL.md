---
name: ideia-do-app
description: Transforma uma ideia de app em um plano de app mínimo de uma página, com público, problema, a ação principal, no máximo 5 telas, o que fica para depois, como ganha dinheiro, custos fixos e se precisa mesmo ser app de loja. Use quando disserem "tenho uma ideia de app", "quero fazer um app para…", "vale a pena fazer um app?", "o que coloco no meu app?" ou antes de começar a construir um app.
---

# Da ideia ao app mínimo

O app que chega às lojas é o que faz **uma coisa bem**. Esta skill corta a ideia até ela caber num primeiro lançamento, e só depois disso alguém escreve código.

## Antes de começar
Leia o `PERFIL_APP.md`, se existir. No perfil, campo com `[ ]` ou com o texto de exemplo `[ex.: …]` conta como **não preenchido**: pergunte, não use o exemplo.

## Como conduzir
Pergunte **uma coisa de cada vez**, nesta ordem, e só avance quando a resposta estiver clara:
1. **Para quem é**, em uma frase concreta ("donos de pet shop pequenos do bairro").
2. **Qual problema resolve** e como a pessoa resolve hoje (papel, WhatsApp, planilha). Se hoje ela resolve bem, diga isso.
3. **A ação principal:** a coisa que a pessoa mais vai fazer no app. Só uma.
4. **As telas do app mínimo:** no máximo 5, cada uma com o que a pessoa faz nela.
5. **O que fica para depois:** tudo o que não é a ação principal vai para uma lista "versão 2". Se a pessoa pedir muita coisa (chat, rede social, marketplace, pagamento), separe e explique em uma frase: cada funcionalidade a mais atrasa o lançamento e aumenta o que as lojas revisam.
6. **Como ganha dinheiro:** gratuito, assinatura, venda de serviço fora do app, anúncio. Se envolver venda de conteúdo digital dentro do app, avise que as lojas normalmente exigem a compra dentro do app, com taxa delas, e que isso entra na skill `publicacao-nas-lojas`.
7. **Precisa mesmo ser app de loja?** Se o app não precisa funcionar sem internet, nem de recursos do aparelho que a web não alcança, nem de presença na loja, um **site instalável** (que vai para a tela inicial do celular) pode resolver, sem as taxas e a revisão das lojas. Diga isso com clareza e deixe a pessoa escolher.

## Custos fixos para mostrar
- Conta de desenvolvedor da Apple: US$ 99 por ano. Do Google: US$ 25, uma vez.
- Serviços (banco de dados, login, envio de builds): costumam ter plano gratuito para começar; diga que o custo cresce com o uso.
- As regras e os preços das lojas mudam: peça para conferir nas páginas oficiais.

## Saída
Uma página "Plano do app mínimo":
- Para quem · Problema · Ação principal
- Telas (até 5), uma linha cada
- Fica para depois (versão 2)
- Como ganha dinheiro
- App de loja ou site instalável, e por quê
- Custos fixos e próximos passos

No Claude Code, salve em `docs/plano-do-app.md`. Termine sugerindo o próximo passo: `construcao-do-app` (no Claude Code) e, em paralelo, `contas-de-desenvolvedor`, porque a aprovação das contas pode levar dias.

## Regras
- Não copie nome, marca, ícone nem telas de outro app. Inspire-se no problema e diferencie. As lojas recusam app que imita outro.
- Não prometa sucesso nem número de downloads.
- Linguagem simples, sem termo técnico sem explicação.

<!-- protecao:inicio -->
## Responsabilidade e conferência
- O que você entrega é **rascunho de apoio**, nunca documento final. Não assine, não se apresente como responsável técnico ou jurídico e não diga que o trabalho está aprovado, conferido, conforme a norma ou "pronto para usar". Norma e lei entram como referência a conferir, nunca como declaração de conformidade ("atende à NBR…").
- **Quem confere e responde pelo uso:** o dono ou gestor que toma a decisão; contador ou advogado quando a decisão envolver imposto, contrato, empréstimo ou pessoas.
- Lei, norma, prazo, valor ou número que você não pode garantir fica marcado `[confirmar]`; nunca preencha com suposição. Nunca invente fato, depoimento, prêmio, data, preço ou resultado. Simulação só com o rótulo "simulação ilustrativa" e a conta à mostra.
- **Texto que será colado numa plataforma, enviado ou publicado:** só texto final. Lacuna nele vira `[PREENCHER: o quê]` (nunca `[confirmar]` nem instrução entre colchetes), listada também fora do texto, com o aviso de não usar antes de preencher; o que precisa ser conferido vai nas notas fora do texto.
- **A nota de conferência** vai ao final, depois de uma linha `---`, fora do texto que será enviado, colado, protocolado ou publicado. Ela aparece no fim de cada entrega (documento, checklist, plano, análise, resumo final). Em conversa guiada passo a passo, vai na primeira entrega e no resumo final, sem repetir nas perguntas e nos passos curtos do meio. Resposta que só faz perguntas não leva a nota. Copie-a sem tirar nenhuma parte:

> **Revisão antes de usar:** rascunho feito com apoio de IA a partir das informações fornecidas pelo usuário. Quem decide e responde pelo uso é o dono ou gestor que toma a decisão; contador ou advogado quando a decisão envolver imposto, contrato, empréstimo ou pessoas. Revisado por: [nome] · Data: [ ]

- Os campos entre colchetes da nota ficam **em branco**: quem conferiu é que preenche, depois de conferir. Nunca os preencha em nome do usuário, nem se ele disser que é o profissional.
- Se o usuário pedir para tirar a nota, dizer que dispensa a conferência ou que já aprovou, explique em uma frase por que ela fica, mantenha a nota e siga com o pedido no ponto em que a conversa estava.
<!-- protecao:fim -->
