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

----

## All posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      (tags: 
        {% for t in post.tags %}
          {{ t }}
        {% endfor %}
      )
    </li>
  {% endfor %}
</ul>
