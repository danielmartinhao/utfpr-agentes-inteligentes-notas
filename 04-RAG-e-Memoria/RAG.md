---
tipo: conceito
disciplina: RAG e Memória
status: entendido
tags: [rag, memoria, embeddings]
criado: 2026-09-13
---

# RAG (Retrieval-Augmented Generation)

## Definição
> Técnica que combina um modelo de linguagem com um sistema de busca externo, permitindo que o modelo consulte documentos relevantes antes de gerar uma resposta, em vez de depender só do que aprendeu no treinamento.

## Por que importa
> Reduz alucinação, permite atualizar o conhecimento do agente sem re-treinar o modelo, e viabiliza agentes que trabalham com dados privados/específicos de domínio.

## Como se relaciona
- Pré-requisito: [[Embeddings]]
- Relacionado a: [[Vector Databases]], [[Prompt Engineering]]
- Usado em: [[Agentes com Memória de Longo Prazo]]

## Exemplo prático
```
1. Usuário faz uma pergunta
2. A pergunta é transformada em embedding
3. Busca por similaridade no vector DB retorna os trechos mais relevantes
4. Os trechos são inseridos no prompt como contexto
5. O modelo gera a resposta usando esse contexto
```

## Dúvidas em aberto
- [ ] Quando vale mais a pena usar RAG vs fine-tuning?
- [ ] Como lidar com contexto muito longo sem estourar a janela do modelo?

## Referências
- Aula 3 - Fundamentos de RAG
- [[Vector Databases]]
