# :brain: NLP_Sentiment_Analysis_Classification

Projeto de **classificação de sentimentos** em avaliações de produtos utilizando **Processamento de Linguagem Natural (NLP)**.  
O objetivo é analisar textos de avaliações de usuários e classificá-los como **positivos** ou **negativos**, com base em seus conteúdos e notas atribuídas.

---

## :dart: Objetivo

- Classificar sentimentos expressos em avaliações textuais de produtos.
- Utilizar **NLP** e algoritmos de **Machine Learning** para identificar se o sentimento é **positivo** ou **negativo**.
- Explorar a relação entre a **nota atribuída** (1 a 5) e o **sentimento percebido** no texto da avaliação.

---

## :floppy_disk: Estrutura dos Dados

O dataset contém as seguintes colunas:

| Coluna        | Descrição                                                                 |
|---------------|---------------------------------------------------------------------------|
| `ID_avaliacao`| Identificador único da avaliação                                          |
| `avaliacao`   | Texto da avaliação escrita pelo usuário                                   |
| `nota`        | Nota atribuída ao produto (escala de 1 a 5)                               |
| `sentimento`  | Sentimento identificado na avaliação (positivo ou negativo)              |

---

## :gear: Tecnologias e Bibliotecas

- Python 3.10+
- Pandas, NumPy
- NLTK, SpaCy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## :test_tube: Etapas do Projeto

1. **Pré-processamento de Texto**
   - Limpeza e normalização dos dados
   - Remoção de stopwords e pontuações
   - Tokenização, lematização/stemming

2. **Análise Exploratória**
   - Frequência de palavras
   - Nuvem de palavras (word cloud)
   - Distribuição dos sentimentos e notas

3. **Modelagem de Classificação**
   - Vetorização: TF-IDF ou Bag-of-Words
   - Modelos: Naive Bayes, Logistic Regression, SVM, etc.
   - Avaliação com métricas: Accuracy, Precision, Recall, F1-score

4. **Visualização de Resultados**
   - Matriz de confusão
   - Comparação entre modelos
   - Palavras mais influentes na classificação
