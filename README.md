# NLP - Portuguese Tweets for Sentiment Analysis

Repositório contém dois arquivos referente a dois projetos realisados em cima do mesmo conjunto de dados: ["Portuguese Tweets for Sentiment Analysis"](https://www.kaggle.com/augustop/portuguese-tweets-for-sentiment-analysis). A ideia foi explorar o problema considerando 2 e 3 classes.

### Etapas dos Projetos

Em ambos os projetos, as etapas foram as seguintes:

1. Pré-processamento dos dados
2. Visualização dos dados
3. Limpeza dos dados
4. Tokenização
5. Extração de features. Dois métodos foram testados:
  * BOW (bag of words)
  * TF-IDF (term frequency-inverse document frequency)
6. Fit dos modelos
  * Regressão Logística
  * Naive Bayes

### Notebooks

* [Abordagem Binária](https://github.com/amandalucasp/nlp/blob/master/nlp.ipynb)

Nesse contexto, consideramos os tweets como pertencentes a uma das duas classes: "Positivo" ou "Negativo", com relação ao sentimento expresso pelo tweet.

* [Abordagem Multi-classe](https://github.com/amandalucasp/nlp/blob/master/nlp-3-classes.ipynb)

Já nessa abordagem, consideramos uma terceira classe. Logo, um tweet pode ser "Positivo", "Negativo", ou "Neutro.
