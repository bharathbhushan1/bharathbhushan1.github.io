---
layout: page
title: About
permalink: /about/
---

## Me
I am Bharath Bhushan, a software engineer residing in
[Bengaluru](https://en.wikipedia.org/wiki/Bangalore),
[India](https://en.wikipedia.org/wiki/India). This website captures my learning
in the areas of [Big Data](https://en.wikipedia.org/wiki/Big_data) and
[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning). I am
also interested in [Indian history](https://en.wikipedia.org/wiki/History_of_India), [philosophy](https://en.wikipedia.org/wiki/Indian_philosophy) and [Dharma](https://en.wikipedia.org/wiki/Dharma).

## Contact information
* bharath.bhushan.id@gmail.com
* [Twitter](https://twitter.com/bharath_bhushan)
* [LinkedIn](https://in.linkedin.com/in/bharath-bhushan-5a8bb83)
* [Github](https://github.com/bharathbhushan1/)

## My journey

* [Qubole](https://www.qubole.com) (last role was Director Engineering, 2014-2018)
* [Appcito](https://twitter.com/appcito?lang=en) (Consulting Software Engineer, 2014)
* [Google](https://about.google/intl/en/) (Software Engineer III, 2011-2014)
* [Zscaler](https://www.zscaler.com) (Senior Software Engineer, 2007-2011)
* [NetScaler/Citrix](https://en.wikipedia.org/wiki/NetScaler) (Senior Software Engineer, 2004-2007)
* [IIT Madras](https://www.iitm.ac.in) (MTech, Computer Science, 2002-2004)
* [RVCE](https://www.rvce.edu.in) (B.E., Computer Science, 1998-2002)

## Patents
This is a list of some of my [patents](https://patents.google.com/?assignee=%22bharath+bhushan%22&oq=%22bharath+bhushan%22)

## Talks
I have given a [talk](https://www.youtube.com/watch?v=TGclcIv_QeU) at a Spark meetup. I have participated in a group discussion on Apache Spark at Fifth Elephant (2017).

## Important products/features
Some of the important products/features which I have been involved in:
* Qubole
  * [Deep Learning AMI](https://docs.qubole.com/en/latest/user-guide/data-science/deeplearning/)
  * [Dynamic Filtering in Apache Spark](https://www.qubole.com/blog/enhance-spark-performance-with-dynamic-filtering/)
  * [Direct writes with Apache Spark](https://www.qubole.com/blog/direct-writes-to-increase-spark-performance/)
  * [Apache Spark on AWS Lambda](https://www.qubole.com/blog/spark-on-aws-lambda/) ([Github source](https://github.com/qubole/spark-on-lambda))
  * [Optimizing listing in Apache Spark](https://www.qubole.com/blog/optimizing-split-computation-in-apache-spark/)
  * [Improving performance of Recover Partitions in Apache Spark](https://www.qubole.com/blog/recover-partitions-performance-spark-on-qubole/)
* Google
  * [Pre-Resolve DNS in mod_pagespeed](https://www.modpagespeed.com/doc/filter-insert-dns-prefetch)
  * [Pre-Resolve DNS in PageSpeed](https://developers.google.com/speed/pagespeed/service/PreResolveDns)
  * [Audit logging for PageSpeed](https://developers.google.com/speed/pagespeed/service/settings)
  * [Rewriter configuration for PageSpeed](https://developers.google.com/speed/pagespeed/service/settings)
* Zscaler
  * [Bandwidth control for Zscaler](https://www.zscaler.com/products/bandwidth-control)
  * [Bandwidth control policies for Zscaler](https://help.zscaler.com/zia/configuring-bandwidth-control-policy)
  * [Zscaler Central Authority](https://help.zscaler.com/zia/about-zscaler-cloud-architecture)
* NetScaler/Citrix
  * [Integrated Caching in Netscaler](https://docs.citrix.com/en-us/netscaler/12/optimization/integrated-caching.html)

## Old stuff
At various times in the past I used to maintain a blog on [medium](https://medium.com/@manku_timma1), [github](http://manku-timma.github.io) and on [write.as](https://write.as/bharathbhushan/). I have now merged all those articles into this blog. I intend to henceforth maintain this as my only blog site.

I used to maintain a github account [here](https://github.com/manku-timma). I have stopped working on that and moved to the [new one](https://github.com/bharathbhushan1) now.

----

## All blog posts
<ul>
  {% for post in site.posts %}
    <li> {{ post.date | date_to_string }}:
      <a href="{{ post.url }}">{{ post.title }}</a>
      (tags: {{ post.tags | array_to_sentence_string }})
    </li>
  {% endfor %}
</ul>
