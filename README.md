# Vault - Especialização em Agentes Inteligentes (UTFPR)

> Este repositório guarda o vault do Obsidian versionado com git.
> É um repositório separado do código do curso (`utfpr-agentes-inteligentes`)
> de propósito — ciclos de edição diferentes e, geralmente, visibilidade
> diferente (este aqui costuma fazer mais sentido como **privado**).

## Estrutura de pastas

| Pasta | Disciplina | Carga Horária | Datas das Aulas |
| :-- | :-- | :-: | :-- |
| `01-Programacao-Python-IA` | Programação Python para Inteligência Artificial | 30h | 11/09, 12/09, 25/09 e 26/09/2026 |
| `02-Fundamentos-Agentes-Inteligentes` | Fundamentos de Agentes Inteligentes | 30h | 09/10, 10/10, 23/10 e 24/10/2026 |
| `03-Matematica-Estatistica-IA` | Matemática e Estatística para Inteligência Artificial | 30h | 06/11, 07/11, 27/11 e 28/11/2026 |
| `04-Computacao-Nuvem-IA` | Computação em Nuvem para Inteligência Artificial | 30h | 04/12, 05/12, 18/12 e 19/12/2026 |
| `05-Aprendizado-de-Maquina` | Aprendizado de Máquina | 30h | 05/03, 06/03, 19/03 e 20/03/2027 |
| `06-Redes-Neurais-Aprendizado-Profundo` | Redes Neurais e Aprendizado Profundo | 30h | 02/04, 03/04, 16/04 e 17/04/2027 |
| `07-Ciencia-de-Dados-Big-Data` | Ciência de Dados e Big Data | 30h | 07/05, 08/05, 21/05 e 22/05/2027 |
| `08-PLN-e-LLMs` | Processamento de Linguagem Natural e LLMs | 30h | 04/06, 05/06, 18/06 e 19/06/2027 |
| `09-Engenharia-Prompt-IA-Generativa` | Engenharia de Prompt e Aplicações de IA Generativa | 30h | 06/08, 07/08, 20/08 e 21/08/2027 |
| `10-Engenharia-Agentes-Autonomos` | Engenharia de Agentes Autônomos | 30h | 10/09, 11/09, 24/09 e 25/09/2027 |
| `11-Sistemas-Multiagentes` | Sistemas Multiagentes | 30h | 15/10, 16/10, 05/11 e 06/11/2027 |
| `12-Etica-Governanca-IA` | Ética e Governança em Sistemas Inteligentes | 30h | 26/11, 27/11, 10/12/2027 e 04/03/2028 |

Cada pasta de disciplina já vem com uma nota `00-Visao-Geral.md` preenchida
com carga horária e datas — use-a como ponto de partida e vá linkando as
notas de conceito e de aula a partir dela.

| Pasta extra | Uso |
| :-- | :-- |
| `00-Templates` | Modelos de nota (conceito, aula, projeto) |
| `90-Projeto-Final` | Notas do projeto final/TCC |
| `95-Notas-Diarias` | Uma nota por dia/aula de estudo |
| `99-Referencias` | Papers, artigos, links externos |

(Os prefixos `90`, `95`, `99` são de propósito — mantêm essas pastas
sempre depois das 12 disciplinas na listagem por ordem alfabética.)

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
