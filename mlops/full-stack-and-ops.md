# MLOps Tools

### CONTINUOUS INTEGRATION

1. [Travis](https://travis-ci.org/)
2. [Circle CI](https://circleci.com/)
3. Github Actions
   1. [poetry black pytest](https://medium.com/@vanflymen/blazing-fast-ci-with-github-actions-poetry-black-and-pytest-9e74299dd4a5)

### PACKAGE REPOSITORIES

1. Pypi - public
2. [Gemfury](https://gemfury.com/) - private

### Docker for DS

* [What are docker layers](https://medium.com/@jessgreb01/digging-into-docker-layers-c22f948ed612)?
* [Install on ubuntu](https://linuxconfig.org/how-to-install-docker-on-ubuntu-18-04-bionic-beaver)
* [Many jupyter docker images (spark too)](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html)
* [How to run jupyter docker 1](https://medium.com/@rahulvaish/jupyter-docker-badd38fd6b51), [2](https://medium.com/fundbox-engineering/overview-d3759e83969c)
* [Tell docker to run on a mounted disk](https://stackoverflow.com/questions/32070113/how-do-i-change-the-default-docker-container-location)
* [Docker, keras, k8s, flask serving](https://medium.com/analytics-vidhya/deploy-your-first-deep-learning-model-on-kubernetes-with-python-keras-flask-and-docker-575dc07d9e76)
* [Compose](https://docs.docker.com/compose/) - run multi coker applications.
* [Docker on ubuntu, tutorial](https://medium.com/fundbox-engineering/overview-d3759e83969c)
* [Containerize your ds environment using docker compose](https://towardsdatascience.com/containerize-your-whole-data-science-environment-or-anything-you-want-with-docker-compose-e962b8ce8ce5) - Docker-Compose is simply a tool that allows you to describe a collection of multiple containers that can interact via their own network in a very straight forward way,&#x20;
* [docker for data science](https://aoyilmaz.medium.com/docker-in-data-science-and-a-friendly-beginner-to-docker-186fafdfbdeb)
* [using vscode to debug containers](https://nirradi.medium.com/vsc-vs-pycharm-developing-inside-docker-containers-4892c83d30e4)

### Kubeflow for DS

* [Youtube - the easy way,](https://www.youtube.com/watch?v=P5wcE4IwKgQ) [intro](https://medium.com/@amina.alsherif/how-to-get-started-with-kubeflow-187792f3e99)\*, [intro2\*](https://kubernetes.io/blog/2017/12/introducing-kubeflow-composable/), [intro3](https://medium.com/better-programming/kubeflow-pipelines-with-gpus-1af6a74ec2a),
* [Really good detailed article, for example it supports many serving options such as seldon](https://ubuntu.com/blog/ml-serving-models-with-kubeflow-on-ubuntu-part-1)
* [presentation](https://www.oliverwyman.com/content/dam/oliver-wyman/v2/events/2018/March/Google\_London\_Event/Public%20Introduction%20to%20Kubeflow.pdf)
* Tutorials:
  * [Official example](https://github.com/kubeflow/example-seldon)
  * [Step by step tut](https://codelabs.developers.google.com/codelabs/cloud-kubeflow-e2e-gis/index.html?index=..%2F..index#0)\*
  * [endtoend tut](https://journal.arrikto.com/an-end-to-end-ml-pipeline-on-prem-notebooks-kubeflow-pipelines-on-the-new-minikf-ee618b7dc7de),&#x20;
  * [really detailed tut](https://towardsdatascience.com/how-to-create-and-deploy-a-kubeflow-machine-learning-pipeline-part-1-efea7a4b650f)
  * KF + [Seldon on ec2](https://docs.seldon.io/projects/seldon-core/en/latest/examples/kubeflow\_seldon\_e2e\_pipeline.html)

### AirFlow

* [Airflow](https://airflow.apache.org/) is a platform created by the community to programmatically author, schedule and monitor workflows.
* [Airflow in 5 minutes](https://medium.com/swlh/apache-airflow-in-5-minutes-c005b4b11b26) by Ashish Kumar
* [Airflow 2.0 tutorial](https://medium.com/apache-airflow/apache-airflow-2-0-tutorial-41329bbf7211) by Tomasz Urbaszek
* [Simple  ETL](https://adenilsoncastro.medium.com/apache-airflow-the-etl-02-f4ac25f4d9b4) by Adnilson Castro
* [Airflow Scheduler & Webserver](https://medium.com/analytics-vidhya/manage-your-workflows-with-apache-airflow-e7b0e45544a8) by Shritam Kumar Mund &#x20;

### Prefect

* [A better airflow ](http://airflow)?
* [ml workflows with prefect](https://www.youtube.com/watch?v=SP6WqCRUkNc)

### Seldon&#x20;

* Runs in k8s
* Seldon-core seldon-deploy (what are the differences?)
* [Serving graph, recipe file](https://becominghuman.ai/seldon-inference-graph-pipelined-model-serving-211c6b095f62)
* [Descriptive intro ](https://medium.com/seldon-open-source-machine-learning/introducing-seldon-core-machine-learning-deployment-for-kubernetes-e10e94c19fd8)
* [Sales pitch intro](https://medium.com/seldon-open-source-machine-learning/introducing-seldon-deploy-c390d11af20c)

### Tutorials&#x20;

* [Kubernetes, sklearn, s2i, gcloud, seldon random serving for ab testing](https://medium.com/analytics-vidhya/manage-ml-deployments-like-a-boss-deploy-your-first-ab-test-with-sklearn-kubernetes-and-b10ae0819dfe)
* [Polyaxon - training, argo-package/deployment , seldin -serving](https://medium.com/analytics-vidhya/polyaxon-argo-and-seldon-for-model-training-package-and-deployment-in-kubernetes-fa089ba7d60b)

### Sentry

* [For python,](https://sentry.io/for/python/) Your code is telling you more than what your logs let on. Sentry’s full stack monitoring gives you full visibility into your code, so you can catch issues before they become downtime.

### Kafka for DS

1. [What is, terminology, use cases](https://sookocheff.com/post/kafka/kafka-in-a-nutshell/)

### Redis for DS

1. What is, vs [memcached](https://medium.com/@pankaj.itdeveloper/memcached-vs-redis-which-one-to-choose-d5177482dc42)
2. [Redis cluster](https://medium.com/@inthujan/introduction-to-redis-redis-cluster-6c7760c8ebbc)
3. [Redis plus spacy](https://towardsdatascience.com/spacy-redis-magic-60f25c21303d)
4. Note: redis is a managed dictionary its strength lies when you have a lot of data that needs to be queries and managed and you don’t want to hard code it, for example.
5. [Long tutorial](https://realpython.com/python-redis/)

### Statsd

1. [Statistics server, with gauges/buckets and flushing/sending ability](https://github.com/statsd/statsd/blob/master/examples/python\_example.py)

### FastAPI

1. [Flask on steroids with variable parameters](https://fastapi.tiangolo.com/alternatives/)

### Visualization

1. [How to use plotly in python](https://plot.ly/python/ipython-notebook-tutorial/)

Plotly for jupyter lab “jupyter labextension install @jupyterlab/plotly-extension”

1. [Venn for python](http://ow-to-create-and-customize-venn-diagrams-in-python-263555527305)

### Serving Models

1. ML SYSTEM DESIGN PATTERNS, [res](https://docs.google.com/presentation/d/1pSkklHkBySMnJNODshW8NZVpBSqOsbJBWeEq8RrS0M4/edit#slide=id.g81f938aa2b\_0\_47), [git](https://github.com/mercari/ml-system-design-pattern)
2. Seldon
3. [Medium on DL as a service by Nir Orman](https://towardsdatascience.com/serving-deep-learning-algorithms-as-a-service-6aa610368fde)
4. [Scaling ML on the cloud](https://towardsdatascience.com/scalable-efficient-big-data-analytics-machine-learning-pipeline-architecture-on-cloud-4d59efc092b5)
5. [Dapr](https://github.com/dapr/dapr) is a portable, serverless, event-driven runtime that makes it easy for developers to build resilient, stateless and stateful microservices that run on the cloud and edge and embraces the diversity of languages and developer frameworks.

Dapr codifies the best practices for building microservice applications into open, independent, building blocks that enable you to build portable applications with the language and framework of your choice. Each building block is independent and you can use one, some, or all of them in your application.

