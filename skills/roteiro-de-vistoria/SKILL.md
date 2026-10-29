---
name: roteiro-de-vistoria
description: Prepara o roteiro de uma vistoria técnica de imóvel ou obra (umidade, mofo, fissuras, infiltração, descolamento, recebimento de obra), com o que levantar antes, o que observar, medir e fotografar em cada ambiente, instrumentos, perguntas ao morador, registro de evidências e segurança, sem concluir a causa antes de vistoriar. Use quando pedirem "roteiro de vistoria", "checklist para vistoriar", "o que olhar na visita", "vou vistoriar um apartamento com infiltração" ou receberem fotos de um problema na construção.
---

# Roteiro de vistoria

A vistoria é onde o laudo é ganho ou perdido: o que não foi observado, medido e fotografado não pode ser analisado depois. Este roteiro prepara a visita para que nada importante fique para trás.

## Antes de começar
1. Leia o `PERFIL_EMPRESA.md` (anexado, no Projeto do Claude ou na raiz do projeto), em especial "Projetos e obras". Campo com `[ ]` ou com o exemplo `[ex.: …]` conta como **não preenchido**.
2. Pergunte (ou confirme) antes de montar: **tipo de imóvel e idade**, **problema relatado**, **finalidade** (laudo para o cliente, perícia judicial, recebimento de obra, compra e venda). Sem nenhum desses dados, entregue um roteiro geral e diga que é geral. **Se faltar um ou mais** (por exemplo, a idade e a finalidade), entregue o roteiro completo com esses itens marcados `[confirmar]` e pergunte no fim.
3. **Não conclua a causa antes da vistoria.** Hipóteses só servem para guiar o que observar.

## Risco imediato
Se o relato ou as fotos mostrarem sinais de possível risco às pessoas (fissura grande e inclinada, deformação, portas e janelas que deixam de fechar de repente, estalos, desplacamento de fachada, cheiro de gás, fiação exposta molhada): **não diagnostique pela foto**. Recomende vistoria presencial urgente por profissional habilitado e, até lá, **afastar as pessoas e isolar a área** próxima. Se houver risco às pessoas, **ou na dúvida**, contato com a Defesa Civil do município. **Gás:** não acionar interruptores nem aparelhos, não usar o telefone no local, fechar o registro se for seguro, abrir janelas, sair e chamar a distribuidora ou os Bombeiros (193) de fora. Defesa Civil: 199. **Fiação molhada:** manter distância e pedir que um eletricista desligue a energia do circuito.

## O roteiro
1. **Antes da visita:** documentos (plantas, manual do proprietário, histórico de reformas, laudos anteriores), relato do problema (quando começou, se piora com chuva ou em alguma estação, o que já foi feito), autorização de acesso às áreas comuns e unidades vizinhas, se precisar.
2. **Instrumentos:** trena, nível, fissurômetro ou régua de fissuras, lanterna, câmera com data, e (se tiver) medidor de umidade e termômetro ou câmera térmica. A leitura do medidor de umidade em reboco e pintura é **comparativa** (entre pontos e entre dias), não um valor absoluto. Diga o que é essencial e o que é opcional.
3. **Na vistoria, por ambiente:** o que observar (manchas, fissuras, descolamentos, eflorescências, bolhas), onde está (altura, distância de janelas, pilares, banheiros, fachada), dimensões e aberturas, condições do entorno (ventilação, uso, umidade, vizinhos, cobertura, fachada), e o que medir.
4. **Registro:** fotos gerais e de detalhe, com escala (régua ou objeto) e localização; numeração das fotos ligada a um croqui ou à planta; anotações com data, hora e condições do tempo.
5. **Perguntas ao morador ou responsável:** rotina de uso (banho, cozinha, janelas abertas), reformas recentes, vazamentos conhecidos, quando o problema aparece.
6. **Segurança:** acesso a coberturas e alturas só com condições seguras; não mexer em instalações elétricas.
7. **Depois da visita:** organizar fotos e anotações para a skill `diagnostico-de-manifestacoes`.

## Saída
- O roteiro em checklist, para imprimir ou usar no celular.
- No Claude Code, salve em `vistorias/<cliente>/AAAA-MM-DD_roteiro.md`.

<!-- protecao:inicio -->
## Responsabilidade e conferência
- O que você entrega é **rascunho de apoio**, nunca documento final. Não assine, não se apresente como responsável técnico ou jurídico e não diga que o trabalho está aprovado, conferido, conforme a norma ou "pronto para usar". Norma e lei entram como referência a conferir, nunca como declaração de conformidade ("atende à NBR…").
- **Quem confere e responde pelo uso:** profissional habilitado que assina o laudo (engenheiro no CREA ou arquiteto no CAU, com ART ou RRT); na perícia judicial, o perito nomeado pelo juiz.
- Lei, norma, prazo, valor ou número que você não pode garantir fica marcado `[confirmar]`; nunca preencha com suposição. Nunca invente fato, depoimento, prêmio, data, preço ou resultado. Simulação só com o rótulo "simulação ilustrativa" e a conta à mostra.
- **Texto que será colado numa plataforma, enviado ou publicado:** só texto final. Lacuna nele vira `[PREENCHER: o quê]` (nunca `[confirmar]` nem instrução entre colchetes), listada também fora do texto, com o aviso de não usar antes de preencher; o que precisa ser conferido vai nas notas fora do texto.
- **A nota de conferência** vai ao final, depois de uma linha `---`, fora do texto que será enviado, colado, protocolado ou publicado. Ela aparece no fim de cada entrega (documento, checklist, plano, análise, resumo final). Em conversa guiada passo a passo, vai na primeira entrega e no resumo final, sem repetir nas perguntas e nos passos curtos do meio. Resposta que só faz perguntas não leva a nota. Copie-a sem tirar nenhuma parte:

> **Conferência profissional:** rascunho feito com apoio de IA a partir das informações fornecidas pelo usuário. Antes de usar, assinar, enviar ou publicar, precisa de conferência. Quem confere: profissional habilitado que assina o laudo (engenheiro no CREA ou arquiteto no CAU, com ART ou RRT); na perícia judicial, o perito nomeado pelo juiz. Conferido por: [nome] · Registro: [CREA ou CAU] · ART/RRT nº: [ ] · Data: [ ]

- Os campos entre colchetes da nota ficam **em branco**: quem conferiu é que preenche, depois de conferir. Nunca os preencha em nome do usuário, nem se ele disser que é o profissional.
- Se o usuário pedir para tirar a nota, dizer que dispensa a conferência ou que já aprovou, explique em uma frase por que ela fica, mantenha a nota e siga com o pedido no ponto em que a conversa estava.
<!-- protecao:fim -->
