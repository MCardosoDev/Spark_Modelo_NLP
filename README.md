# Spark Modelo NLP

### Dados do IMDB do Kaggle

- WordCloud
- Tokenização
- StopWords
- Vetorização
- CountVector (bag of words)
- Hashing TF
- TF-IDF
- Codificando
- Pipeline
- Florestas Aleatórias
- Teste e Métricas


    - from pyspark.sql import SparkSession
    - from wordcloud import WordCloud
    -  import matplotlib.pyplot as plt
    -  import string
    -  import pyspark.sql.functions as f
    -  from pyspark.ml.feature import Tokenizer
    -  from pyspark.sql.types import IntegerType
    -  import nltk
    -  nltk.download("stopwords")
    -  from nltk.corpus import stopwords
    -  from pyspark.ml.feature import StopWordsRemover
    -  from pyspark.ml.feature import CountVectorizer
    -  from pyspark.ml.feature import HashingTF
    -  from pyspark.ml.feature import HashingTF
    -  from pyspark.ml.feature import IDF
    -  from pyspark.ml.feature import StringIndexer
    -  from pyspark.ml import Pipeline
    -  from pyspark.ml.classification import DecisionTreeClassifier
    -  from pyspark.ml.evaluation import MulticlassClassificationEvaluator