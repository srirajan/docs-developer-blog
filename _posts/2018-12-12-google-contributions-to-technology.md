---

layout: post
title: "Google's contributions to technology"
date: 2018-12-12 00:00
comments: true
author: Sri Rajan
published: true
authorIsRacker: true
categories:
  - general

---

This post started as a back-on-forth discussion in a private channel where I suggested that we are slowly and surely implementing infrastructure & software, in the "Google Way". This led to a bit more research to actually write down the list of Google's contributions and influences.  Here are some guidelines followed to write this down.

 - Direct contributions - The definition of "direct", in this context, is software that is available and used in the public domain.

 - Influences - The definition of "influences", in this context, is ideas that have led to creation of software that is available and used in the public domain. 

 - The software must exist in the public domain under an open source license that has been approved by [OSI](https://opensource.org/).

 - Projects originating from events like Google's Summer of Code have been excluded as they are hard to measure and strictly speaking is not software that originated from within Google. 


**Direct Contributions**

 - Android - Arguably the most popular contribution. Android is a mobile operating system, initially developed by Android Inc., acquired by Google in 2005. The core Android source code is known as [Android Open Source Project (AOSP)](https://source.android.com/), and is primarily licensed under the Apache License. Android has been the best-selling OS worldwide on smartphones ([ref](https://www.statista.com/statistics/266210/number-of-available-applications-in-the-google-play-store/)).

 - Chromium OS - The developer version of Google's Chrome OS that implements the web/cloud based operating system. [Chromium OS](https://www.chromium.org/chromium-os) has formed the basis for other projects and some of the technology within the OS like [crossvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) has been used in container technology.

 - Control groups (cgroups) - Not as popular as Android but [cgroups] (https://en.wikipedia.org/wiki/Cgroups) addition to the Linux kernel was an important step in being able to run container engines like Docker.

 - AngularJS - A JavaScript-based open-source front-end web application framework which is maintained by Google and the community. More at [https://github.com/angular/angular](https://github.com/angular/angular) 

- Kubernetes - Kubernetes(K8s) is an open-source container-orchestration platform was originally designed by Google has its roots in Google's [Borg](https://ai.google/research/pubs/pub43438) and Google's learnings on Container management ([ref](https://queue.acm.org/detail.cfm?id=2898444)). 

- GoLang - Golang is a programming language, compiled, and syntactically similar to C but has some of the dynamic features of Python ([ref](https://techcrunch.com/2009/11/10/google-go-language/)). It has seen increased popularity since 2009 and is used by software such as Docker([ref](https://www.slideshare.net/jpetazzo/docker-and-go-why-did-we-decide-to-write-docker-in-go)).

- Tensorflow - TensorFlow is a programming library used for machine learning applications which Google open sourced in 2015 ([ref](https://www.wired.com/2015/11/google-open-sources-its-artificial-intelligence-engine/)).

**Influences**
 
 - MapReduce - Google invented MapReduce to manage search on a large-scale. 
Google published a [white paper](http://static.googleusercontent.com/media/research.google.com/en/us/archive/mapreduce-osdi04.pdf) describing the MapReduce programming model laid the foundation for Apache Hadoop ([ref] (https://books.google.co.uk/books?id=axruBQAAQBAJ&pg=PA300&redir_esc=y#v=onepage&q&f=false)).

- Hbase - Similar to Mapreduce, Google's Bigtable [whitepaper](http://static.googleusercontent.com/media/research.google.com/en/us/archive/bigtable-osdi06.pdf) laid the foundation for Apache Hbase.

- Chubby - Chubby is a distributed lock service intended for use within Google’s distributed systems. Apache ZooKeeper is the open source implementation based on Google’s Chubby [whitepaper](http://static.googleusercontent.com/media/research.google.com/en/us/archive/chubby-osdi06.pdf). Worth mentioning that ZooKeeper has evolved into other areas like metadata storage.

- Dremel - Dremel is a distributed system developed at Google for querying large datasets. It is used in Google Cloud's BigQuery service. Apache Drill was inspired by this and is a top level Apache project ([ref](https://drill.apache.org/docs/architecture-introduction/)).

 
There is probably more we can dig up, but this list is good enough to back up the reputation of Google an engineering company with an open source culture, and the impact these contributions have had. While these contributions have also resulted in value for Google, they have significantly shaped the software we use and run today. 


<table>
  <tr>If you liked this blog, share it by using the following icons:</tr>
  <tr>
   <td>
       <img src="{% asset_path line-tile.png %}" width=50 >
    </td>
    <td>
      <a href="https://twitter.com/home?status=https%3A//developer.rackspace.com/blog/google-contributions-to-technology/">
        <img src="{% asset_path shareT.png %}">
      </a>
    </td>
    <td>
       <img src="{% asset_path line-tile.png %}" width=50 >
    </td>
    <td>
      <a href="https://www.facebook.com/sharer/sharer.php?u=https%3A//developer.rackspace.com/blog/google-contributions-to-technology/">
        <img src="{% asset_path shareFB.png %}">
      </a>
    </td>
    <td>
       <img src="{% asset_path line-tile.png %}" width=50 >
    </td>
    <td>
      <a href="https://www.linkedin.com/shareArticle?mini=true&url=https%3A//developer.rackspace.com/blog/google-contributions-to-technology&summary=&source=">
        <img src="{% asset_path shareL.png %}">
      </a>
    </td>
  </tr>
</table>


</br>
