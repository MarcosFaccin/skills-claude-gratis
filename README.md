# Skills grátis para o Claude · trIlhA iddeIA

10 skills em português para o Claude trabalhar no seu ramo, uma de cada pacote da [loja da trIlhA iddeIA](https://iddeia.com.br/loja/). Use à vontade na sua empresa. Se gostar, o pacote completo de cada área está na loja.

Skills são instruções que o Claude carrega sozinho quando a tarefa pede. Com elas, ele faz o trabalho do jeito do seu setor, em vez de dar uma resposta genérica.

| Skill | Para quê | Pacote completo |
|---|---|---|
| `procedimento-padrao` | Transforma "como a gente faz" em procedimento padrão (POP), com responsável, passos, checklist e o que fazer quando der errado | Escritório · 8 skills |
| `briefing-e-programa` | Conduz o briefing de arquitetura, interiores ou reforma e monta o programa de necessidades por ambiente | Arquitetura e Reforma · 4 skills |
| `roteiro-de-vistoria` | Roteiro de vistoria técnica de imóvel ou obra: o que levantar antes e o que observar, medir e fotografar em cada ambiente | Perícia e Patologia · 4 skills |
| `diario-de-obra` | Transforma o relato do dia da obra no Relatório Diário de Obra (RDO), sem inventar quantidades | Engenharia · 5 skills |
| `preco-do-projeto` | Calcula o preço de sistema, agente, automação, app ou site pelos dias por fase, folga, impostos e marcos de pagamento | Agência de IA · 5 skills |
| `ideia-do-app` | Transforma a ideia num plano de app mínimo de uma página: público, ação principal, até 5 telas e se precisa mesmo ir para a loja | Apps com Claude Code · 5 skills |
| `conselho-estrategia` | Conselheiro de estratégia (papel de CEO): prioridades, crescimento e o que parar de fazer, com os números do seu negócio | Conselho C-Level · 7 skills |
| `base-de-conhecimento` | Monta a base que o agente de atendimento consulta para responder seus clientes | Atendimento com IA · 5 skills |
| `roteiro-de-entrevista` | Perguntas por competência, ficha de avaliação e o que nunca perguntar | RH · 5 skills |
| `calendario-de-conteudo` | Calendário do mês para as redes da sua empresa, com o jeito da sua marca | Conteúdo e Redes · 5 skills |

Os 10 pacotes completos (53 skills) também saem juntos no **Pacote Todas as Skills**, na [loja](https://iddeia.com.br/loja/).

## Requisito

Claude Pro ou superior (plano pago da Anthropic). No Claude.ai, a execução de código e a criação de arquivos precisam estar ativadas nas configurações. Em planos Team ou Enterprise, o administrador pode precisar liberar o uso de Skills.

## Como instalar

Baixe este repositório (botão *Code › Download ZIP*) e descompacte.

**No Claude.ai ou no app do Claude** (o nome dos menus pode variar um pouco, procure por *Skills*):
1. Abra *Personalização › Skills* no menu lateral.
2. Clique em *Adicionar › Fazer upload de Skill* e envie os arquivos da pasta `zips/`. É um .zip por skill, já pronto: não descompacte esses.
3. Peça normalmente ("monta o POP de abertura da loja") e o Claude usa a skill sozinho.

**No Claude Code:** copie as pastas de `skills/` para `~/.claude/skills/` ou para `.claude/skills/` de um projeto.

## Antes de usar

As skills leem um perfil do seu negócio, se ele existir. Preencha o da pasta `perfis/` e anexe na conversa (ou deixe na pasta do projeto, no Claude Code):
- `PERFIL_EMPRESA.md`: para quase todas as skills;
- `PERFIL_AGENCIA.md`: para `preco-do-projeto`;
- `PERFIL_APP.md`: para `ideia-do-app`.

Campo que ficou com `[ ]` ou com o exemplo `[ex.: …]` conta como não preenchido, e a skill pergunta.

## Responsabilidade

O que as skills entregam é rascunho de apoio. Documento técnico, jurídico ou contábil precisa da conferência de um profissional habilitado (arquiteto com RRT, engenheiro com ART, advogado, contador), e cada entrega termina com uma nota de conferência para ele preencher. Detalhes em [TERMOS-DE-USO.md](TERMOS-DE-USO.md).

## Licença

Uso gratuito na sua empresa, com adaptação livre. Não pode revender nem republicar. Veja [LICENCA.md](LICENCA.md).

---

Feito pela [IDDEIA](https://iddeia.com.br) · contato@iddeia.com.br · Instagram [@iddeia.ai](https://instagram.com/iddeia.ai)
