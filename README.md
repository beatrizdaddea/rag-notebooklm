# 📚 Miniguia de Estudos com NotebookLM: RAG (Retrieval-Augmented Generation)

## 🎯 Contexto e Objetivos

Este projeto tem como objetivo explorar o uso do NotebookLM como ferramenta de aprendizagem ativa para compreender conceitos e aplicações de Retrieval-Augmented Generation (RAG).

O foco foi desenvolver uma base sólida sobre:

* Como funcionam sistemas RAG
* Uso de embeddings e busca semântica
* Integração com LLMs
* Aplicações práticas em sistemas reais

Além disso, o projeto busca desenvolver habilidades de:

* Curadoria de conteúdo técnico
* Engenharia de prompts
* Pensamento crítico no uso de IA

---

## 📖 Curadoria de Fontes

As seguintes fontes foram selecionadas e utilizadas no NotebookLM:

1. https://arxiv.org/pdf/2005.11401.pdf (RAG Paper - Facebook)
2. https://www.pinecone.io/learn/retrieval-augmented-generation/
3. https://platform.openai.com/docs/guides/embeddings
4. https://huggingface.co/docs/transformers/index
5. https://www.deeplearning.ai/short-courses/

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

### 🔹 Prompt 1 (Exploração inicial)

**Prompt:**

> Explique o que é RAG como se eu fosse um desenvolvedor iniciante.

**Resultado:**
Resposta muito genérica.

**Ajuste:**

> Explique RAG com foco em arquitetura (retriever + generator) e fluxo de dados.

---

### 🔹 Prompt 2 (Aprofundamento)

**Prompt:**

> Quais são os componentes principais de um sistema RAG?

**Resultado:**
Boa resposta, mas faltou exemplo prático.

**Ajuste:**

> Explique os componentes de RAG e dê um exemplo de implementação prática com embeddings.

---

### 🔹 Prompt 3 (Comparação)

**Prompt:**

> Qual a diferença entre fine-tuning e RAG?

**Insight:**
Excelente para entendimento estratégico.

---

### 🔹 Dificuldades encontradas

* Respostas muito genéricas no início
* Falta de contexto nos prompts
* Necessidade de prompts mais específicos e técnicos

---

## 📘 Miniguia de Estudo

### 🧩 O que é RAG?

RAG (Retrieval-Augmented Generation) é uma técnica que combina:

* Recuperação de informação (retrieval)
* Geração de texto (LLM)

Fluxo:

1. Usuário faz pergunta
2. Sistema busca documentos relevantes
3. LLM gera resposta com base nesses documentos

---

### ⚙️ Componentes principais

* **Embedding Model** → transforma texto em vetores
* **Vector Database** → armazena embeddings
* **Retriever** → busca contexto relevante
* **LLM (Generator)** → gera resposta final

---

### 📊 Vantagens

* Respostas mais atualizadas
* Redução de alucinações
* Não precisa treinar modelo do zero

---

### 📉 Limitações

* Dependência da qualidade dos dados
* Latência maior
* Complexidade arquitetural

---

## 📖 Glossário

* **Embedding:** Representação vetorial de texto
* **Vector Database:** Banco para busca semântica
* **Retriever:** Componente de busca
* **LLM:** Modelo de linguagem grande
* **Chunking:** Divisão de texto em partes menores

---

## 🧠 Prompts Reutilizáveis

* "Explique [conceito] com foco em aplicação prática"
* "Compare [A] vs [B] com vantagens e desvantagens"
* "Explique como implementar [conceito] passo a passo"
* "Quais são os erros comuns ao usar [conceito]?"

---

## 🚀 Conclusão

O uso do NotebookLM permitiu uma abordagem ativa de aprendizado, facilitando a organização do conhecimento e aprofundamento técnico sobre RAG.

Este projeto demonstra não apenas conhecimento técnico, mas também a capacidade de aprender com IA de forma estruturada e crítica.
