## Notes on doing NLP in Spark

A few different native Spark libraries:
* MLlib (runs on RDDs)
  * [Documentation](https://spark.apache.org/docs/2.2.0/ml-guide.html)
* Spark.ml (runs on Dataframes)
  * [Documentation](https://spark.apache.org/docs/2.2.0/sql-programming-guide.html)
* SparkNLP (runs on Dataframes)
  * [Quickstart guide](http://nlp.johnsnowlabs.com/quickstart.html)
  * [Documentation](http://nlp.johnsnowlabs.com/components.html)
  * [Repo](https://github.com/JohnSnowLabs/spark-nlp)

Can also use spark to parallel process using python packages:
* [Running NLTK / Spacy on nodes](http://sujitpal.blogspot.com/2018/03/accessing-ml-models-in-spark-from.html)
* [Another example](http://www.textanalyticsworld.com/pdf/SF/2015/Day1_1405_Daniel.pdf)
