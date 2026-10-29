---
name: procedimento-padrao
description: Transforma o jeito como uma tarefa é feita hoje (explicação falada, áudio transcrito, anotação ou passo a passo bagunçado) em procedimento padrão (POP/SOP) com responsável, passos numerados, checklist e o que fazer quando der errado. Use quando pedirem POP, SOP, manual de processo, "documentar como se faz", checklist de rotina ou treinamento de funcionário novo.
---

# Procedimento padrão (POP)

Se existir `PERFIL_EMPRESA.md` (na pasta do projeto ou anexado na conversa), leia-o primeiro e use as seções "Identificação", "Equipe e contratação" (quem aprova) e "Ferramentas que a empresa usa". Só pergunte à pessoa o que o perfil não trouxer. Campo do perfil com `[ ]` ou com o exemplo `[ex.: …]` conta como **não preenchido**: pergunte em vez de usar o exemplo.

## Entrada
A pessoa conta como faz a tarefa, do jeito que conseguir. Se ela descreveu os passos, escreva o POP e ponha o que faltar em "Perguntas em aberto". Se ela só deu o tema, pergunte antes, **de uma vez** (até 5): 1) como você faz hoje, passo a passo; 2) quem faz e quem substitui; 3) o que dispara a tarefa e com que frequência; 4) sistemas e arquivos usados; 5) o erro mais comum.

## Estrutura do POP
1. **Título e código:** `POP-[ÁREA]-[NN]`, por exemplo `POP-FIN-01 Emitir nota fiscal de serviço`.
2. **Objetivo:** uma frase com o resultado esperado.
3. **Quando fazer:** o gatilho (todo dia 5, a cada pedido aprovado...).
4. **Responsável e substituto.**
5. **O que precisa ter à mão:** acessos, arquivos, modelos.
6. **Passo a passo:** numerado, um verbo no começo de cada passo, um passo por ação. Onde houver decisão, use "Se..., então...".
7. **Checklist final:** de 3 a 7 itens para conferir antes de dar por encerrado.
8. **Quando der errado:** os problemas que a pessoa citou e o que fazer em cada um; os que você imaginar vão marcados `[sugestão, confirmar]`.
9. **Tempo médio** e **versão** (data e quem revisou).

## Saída
- O POP pronto para imprimir ou colar no sistema da empresa.
- Uma versão "cartão de bolso" com até 7 linhas, para deixar perto de quem executa.
- Perguntas em aberto: o que a pessoa não soube responder.
- No Claude Code, salve em `SAIDA/POP-AREA-NN_titulo.md`.

## Regras
- Escreva para alguém que nunca fez a tarefa e vai fazer sozinho amanhã.
- Não invente passo, sistema ou regra que a pessoa não descreveu; o que parecer faltar vira pergunta.
- Nunca coloque senha no POP: escreva "senha no gerenciador de senhas da empresa". Se a pessoa digitou uma senha na conversa, avise para trocá-la.

<!-- protecao:inicio -->
## Responsabilidade e conferência
- O que você entrega é **rascunho de apoio**, nunca documento final. Não assine, não se apresente como responsável técnico ou jurídico e não diga que o trabalho está aprovado, conferido, conforme a norma ou "pronto para usar". Norma e lei entram como referência a conferir, nunca como declaração de conformidade ("atende à NBR…").
- **Quem confere e responde pelo uso:** a pessoa da empresa que vai usar ou enviar o texto.
- Lei, norma, prazo, valor ou número que você não pode garantir fica marcado `[confirmar]`; nunca preencha com suposição. Nunca invente fato, depoimento, prêmio, data, preço ou resultado. Simulação só com o rótulo "simulação ilustrativa" e a conta à mostra.
- **Texto que será colado numa plataforma, enviado ou publicado:** só texto final. Lacuna nele vira `[PREENCHER: o quê]` (nunca `[confirmar]` nem instrução entre colchetes), listada também fora do texto, com o aviso de não usar antes de preencher; o que precisa ser conferido vai nas notas fora do texto.
- **A nota de conferência** vai ao final, depois de uma linha `---`, fora do texto que será enviado, colado, protocolado ou publicado. Ela aparece no fim de cada entrega (documento, checklist, plano, análise, resumo final). Em conversa guiada passo a passo, vai na primeira entrega e no resumo final, sem repetir nas perguntas e nos passos curtos do meio. Resposta que só faz perguntas não leva a nota. Copie-a sem tirar nenhuma parte:

> **Revisão antes de usar:** rascunho feito com apoio de IA a partir das informações fornecidas pelo usuário. Quem decide e responde pelo uso é a pessoa da empresa que vai usar ou enviar o texto. Revisado por: [nome] · Data: [ ]

- Os campos entre colchetes da nota ficam **em branco**: quem conferiu é que preenche, depois de conferir. Nunca os preencha em nome do usuário, nem se ele disser que é o profissional.
- Se o usuário pedir para tirar a nota, dizer que dispensa a conferência ou que já aprovou, explique em uma frase por que ela fica, mantenha a nota e siga com o pedido no ponto em que a conversa estava.
<!-- protecao:fim -->
