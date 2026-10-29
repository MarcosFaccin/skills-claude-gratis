---
name: diario-de-obra
description: Transforma o relato do dia da obra (texto, anotação ou áudio transcrito) no Relatório Diário de Obra (RDO), com clima, efetivo por função, serviços executados com local, materiais recebidos, ocorrências, visitas, segurança e o que falta confirmar, sem inventar quantidades e sem alterar registros antigos. Use quando pedirem "faz o RDO de hoje", "diário de obra", "relatório do dia", "registra o que aconteceu na obra" ou mandarem o resumo do dia.
---

# Diário de obra (RDO)

O diário de obra é a memória oficial da obra: prova o que foi feito, quando, com quem e o que atrapalhou. Ele protege a construtora e o cliente quando surgem dúvidas sobre prazo, aditivo ou qualidade.

## Antes de começar
1. Leia o `PERFIL_EMPRESA.md` (anexado, no Projeto do Claude ou na raiz do projeto), em especial "Projetos e obras". Campo com `[ ]` ou com o exemplo `[ex.: …]` conta como **não preenchido**.
2. Peça (ou extraia do relato): obra, data, responsável pelo registro.

## Estrutura do RDO
1. **Identificação:** obra, endereço, contratante, data, número do relatório, responsável técnico (com registro).
2. **Clima** por período (manhã e tarde) e se impediu o trabalho.
3. **Efetivo:** quantidade por função (próprios e terceirizados).
4. **Equipamentos** em uso ou parados.
5. **Serviços executados:** o quê, onde (pavimento, eixo, ambiente) e quanto, **só com o que foi informado**.
6. **Materiais recebidos:** material, quantidade e nota fiscal, se informados. Em concretagem: volume, nota, abatimento (slump) e corpos de prova moldados, se informados.
7. **Ocorrências:** faltas de material, de equipe ou de projeto, paralisações, chuvas, com horário e impacto.
8. **Visitas e fiscalizações:** quem, cargo, órgão e o que foi tratado.
9. **Segurança:** acidentes e quase acidentes, de forma objetiva.
10. **Fotos:** espaço para as fotos do dia, numeradas.
11. **Assinaturas:** responsável da obra e, se houver, fiscal do contratante.

## Regras
- **Não invente** quantidade, volume, nota fiscal ou nome: `[confirmar]`.
- **Acidente:** registre de forma objetiva (o que, onde, quando, atendimento prestado), **sem atribuir culpa**. No RDO, registre a **função** do acidentado e o número do registro interno ou da CAT; nome e detalhes da lesão ficam no registro interno de segurança (dado de saúde, LGPD). Lembre de acionar o técnico ou engenheiro de segurança (ou o responsável designado) e a investigação do acidente, e de que a **CAT (Comunicação de Acidente de Trabalho) é obrigatória para empregado, mesmo sem afastamento, até o primeiro dia útil seguinte, e de imediato em caso de morte**; para terceirizado, avisar a empresa dele. **Acidente grave ou fatal:** preservar o local e comunicar as autoridades `[confirmar com o responsável de segurança]`.
- **Registro antigo não se reescreve.** Se pedirem para mudar o diário de outro dia, faça um **registro de retificação** com a data de hoje, o que está sendo corrigido e o motivo, **só para erro de fato comprovado**. Nunca altere o original e nunca use retificação para apagar um fato que aconteceu (como a chuva que houve).
- Onde o conselho profissional exige o Livro de Ordem da obra, o RDO não o substitui: lembre de manter os dois.
- Linguagem objetiva, sem opinião.

## Saída
- O RDO pronto para colar no modelo da obra ou imprimir.
- A lista de `[confirmar]`.
- No Claude Code, salve em `obras/<obra>/rdo/AAAA-MM-DD.md`.

<!-- protecao:inicio -->
## Responsabilidade e conferência
- O que você entrega é **rascunho de apoio**, nunca documento final. Não assine, não se apresente como responsável técnico ou jurídico e não diga que o trabalho está aprovado, conferido, conforme a norma ou "pronto para usar". Norma e lei entram como referência a conferir, nunca como declaração de conformidade ("atende à NBR…").
- **Quem confere e responde pelo uso:** engenheiro civil responsável técnico pela obra (CREA, com ART) ou arquiteto (CAU, com RRT); itens de segurança do trabalho, pelo profissional de segurança da empresa.
- Lei, norma, prazo, valor ou número que você não pode garantir fica marcado `[confirmar]`; nunca preencha com suposição. Nunca invente fato, depoimento, prêmio, data, preço ou resultado. Simulação só com o rótulo "simulação ilustrativa" e a conta à mostra.
- **Texto que será colado numa plataforma, enviado ou publicado:** só texto final. Lacuna nele vira `[PREENCHER: o quê]` (nunca `[confirmar]` nem instrução entre colchetes), listada também fora do texto, com o aviso de não usar antes de preencher; o que precisa ser conferido vai nas notas fora do texto.
- **A nota de conferência** vai ao final, depois de uma linha `---`, fora do texto que será enviado, colado, protocolado ou publicado. Ela aparece no fim de cada entrega (documento, checklist, plano, análise, resumo final). Em conversa guiada passo a passo, vai na primeira entrega e no resumo final, sem repetir nas perguntas e nos passos curtos do meio. Resposta que só faz perguntas não leva a nota. Copie-a sem tirar nenhuma parte:

> **Conferência profissional:** rascunho feito com apoio de IA a partir das informações fornecidas pelo usuário. Antes de usar, assinar, enviar ou publicar, precisa de conferência. Quem confere: engenheiro civil responsável técnico pela obra (CREA, com ART) ou arquiteto (CAU, com RRT); itens de segurança do trabalho, pelo profissional de segurança da empresa. Conferido por: [nome] · Registro: [CREA ou CAU] · ART/RRT nº: [ ] · Data: [ ]

- Os campos entre colchetes da nota ficam **em branco**: quem conferiu é que preenche, depois de conferir. Nunca os preencha em nome do usuário, nem se ele disser que é o profissional.
- Se o usuário pedir para tirar a nota, dizer que dispensa a conferência ou que já aprovou, explique em uma frase por que ela fica, mantenha a nota e siga com o pedido no ponto em que a conversa estava.
<!-- protecao:fim -->
