---
title: "Configuring & De-bugging Spark Environment"
tags: [Data science, Spark, Resources]
---
# Links to Spark configuration, memory management / debugging, and the "small files" problem

### Texts
* [Mastering Apache Spark - gitbook](https://jaceklaskowski.gitbooks.io/mastering-apache-spark/content/)
* [Learning Spark - PDF](https://github.com/niewj/ebook-share/blob/master/books/OReilly.Learning.Spark.Lightning-Fast.Big.Data.Analysis.pdf)
* [Spark Definitive Guide - hardcopy ~$40](https://smile.amazon.com/Spark-Definitive-Guide-Processing-Simple/dp/1491912219/)

### General Spark Config 
* [Tuning parameters](https://blog.cloudera.com/blog/2015/03/how-to-tune-your-apache-spark-jobs-part-2/)
* [More Parameters](https://discourse.snowplowanalytics.com/t/learnings-from-using-the-new-spark-emr-jobs/1260)
* [Best practices](https://dlab.epfl.ch/2017-09-30-what-i-learned-from-processing-big-data-with-spark/)

### Spark Memory Config
* [Memory Config Guide / Spreadsheet](http://c2fo.io/c2fo/spark/aws/emr/2016/07/06/apache-spark-config-cheatsheet/)
* [Another config walkthrough](https://www.richakhandelwal.com/tuning-your-spark-jobs/)
* [Example memory config calculations](http://site.clairvoyantsoft.com/understanding-resource-allocation-configurations-spark-application/)

### Spark Out-of-Memory Debugging
* [Ways of addressing out-of-memory errors](https://www.slideshare.net/SparkSummit/understanding-memory-management-in-spark-for-fun-and-profit)
* [Common errors & fixes](https://www.indix.com/blog/engineering/lessons-from-using-spark-to-process-large-amounts-of-data-part-i/)
* [More debugging examples](http://labs.criteo.com/2018/01/spark-out-of-memory/)
* [Adjusting memory overhead for Python](https://gsamaras.wordpress.com/code/memoryoverhead-issue-in-spark/)

### Spark / Hadoop small file problems
The problem:
* [Hadoop small files problem](https://blog.cloudera.com/blog/2009/02/the-small-files-problem/)
* [Why its a problem for Spark (& S3)](http://garrens.com/blog/2017/11/04/big-data-spark-and-its-small-files-problem/)
Solutions:
* [Hadoop workaround class](https://aws.amazon.com/blogs/big-data/using-combineinputformat-to-combat-hadoops-small-files-problem/)
* [Whole Text Files](https://medium.com/@dfdeshom/how-does-sparks-wholetextfiles-work-be8e0bd45da0)
* [Parallel loading to Spark RDDs](https://stackoverflow.com/questions/41062705/reading-multiple-files-from-s3-in-parallel-spark-java)
* [Efficient load for large # of semi-structured files (e.g. JSON, CSV)](https://szczeles.github.io/Reading-JSON-CSV-and-XML-files-efficiently-in-Apache-Spark/)

### Spark Config Docs
* [Spark Config Documentation](https://spark.apache.org/docs/2.2.0/configuration.html#available-properties)
* [Spark Session Docs (place to set settings)](https://spark.apache.org/docs/2.2.0/api/python/pyspark.sql.html#pyspark.sql.SparkSession)


