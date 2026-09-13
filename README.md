# Vault - Especialização em Agentes Inteligentes (UTFPR)

> Este repositório guarda o vault do Obsidian versionado com git.
> É um repositório separado do código do curso (`utfpr-agentes-inteligentes`)
> de propósito — ciclos de edição diferentes e, geralmente, visibilidade
> diferente (este aqui costuma fazer mais sentido como **privado**).

## Como usar

1. Clone este repositório.
2. Abra o Obsidian → "Open folder as vault" → selecione a pasta clonada.
3. Para criar notas novas a partir de um template, instale o plugin **Templater**
   e configure a pasta `00-Templates` como pasta de templates.
4. Use `[[Nome da nota]]` para linkar conceitos entre si — é isso que constrói
   o grafo de conhecimento.

## Sincronização automática (recomendado)

Instale o plugin **Obsidian Git** (via "Community plugins" dentro do Obsidian):

1. Settings → Community plugins → Browse → busque "Obsidian Git" → Install → Enable.
2. Nas configurações do plugin, ative "Vault backup interval" (ex: a cada 10 min)
   pra ele fazer commit + push sozinho.
3. Configure também "Pull updates on startup" pra sempre abrir com a versão mais
   recente, caso edite em mais de um computador.

Assim você não precisa lembrar de rodar `git add/commit/push` manualmente toda
vez que termina de estudar.

## Estrutura de pastas

- `00-Templates/` — modelos de nota (conceito, aula, projeto)
- `01-Fundamentos-IA/`
- `02-LLMs-e-Prompting/`
- `03-Arquiteturas-Multiagente/`
- `04-RAG-e-Memoria/`
- `05-Ferramentas-e-Function-Calling/`
- `06-Avaliacao-e-Etica/`
- `07-Frameworks/` (LangChain, AutoGen, CrewAI, etc.)
- `08-Projeto-Final/`
- `09-Notas-Diarias/` — uma nota por aula/dia de estudo
- `10-Referencias/` — papers, artigos, links externos

## Sistema de tags

- Por disciplina: `#fundamentos-ia`, `#multiagente`, `#rag`, etc.
- Por tipo: `#aula`, `#projeto`, `#leitura`
- Por domínio: `#a-entender`, `#entendido`, `#dominado`
  (também refletido no campo `status:` do frontmatter, útil pra usar com Dataview)

## Plugins recomendados

| Plugin | Para que serve aqui |
|---|---|
| **Templater** | Criar notas novas já com a estrutura dos templates |
| **Dataview** | Montar tabelas automáticas (ex: "todas as notas com status: a-entender") |
| **Excalidraw** | Desenhar diagramas de arquitetura de agentes à mão |
| **Spaced Repetition** | Revisar conceitos-chave antes de provas |
| **Graph Analysis** | Ver quais conceitos estão mais conectados (bons candidatos a revisão) |

## Regra de integração com o Notion

**Notion = o que fazer e quando. Obsidian = o que aprendi e como se conecta.**
Cada card de entrega no Notion deve linkar para a pasta/nota correspondente aqui.
