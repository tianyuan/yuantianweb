---
title: 'Functional Programming in Scala '
author: Yuan Tian
date: '2018-01-06'
slug: functional-programming-in-scala
categories:
  - iLearn
tags:
  - '2017'
  - notes
output: 
 blogdown::html_page:
    toc: true
    toc_depth: 5
---

Functional programming (FP) finally goes [mainstream](http://www.zdnet.com/article/functional-programming-finally-goes-mainstream-heres-what-you-need-to-know/). It is not a new concept, but it is absolutely a complex one for beginners including me. I got exposed to a large set of references, online courses and books, and I will try to organize them in a useful way.  

### Why Functional Programming (FP)? Why Scala?

I enjoyed the talk given by Martin Odersky, which answer the two key questions with very simple code examples. The 15-minutes talk is [*Working Hard to Keep it Simple*](https://www.youtube.com/watch?v=3jg1AheF4n0) with [*slides*](https://www.slideshare.net/Odersky/oscon-keynote-working-hard-to-keep-it-simple) on SlideShare. 

### Where should I start with FP in Scala? [click here](http://docs.scala-lang.org/getting-started.html)

#### 1. Set up and get started in Scala: 

A super quick start will be using [Scastie](https://scastie.scala-lang.org/), Scala in browser, to jump directy into Scala without installing anything. 

You always can choose to work with an IDE such as[IntelliJ with sbt](http://docs.scala-lang.org/getting-started-intellij-track/building-a-scala-project-with-intellij-and-sbt.html), which you need to set up the environment in your local machine. 

A third option is to user [docker](https://www.docker.com/). Install docker and then use the docker image to launch [Appache Zepplin](https://zeppelin.apache.org/download.html) which has mutiple interpreters supporting Spark, Scala, Python and other languages.

* Launch Apache Zeppeline in a container. **If you haven't download it, this command will take care of the download for you**.

```
docker run -p 8080:8080 --rm --name zeppelin apache/zeppelin:0.7.3
```
* To retain the `logs` and `notebook` directories, launch it with the following command: 

```
docker run -p 8080:8080 --rm -v $PWD/logs:/logs -v $PWD/notebook:/notebook -e ZEPPELIN_LOG_DIR='/logs' -e ZEPPELIN_NOTEBOOK_DIR='/notebook' --name zeppelin apache/zeppelin:0.7.3
```
After setting up the Cassandra Spark Connector with login, here is the new command: 
```
docker run -p 8080:8080 --rm -d -v $PWD/interpreter.json:/zeppelin/conf/interpreter.json -v $PWD/logs:/logs -v $PWD/notebook:/notebook -e ZEPPELIN_LOG_DIR='/logs' -e ZEPPELIN_NOTEBOOK_DIR='/notebook' --name zeppelin apache/zeppelin:0.7.3
```


* Open your broswer, and access [`localhost：8080`](http://localhost:8080/#/) to start your session. Information about Appache Zeppelin's UI can be found [here](http://zeppelin.apache.org/docs/0.7.3/quickstart/explorezeppelinui.html). 
#### 2. Beginner's Guide

The [documentation](http://docs.scala-lang.org/getting-started.html) is always the first-hand source you need to explore. There is no better way to learn a programming language than getting your hands dirty in the codes. Of course, we need instructions and guidance. Here is a list of places that you can start: 

* The tour of [our interactive introduction to Scala on scala-exercises.com](https://www.scala-exercises.org/scala_tutorial/terms_and_types).
* [The tour of Scala](http://docs.scala-lang.org/tour/tour-of-scala.html)
* [Scala Cheatsheet for Syntactic Constructions](http://docs.scala-lang.org/cheatsheets/index.html)


