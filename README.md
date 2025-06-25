# NLP
Atividades realizadas durante o projeto de MIDTI
# Análise de Representações Vetoriais com Sentence-BERT para Tarefas de PLN

Este repositório contém notebooks desenvolvidos no contexto do projeto da MIDTI, cujo objetivo central é analisar a relevância das representações vetoriais do modelo Sentence-BERT (S-BERT) para otimização de tarefas de Processamento de Linguagem Natural (PLN).

##  Objetivos do Projeto

**Objetivo Geral:**

- Analisar a relevância das representações vetoriais do Sentence-BERT para otimizar tarefas de PLN.

**Objetivos Específicos:**

- Identificar as componentes vetoriais mais relevantes para análise de sentimento;
- Aplicar técnicas de redução de dimensionalidade e avaliar seus impactos;
- Validar as representações reduzidas em tarefas práticas de PLN.

##  Conteúdo do Repositório

###  `embeddingNovo.ipynb`

Notebook dedicado à manipulação de embeddings gerados pelo modelo Sentence-BERT:

- Carregamento do modelo pré-treinado utilizando a biblioteca `transformers`;
- Leitura de frases a partir de um arquivo e extração dos embeddings vetoriais correspondentes;
- Preparo dos dados para análise de componentes e visualizações futuras.

###  `Tarefa_1.ipynb`

Notebook complementar com aplicação prática de classificação supervisionada:

- Utilização do conjunto de dados clássico `iris` do `scikit-learn`;
- Criação e treinamento de uma rede neural utilizando `MLPClassifier`;
- Demonstração de pipeline de classificação que poderá ser adaptado a dados vetoriais extraídos de embeddings.

##  Requisitos

Certifique-se de ter as seguintes dependências instaladas:

- Python 3.8+
- [Transformers](https://huggingface.co/transformers/) (`pip install transformers`)
- PyTorch (`pip install torch`)
- Scikit-learn (`pip install scikit-learn`)
- Jupyter Notebook (`pip install notebook`)

##  Como Executar

Clone o repositório e execute os notebooks com Jupyter:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
jupyter notebook
```

Abra os notebooks pelo navegador e execute as células conforme as instruções.

##  Observações

- Este repositório está em desenvolvimento contínuo como parte de um projeto de pesquisa aplicada;
- Futuras atualizações incluirão análise de componentes principais (PCA), t-SNE, UMAP e validação dos vetores reduzidos em tarefas como classificação de sentimento e clustering.
