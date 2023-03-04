# DevOps Tools

### CONTINUOUS INTEGRATION

1. [Travis](https://travis-ci.org/)
2. [Circle CI](https://circleci.com/)
3. [TeamCity](https://www.jetbrains.com/teamcity/)
4. [Jenkins](https://www.jenkins.io/)
5. Github Actions
   1. [poetry black pytest](https://medium.com/@vanflymen/blazing-fast-ci-with-github-actions-poetry-black-and-pytest-9e74299dd4a5)

### Docker&#x20;

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

### Kubernetes

* For beginners:
  * [1](https://medium.com/containermind/a-beginners-guide-to-kubernetes-7e8ca56420b6), [2](https://medium.com/faun/kubernetes-basics-for-new-users-d57fdf85adba)\*, [3](https://medium.com/google-cloud/kubernetes-101-pods-nodes-containers-and-clusters-c1509e409e16)\*, [4](https://medium.com/swlh/kubernetes-in-a-nutshell-tutorial-for-beginners-caa442dfd6c0), [5](https://kubernetes.io/docs/tutorials/kubernetes-basics/)\*, 6,&#x20;
* Advanced&#x20;
  * [1](https://www.freecodecamp.org/news/learn-kubernetes-in-under-3-hours-a-detailed-guide-to-orchestrating-containers-114ff420e882/), 2, 3,
* [A list with all the tools ](https://collabnix.github.io/kubetools/)

### Helm

* [Package manager for kubernetes](https://helm.sh/)

### Kubeflow

* [Youtube - the easy way,](https://www.youtube.com/watch?v=P5wcE4IwKgQ) [intro](https://medium.com/@amina.alsherif/how-to-get-started-with-kubeflow-187792f3e99)\*, [intro2\*](https://kubernetes.io/blog/2017/12/introducing-kubeflow-composable/), [intro3](https://medium.com/better-programming/kubeflow-pipelines-with-gpus-1af6a74ec2a),
* [Really good detailed article, for example it supports many serving options such as seldon](https://ubuntu.com/blog/ml-serving-models-with-kubeflow-on-ubuntu-part-1)
* [presentation](https://www.oliverwyman.com/content/dam/oliver-wyman/v2/events/2018/March/Google\_London\_Event/Public%20Introduction%20to%20Kubeflow.pdf)
* Tutorials:
  * [Official example](https://github.com/kubeflow/example-seldon)
  * [Step by step tut](https://codelabs.developers.google.com/codelabs/cloud-kubeflow-e2e-gis/index.html?index=..%2F..index#0)\*
  * [endtoend tut](https://journal.arrikto.com/an-end-to-end-ml-pipeline-on-prem-notebooks-kubeflow-pipelines-on-the-new-minikf-ee618b7dc7de),&#x20;
  * [really detailed tut](https://towardsdatascience.com/how-to-create-and-deploy-a-kubeflow-machine-learning-pipeline-part-1-efea7a4b650f)
  * KF + [Seldon on ec2](https://docs.seldon.io/projects/seldon-core/en/latest/examples/kubeflow\_seldon\_e2e\_pipeline.html)

### MiniKF

* [Tutorial](https://journal.arrikto.com/an-end-to-end-ml-pipeline-on-prem-notebooks-kubeflow-pipelines-on-the-new-minikf-ee618b7dc7de), [youtube](https://www.youtube.com/watch?v=XZGHFktDSE0)
* [ROK - save snapshot of your env](https://journal.arrikto.com/arrikto-launches-rok-and-rok-registry-93d76eb0c3a2)

### S2i

* Builds docker images out of gits

### Terraform

1. [youtube course](https://www.youtube.com/watch?v=SLB\_c\_ayRMo)



### Tutorials&#x20;

* [Kubernetes, sklearn, s2i, gcloud, seldon random serving for ab testing](https://medium.com/analytics-vidhya/manage-ml-deployments-like-a-boss-deploy-your-first-ab-test-with-sklearn-kubernetes-and-b10ae0819dfe)
* [Polyaxon - training, argo-package/deployment , seldin -serving](https://medium.com/analytics-vidhya/polyaxon-argo-and-seldon-for-model-training-package-and-deployment-in-kubernetes-fa089ba7d60b)

### AWS Lambda

* [Comparison](https://www.bluematador.com/blog/serverless-in-aws-lambda-vs-fargate) against aws fargate

### rabbitMQ&#x20;

* [Producer broker, consumer - a tutorial on what is RMQ](https://www.cloudamqp.com/blog/2015-05-18-part1-rabbitmq-for-beginners-what-is-rabbitmq.html)
* [Part2.3](https://www.cloudamqp.com/blog/2015-05-21-part2-3-rabbitmq-for-beginners\_example-and-sample-code-python.html) - python code
* [Part 3](https://www.cloudamqp.com/blog/2015-05-27-part3-rabbitmq-for-beginners\_the-management-interface.html) -  managing
* [Part 4](https://www.cloudamqp.com/blog/2015-09-03-part4-rabbitmq-for-beginners-exchanges-routing-keys-bindings.html)

### [ActiveMQ ](http://activemq.apache.org/)

\- Apache ActiveMQ™ is the most popular open source, multi-protocol, Java-based messaging serve

### Kafka&#x20;

* [Kafka 101 youtube](https://www.youtube.com/watch?v=j4bqyAMMb7o\&list=PLa7VYi0yPIH0KbnJQcMv5N9iW8HkZHztH), [event sourcing & event storage](https://www.youtube.com/watch?v=p\_sSRwpBkgs\&list=PLa7VYi0yPIH1TXGUoSUqXgPMD2SQXEXxj\&index=1) with Kafka - confluent
* [Web](https://kafka.apache.org/)
* [Medium - really good short intro](https://medium.com/hacking-talent/kafka-all-you-need-to-know-8c7251b49ad0)
* [Intro](https://medium.com/@jcbaey/what-is-apache-kafka-e9e73884e367), [Intro 2](https://medium.com/@patelharshali136/apache-kafka-tutorial-kafka-for-beginners-a58140cef84f),&#x20;
* [Kafka in a nutshell](https://medium.com/@aiven\_io/apache-kafka-in-a-nutshell-df10dfcc7dc) - But even these solutions came up short in some cases. For example, RabbitMQ stores messages in DRAM until the DRAM is completely consumed, at which point messages are written to disk, [severely impacting performance](https://blog.mavenhive.in/which-one-to-use-and-when-rabbitmq-vs-apache-kafka-7d5423301b58).

Also, the routing logic of AMQP can be fairly complicated as opposed to Apache Kafka. For instance, each consumer simply decides which messages to read in Kafka.

In addition to message routing simplicity, there are places where developers and DevOps staff prefer Apache Kafka for its high throughput, scalability, performance, and durability; although, developers still swear by all three systems for various reasons.

* [Apache Kafka Kafka](https://medium.com/develbyte/introduction-to-zookeeper-bcda7ef136cd) is a pub-sub messaging system. It uses Zookeeper to detect crashes, to implement topic discovery, and to maintain production and consumption state for topics.
* [Tutorial on putting a model in kafka and using zoo keeper](https://towardsdatascience.com/putting-ml-in-production-i-using-apache-kafka-in-python-ce06b3a395c8) with code.

### Zoo keeper

* Intro [1](https://medium.com/@rinu.gour123/role-of-apache-zookeeper-in-kafka-monitoring-configuration-c5bd1a7e4226), [2-usecases](https://medium.com/@bikas.katwal10/zookeeper-introduction-designing-a-distributed-system-using-zookeeper-and-java-7f1b108e236e), [3\*](https://medium.com/@ben2460/about-apache-zookeeper-distributed-lock-1a990315e05c), [4](https://www.tutorialspoint.com/zookeeper/zookeeper\_overview.htm)
* What is [1](https://medium.com/@gavindya/what-is-zookeeper-db8dfc30fc9b), [2](https://medium.com/rahasak/apache-zookeeper-31b2091657a8)
* It is a [service discovery in a nutshell, kafka is using it to allow discovery, registration etc of services. So that customers can subscribe and get their publication. ](https://www.quora.com/What-is-ZooKeeper)

### KSQLDB

* KSQLDB 101 uses kafka streams to run queries over kafka, [youtube](https://www.youtube.com/watch?v=oThQzCXjuk4\&list=PLa7VYi0yPIH3ulxsOf5g43\_QiB-HOg5\_Y)

### ELK

* [Elastic on ELK](https://www.elastic.co/what-is/elk-stack)
* [Logz.io on ELK](https://logz.io/learn/complete-guide-elk-stack)
* [Hackernoon intro](https://hackernoon.com/elastic-stack-a-brief-introduction-794bc7ff7d4f)

### Logz.io

* [Intro,](https://www.youtube.com/watch?v=LqJYeeTss9Q) [What is](https://www.youtube.com/watch?v=6VVig5tnTJE)



### Programming Concepts

[Dependency injection](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/) - based on [SOLID](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design#toc-single-responsibility-principle) the class should do one thing, so we are letting other classes create 3rd party/class objects for us instead of doing it internally, either by init passing or by injecting in runtime.\


[SOLID](https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design#toc-single-responsibility-principle) - the five principles of object oriented.&#x20;

### API GATEWAY

1. [what is](https://www.javatpoint.com/introduction-to-api-gateways)

### NGINX

1. [NGINX](https://www.nginx.com/resources/glossary/nginx/) is open source software for web serving, reverse proxying, caching, load balancing, media streaming, and more. It started out as a web server designed for maximum performance and stability. In addition to its HTTP server capabilities, NGINX can also function as a proxy server for email (IMAP, POP3, and SMTP) and a reverse proxy and load balancer for HTTP, TCP, and UDP servers.
2. Cloudflare on [what is a reverse proxy](https://www.cloudflare.com/learning/cdn/glossary/reverse-proxy/)
3. "[One advantage of using NGINX as an API gateway ](https://www.nginx.com/blog/deploying-nginx-plus-as-an-api-gateway-part-1/)is that it can perform that role while simultaneously acting as a reverse proxy, load balancer, and web server for existing HTTP traffic. If NGINX is already part of your application delivery stack then it is generally unnecessary to deploy a separate API gateway"

