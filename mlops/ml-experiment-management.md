# Experiment Management

1. [All the alternatives](https://blog.valohai.com/top-machine-learning-platforms)
2. Cnvrg.io -
   1. Manage - Easily navigate machine learning with dashboards, reproducible data science, dataset organization, experiment tracking and visualization, a model repository and more
   2. Build - Run and track experiments in hyperspeed with the freedom to use any compute environment, framework, programming language or tool - no configuration required
   3. Automate - Build more models and automate your machine learning from research to production using reusable components and drag-n-drop interface
3. Comet.ml - Comet lets you track code, experiments, and results on ML projects. It’s fast, simple, and free for open source projects.
4. Floyd - notebooks on the cloud, similar to colab / kaggle, etc. gpu costs 4$/h
5. [Trains - open source](https://heartbeat.fritz.ai/trains-all-aboard-ba92a728eb6d)
6. Missing link - RIP
7. Spark
   1. [Rdds vs datasets vs dataframes](https://databricks.com/blog/2016/07/14/a-tale-of-three-apache-spark-apis-rdds-dataframes-and-datasets.html)
   2. [What are Rdds?](https://www.quora.com/What-are-resilient-distributed-datasets-RDDs-How-do-they-help-Spark-with-its-awesome-speed)
   3. [keras , tf,  spark](https://medium.com/qubida-analytics-blog/build-a-deep-learning-image-classification-pipeline-with-spark-keras-and-tensorflow-3bf26fda15e6)
   4. [Repartition vs coalesce ](https://medium.com/@mrpowers/managing-spark-partitions-with-coalesce-and-repartition-4050c57ad5c4)
   5. [Best practices](https://www.bi4all.pt/en/news/en-blog/apache-spark-best-practices/)
8. Databricks
   1. [Koalas](https://github.com/databricks/koalas) - pandas API on Apache Spark
   2. [Intro to DB on spark](https://www.youtube.com/watch?v=DqihOzZl5jM\&list=PLTPXxbhUt-YV-CwJTiE36C-0le8wlFJ5G\&index=5), has some basic sklearn-like tool and other custom operations such as single-vector-based aggregator for using features as an input to a model
   3. [Pyspark.ml](https://spark.apache.org/docs/latest/api/python/pyspark.ml.html)
   4. [Keras as a single node (no spark)](https://docs.databricks.com/applications/deep-learning/single-node-training/keras.html)
   5. [Horovod for distributed keras (and more)](https://docs.databricks.com/applications/deep-learning/distributed-training/mnist-tensorflow-keras.html)
   6. [Documentations](https://docs.databricks.com/index.html) (read me, has all libraries)
   7. [Medium tutorial](https://towardsdatascience.com/how-to-train-your-neural-networks-in-parallel-with-keras-and-apache-spark-ea8a3f48cae6), explains the 3 pros of DB with examples of using with native and non native algos
      1. Spark sql
      2. Mlflow
      3. Streaming
      4. SystemML DML using keras models.
   8. [systemML notebooks (didnt read)](http://systemml.apache.org/get-started.html#sample-notebook)
   9. [Sklearn notebook example](https://docs.databricks.com/\_static/notebooks/scikit-learn.html)
   10. [Utilizing spark nodes](https://databricks.com/blog/2016/02/08/auto-scaling-scikit-learn-with-apache-spark.html) for grid searching with sklearn
       1. from spark\_sklearn import GridSearchCV
   11. [How can we leverage](https://databricks-prod-cloudfront.cloud.databricks.com/public/13fe59d17777de29f8a2ffdf85f52925/5638528096339357/1867405/6918044996430578/latest.html) our existing experience with modeling libraries like [scikit-learn](http://scikit-learn.org/stable/index.html)? We'll explore three approaches that make use of existing libraries, but still benefit from the parallelism provided by Spark.

These approaches are:

* Grid Search
* Cross Validation
* Sampling (random, chronological subsets of data across clusters)

1. Github [spark-sklearn](https://github.com/databricks/spark-sklearn) (needs to be compared to what spark has internally)
   1. [Ref:](https://mapr.com/blog/predicting-airbnb-listing-prices-scikit-learn-and-apache-spark/) It's worth pausing here to note that the architecture of this approach is different than that used by MLlib in Spark. Using spark-sklearn, we're simply distributing the cross-validation run of each model (with a specific combination of hyperparameters) across each Spark executor. Spark MLlib, on the other hand, will distribute the internals of the actual learning algorithms across the cluster.
   2. The main advantage of spark-sklearn is that it enables leveraging the very rich set of [machine learning](https://mapr.com/ebook/machine-learning-logistics/) algorithms in scikit-learn. These algorithms do not run natively on a cluster (although they can be parallelized on a single machine) and by adding Spark, we can unlock a lot more horsepower than could ordinarily be used.
   3. Using [spark-sklearn](https://github.com/databricks/spark-sklearn) is a straightforward way to throw more CPU at any machine learning problem you might have. We used the package to reduce the time spent searching and reduce the error for our estimator
2. [Airbnb example using spark and sklearn,cross\_val& grid search comparison vs joblib](https://mapr.com/blog/predicting-airbnb-listing-prices-scikit-learn-and-apache-spark/)
3. [Sklearn example 2, tfidf, ](http://cdn2.hubspot.net/hubfs/438089/notebooks/ML/scikit-learn/demo\_-\_1\_-\_sklearn.html)
4. [Tracking experiments](https://docs.databricks.com/applications/mlflow/tracking.html)
   1. [example](https://docs.databricks.com/applications/mlflow/tracking-examples.html#train-a-scikit-learn-model-and-save-in-scikit-learn-format)
5. [Saving loading deployment](https://docs.databricks.com/applications/mlflow/models.html#examples)
   1. [Aws sagemaker](https://docs.databricks.com/applications/mlflow/model-examples.html#scikit-learn-model-deployment-on-sagemaker)
   2. [Medium](https://towardsdatascience.com/a-different-way-to-deploy-a-python-model-over-spark-2da4d625f73e) and sklearn random trees
6. [How to productionalize your model using db spark 2.0 on youtube](https://databricks.com/session/how-to-productionize-your-machine-learning-models-using-apache-spark-mllib-2-x)
