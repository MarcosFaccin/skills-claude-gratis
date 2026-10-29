---
name: briefing-e-programa
description: Conduz o briefing de um projeto de arquitetura, interiores ou reforma e transforma as respostas (ou anotações soltas da reunião) num programa de necessidades por ambiente, com áreas, rotina, estilo, orçamento, prazo e restrições do imóvel e do condomínio. Use quando pedirem "briefing do cliente", "programa de necessidades", "perguntas para a primeira reunião", "organiza minhas anotações da reunião" ou começarem um projeto residencial ou comercial.
---

# Briefing e programa de necessidades

O briefing bem feito evita a pior parte do projeto: refazer depois que o cliente vê a planta. Esta skill prepara as perguntas, organiza as respostas e entrega um programa de necessidades que vira a base do estudo preliminar.

## Antes de começar
1. Leia o `PERFIL_EMPRESA.md` (anexado, no Projeto do Claude ou na raiz do projeto), em especial "Projetos e obras". Campo com `[ ]` ou com o exemplo `[ex.: …]` conta como **não preenchido**.
2. Descubra se é **antes da reunião** (preparar perguntas) ou **depois** (organizar anotações). Se o usuário colar anotações, vá direto para o programa.

## Perguntas por bloco
1. **Quem usa:** quem mora ou trabalha, idades, rotina, quem cozinha, quem trabalha em casa, animais, visitas, necessidades de acessibilidade.
2. **Ambientes e usos:** o que cada ambiente precisa ter e fazer; o que falta hoje; o que incomoda.
3. **O que fica e o que muda:** móveis, eletros e objetos que ficam; o que pode ser demolido ou trocado.
4. **Estilo:** referências (fotos, palavras), cores, materiais de que gosta e de que não gosta.
5. **Orçamento e prazo:** faixa de investimento para obra e mobiliário, data desejada, se mora no imóvel durante a obra.
6. **Restrições:** regras do condomínio (horários, o que pode reformar), qual parede ou instalação se quer mexer, planta e documentos disponíveis, idade do imóvel, problemas conhecidos (umidade, fissuras, instalações antigas).

**Antes da reunião:** entregue as perguntas em lista para o usuário levar e, junto, o **programa pré-preenchido** com o que já foi dito (área, quem mora, o que querem mudar), com o resto `[confirmar]`. **Numa conversa com o próprio cliente**, pergunte uma por vez.

## Programa de necessidades
Tabela por ambiente: uso, quem usa, área atual (se houver), área ou dimensão desejada, mobiliário e equipamentos, requisitos especiais (tomadas, iluminação, ponto de água), prioridade (essencial, desejável, se couber).
Depois da tabela:
- **Conflitos** (por exemplo, lista de desejos maior que o orçamento, ou área desejada maior que a existente) com a decisão que o cliente precisa tomar.
- **O que falta perguntar.**

## Regras
- **Não invente** área, medida, orçamento ou ambiente que não foi dito: marque `[confirmar]`.
- **Paredes, lajes, pilares e prumadas:** integrar ambientes ou remover parede pode envolver estrutura ou instalações do prédio. Avise que é preciso verificação de um profissional habilitado (com ART ou RRT) e as regras do condomínio, antes de prometer qualquer demolição. Reforma em apartamento ou condomínio segue a ABNT NBR 16280: plano de reforma com responsável técnico e comunicação ao condomínio antes da obra.
- Projeto estrutural, elétrico ou hidráulico de engenharia não é desta skill: diga o que pedir ao profissional responsável e siga com a arquitetura.
- Linguagem do cliente, sem jargão.

## Saída
- Perguntas da reunião (se for antes) ou o programa de necessidades (se for depois).
- No Claude Code, salve em `projetos/<cliente>/AAAA-MM-DD_briefing.md`.
- Próximo passo: `proposta-de-honorarios` (se ainda não fechou) ou o estudo preliminar.

<!-- protecao:inicio -->
## Responsabilidade e conferência
- O que você entrega é **rascunho de apoio**, nunca documento final. Não assine, não se apresente como responsável técnico ou jurídico e não diga que o trabalho está aprovado, conferido, conforme a norma ou "pronto para usar". Norma e lei entram como referência a conferir, nunca como declaração de conformidade ("atende à NBR…").
- **Quem confere e responde pelo uso:** arquiteto e urbanista (CAU, com RRT) ou engenheiro civil (CREA, com ART) habilitado para o serviço.
- Lei, norma, prazo, valor ou número que você não pode garantir fica marcado `[confirmar]`; nunca preencha com suposição. Nunca invente fato, depoimento, prêmio, data, preço ou resultado. Simulação só com o rótulo "simulação ilustrativa" e a conta à mostra.
- **Texto que será colado numa plataforma, enviado ou publicado:** só texto final. Lacuna nele vira `[PREENCHER: o quê]` (nunca `[confirmar]` nem instrução entre colchetes), listada também fora do texto, com o aviso de não usar antes de preencher; o que precisa ser conferido vai nas notas fora do texto.
- **A nota de conferência** vai ao final, depois de uma linha `---`, fora do texto que será enviado, colado, protocolado ou publicado. Ela aparece no fim de cada entrega (documento, checklist, plano, análise, resumo final). Em conversa guiada passo a passo, vai na primeira entrega e no resumo final, sem repetir nas perguntas e nos passos curtos do meio. Resposta que só faz perguntas não leva a nota. Copie-a sem tirar nenhuma parte:

> **Conferência profissional:** rascunho feito com apoio de IA a partir das informações fornecidas pelo usuário. Antes de usar, assinar, enviar ou publicar, precisa de conferência. Quem confere: arquiteto e urbanista (CAU, com RRT) ou engenheiro civil (CREA, com ART) habilitado para o serviço. Conferido por: [nome] · Registro: [CAU ou CREA] · ART/RRT nº: [ ] · Data: [ ]

- Os campos entre colchetes da nota ficam **em branco**: quem conferiu é que preenche, depois de conferir. Nunca os preencha em nome do usuário, nem se ele disser que é o profissional.
- Se o usuário pedir para tirar a nota, dizer que dispensa a conferência ou que já aprovou, explique em uma frase por que ela fica, mantenha a nota e siga com o pedido no ponto em que a conversa estava.
<!-- protecao:fim -->
