# Sistema de Recuperação de Informações (RAG) com LangChain e FAISS

Repositório desenvolvido como atividade prática da disciplina de Tópicos Específicos em Sistemas para Internet (IFRN), com o objetivo de construir um sistema de recuperação de informações utilizando vetores de embeddings e banco de dados vetorial.

## 🛠️ Tecnologias Utilizadas
* **Python** (via Google Colab)
* **LangChain** (para divisão de texto em chunks e pipeline de busca)
* **FAISS** (Facebook AI Similarity Search, para indexação e busca vetorial)
* **Sentence-Transformers / HuggingFace** (modelo `all-MiniLM-L6-v2` para geração de embeddings)

---

## 📂 Estrutura do Projeto

1. **Preparação do Ambiente:** Instalação das bibliotecas necessárias no Google Colab.
2. **Processamento do Texto:** Divisão do documento conceitual sobre Inteligência Artificial em *chunks*.
3. **Banco de Dados Vetorial:** Geração de embeddings e indexação no FAISS.
4. **RetrievalQA:** Realização de busca por similaridade semântica no banco vetorial.

---

## 🚀 Como Executar no Google Colab

1. Abra o arquivo `.ipynb` presente neste repositório.
2. Clique no botão **"Open in Colab"** ou faça o upload manual no [Google Colab](https://colab.research.google.com/).
3. Execute as células sequencialmente para observar a criação do VectorDB e o retorno da consulta.

---

## 💡 Exemplo de Pergunta e Resposta

* **1º Pergunta do Usuário:**
  > *"O que são embeddings e para que serve o FAISS?"*

* **Resposta Recuperada do Banco Vetorial (FAISS):**
  > *"Os embeddings são representações vetoriais de palavras ou textos que capturam o significado semântico, permitindo que os modelos processem linguagem natural de forma eficiente. O FAISS (Facebook AI Similarity Search) é uma biblioteca desenvolvida para busca eficiente de similaridade e agrupamento de vetores densos em bancos de dados vetoriais."*

* **2º Pergunta do Usuário:**
  > *"O que é Inteligência Artificial?"*

* **RESPOSTA RECUPERADA DO VECTORDB (FAISS):**
  > *"A Inteligência Artificial (IA) é um campopda ciência da computação dedicado ao desenvolvimento de sistemas capazes de realizar tarefas que
normalmente exigiriam inteligência humana."*
---
**Fonte dos dados:** Artigo Educacional sobre Fundamentos de IA / Material didático da disciplina.
