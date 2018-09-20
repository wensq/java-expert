# Java Expert Skills
The skills to master if you want to become an expert in Java Language.

* [Library](#library)
    * [Lombok](#lombok)
    * [vavr](#vavr)
    * [Guava](#guava)
    * [Flogger](#flogger)
    * [reactor](#reactor)
    * [resilience4j](#resilience4j)
    * [Objenesis](#objenesis)
* [Framework](#framework)
    * [Spring](#spring)
        * [Spring Framework](#spring-framework)
        * [Spring Data](#spring-data)
        * [Spring Boot](#spring-boot)
    * [Metrics](#metrics)
        * [Micrometer](#micrometer)
* [Service](#service)
    * [Elastic Stack](#elastic-stack)
        * [Elasticsearch](#elasticsearch)
    * [In-Memory Data Grid](#in-memory-data-grid)
        * [Apache Ignite](#apache-ignite)
* [Tool](#tool)
    * [OS](#os)
        * [dstat](#dstat)
        * [iftop](#iftop)
    * [Java](#java)
        * [BTrace](#btrace)
        * [javOSize](#javosize)
        * [vjtop](#vjtop)
        * [vjmap](#vjmap)
        * [vjdump](#vjdump)
        * [vjjmxcli](#vjjmxcli)
* [Topic](#topic)
    * [Code Style](#code-style)
        * [Guide](#code-style-guide)
        * [Plugin](#code-style-plugin)


# Library

### [Lombok](https://projectlombok.org/)
Make Java development more productive and robust.

[Features](https://projectlombok.org/features/all)
| [Twitter](https://twitter.com/hashtag/ProjectLombok)
| [Weibo](http://s.weibo.com/weibo/Lombok%2520Java)


### [vavr](http://www.vavr.io/)
Vavr (formerly called Javaslang) is an object-functional language extension to Java 8+, which aims to reduce the lines of code and increase code quality.

[User Guide](http://www.vavr.io/vavr-docs/)
| [Blog](http://blog.vavr.io/)
| [Twitter](https://twitter.com/search?q=vavr)


### [Guava](https://github.com/google/guava)
Guava is a set of core libraries that includes new collection types (such as multimap and multiset), immutable collections, a graph library, functional types, an in-memory cache, and APIs/utilities for concurrency, I/O, hashing, primitives, reflection, string processing, and much more!

[Wiki](https://github.com/google/guava/wiki)
| [Twitter](https://twitter.com/hashtag/googleguava)
| [Weibo](http://s.weibo.com/weibo/Google%2520Guava)


### [Flogger](https://google.github.io/flogger/)
Flogger is a fluent logging API for Java. It supports a wide variety of features, and has many benefits over existing logging APIs.

[Home](https://google.github.io/flogger/)
| [Benefits](https://google.github.io/flogger/benefits)
| [Best Practices](https://google.github.io/flogger/best_practice)


### [reactor](https://projectreactor.io/)
Reactor is a fourth-generation Reactive library for building non-blocking applications on
the JVM based on the Reactive Streams Specification.

[Documentation](https://projectreactor.io/docs)
| [Tutorial](https://projectreactor.io/learn)
| [Reference Guide](https://projectreactor.io/docs/core/release/reference/)
| [Twitter](https://twitter.com/projectreactor)
| [Gitter](https://gitter.im/reactor/reactor)
| [Weibo](http://s.weibo.com/weibo/Spring%2520reactor)

### [resilience4j](https://github.com/resilience4j/resilience4j)
Resilience4j is a fault tolerance library designed for Java8 and functional programming.

[User Guide](http://resilience4j.github.io/resilience4j/)
| [Twitter](https://twitter.com/search?q=resilience4j)
| [Weibo](http://s.weibo.com/weibo/resilience4j)


### [Objenesis](http://objenesis.org/)
To instantiate a new object of a particular class without calling the constructor.

[Tutorial](http://objenesis.org/tutorial.html)
| [Details](http://objenesis.org/details.html)
| [Twitter](https://twitter.com/search?q=Objenesis)
| [Weibo](http://s.weibo.com/weibo/Objenesis)


# Framework

## Spring
Spring helps development teams everywhere build simple, portable, fast and flexible JVM-based systems and applications.

[Doc](https://spring.io/docs)
| [Guides](https://spring.io/guides)
| [Projects](https://spring.io/projects)
| [Blog](https://spring.io/blog)

### [Spring Framework](http://projects.spring.io/spring-framework/)
Core support for dependency injection, transaction management, web applications, data access, messaging, testing and more.

[Reference](http://docs.spring.io/spring/docs/current/spring-framework-reference/htmlsingle/)
| [Twitter](https://twitter.com/search?q=Spring%20Framework)
| [Weibo](http://s.weibo.com/weibo/Spring%20Framework)


### [Spring Data](http://projects.spring.io/spring-data/)
Spring Data’s mission is to provide a familiar and consistent, Spring-based programming model for data access while still retaining the special traits of the underlying data store. 

It makes it easy to use data access technologies, relational and non-relational databases, map-reduce frameworks, and cloud-based data services. This is an umbrella project which contains many subprojects that are specific to a given database.

[Commons](http://docs.spring.io/spring-data/commons/docs/current/reference/html/)
| [Gemfire](http://projects.spring.io/spring-data-gemfire)
| [JPA](http://projects.spring.io/spring-data-jpa)
| [KeyValue](https://github.com/spring-projects/spring-data-keyvalue)
| [LDAP](http://projects.spring.io/spring-data-ldap)
| [MongoDB](http://projects.spring.io/spring-data-mongodb)
| [REST](http://projects.spring.io/spring-data-rest)
| [Redis](http://projects.spring.io/spring-data-redis)
| [Cassandra](http://projects.spring.io/spring-data-cassandra)
| [Solr](http://projects.spring.io/spring-data-solr)
| [Aerospike](https://github.com/spring-projects/spring-data-aerospike)
| [Couchbase](http://projects.spring.io/spring-data-couchbase)
| [DynamoDB](https://github.com/michaellavelle/spring-data-dynamodb)
| [Elasticsearch](http://projects.spring.io/spring-data-elasticsearch)
| [Hazelcast](https://github.com/hazelcast/spring-data-hazelcast)
| [Neo4j](http://projects.spring.io/spring-data-neo4j)
| [Twitter](https://twitter.com/search?q=Spring%20Data)
| [Weibo](http://s.weibo.com/weibo/Spring%20Data)


### [Spring Boot](http://projects.spring.io/spring-boot/)
Takes an opinionated view of building production-ready Spring applications. Spring Boot favors convention over configuration and is designed to get you up and running as quickly as possible.

[Reference](http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
| [Twitter](https://twitter.com/search?q=Spring%20Boot)
| [Gitter](https://gitter.im/spring-projects/spring-boot)
| [Weibo](http://s.weibo.com/weibo/Spring%20Boot)


## Metrics

### [Micrometer](http://micrometer.io/)
Vendor-neutral application metrics facade.

Micrometer provides a simple facade over the instrumentation clients for the most popular monitoring systems, allowing you to instrument your JVM-based application code without vendor lock-in. Think SLF4J, but for metrics.

[Documentation](http://micrometer.io/docs)
| [Talk: Observability 3 Ways](https://www.dotconferences.com/2017/04/adrian-cole-observability-3-ways-logging-metrics-tracing)
| [Twitter](https://twitter.com/micrometerio)
| [Weibo](http://s.weibo.com/weibo/Micrometer)


# Service

## Elastic Stack

[Blog](https://www.elastic.co/blog)
| [Community](https://www.elastic.co/community)
| [Documentation](https://www.elastic.co/guide)
| [Videos & Webinars](https://www.elastic.co/videos)


### [Elasticsearch](https://www.elastic.co/products/elasticsearch)
Elasticsearch is a distributed, RESTful search and analytics engine capable of solving a growing number of use cases.
As the heart of the Elastic Stack, it centrally stores your data so you can discover the expected and uncover the unexpected.

[Reference](https://www.elastic.co/guide/en/elasticsearch/reference/current/index.html)
| [The Definitive Guide](https://www.elastic.co/guide/en/elasticsearch/guide/current/index.html)
| [Resiliency Status](https://www.elastic.co/guide/en/elasticsearch/resiliency/current/index.html)
| [Painless Scripting Language](https://www.elastic.co/guide/en/elasticsearch/painless/current/index.html)
| [Plugins and Integrations](https://www.elastic.co/guide/en/elasticsearch/plugins/current/index.html)
| [Clients](https://www.elastic.co/guide/en/elasticsearch/client/index.html)
| [Curator Index Management](https://www.elastic.co/guide/en/elasticsearch/client/curator/current/index.html)


## In-Memory Data Grid

### [Apache Ignite](https://ignite.apache.org/)
Ignite is:
* A memory-centric data platform
* that is strongly consistent
* and highly available
* with powerful SQL,
* key-value and processing APIs

[Features](https://ignite.apache.org/features.html)
| [Use Cases](https://ignite.apache.org/usecases.html)
| [Docs](https://apacheignite.readme.io/docs)
| [Integrations](https://apacheignite-mix.readme.io/docs)
| [Examples](https://github.com/apache/ignite/tree/master/examples)
| [Tools](https://apacheignite-tools.readme.io/docs)
| [YouTube](https://www.youtube.com/channel/UChYD3lCEnzHlWioUb2sNgSg)
| [Twitter](https://twitter.com/search?q=ApacheIgnite)
| [Gitter](https://gitter.im/apacheignite/ignite)
| [Weibo](http://s.weibo.com/weibo/Apache%20Ignite)


# Tool

## OS

### [dstat](http://dag.wiee.rs/home-made/dstat/)
Dstat is a versatile replacement for vmstat, iostat, netstat and ifstat. Dstat overcomes some of their limitations and adds some extra features, more counters and flexibility. Dstat is handy for monitoring systems during performance tuning tests, benchmarks or troubleshooting. 

Dstat allows you to view all of your system resources in real-time, you can eg. compare disk utilization in combination with interrupts from your IDE controller, or compare the network bandwidth numbers directly with the disk throughput (in the same interval).

[Documentation](https://github.com/dagwieers/dstat/blob/master/docs/dstat.1.adoc)
| [Twitter](https://twitter.com/search?q=dstat)
| [Weibo](http://s.weibo.com/weibo/dstat)


### [iftop](http://www.ex-parrot.com/pdw/iftop/)
Display bandwidth usage on an interface.

iftop does for network usage what top(1) does for CPU usage. It listens to network traffic on a named interface and displays a table of current bandwidth usage by pairs of hosts.

[Man Page](https://www.systutorials.com/docs/linux/man/8-iftop/)
| [Twitter](https://twitter.com/search?q=iftop)
| [Weibo](http://s.weibo.com/weibo/iftop)


## Java

### [BTrace](https://github.com/btraceio/btrace)
BTrace is a safe, dynamic tracing tool for the Java platform.

BTrace can be used to dynamically trace a running Java program (similar to DTrace for OpenSolaris applications and OS). BTrace dynamically instruments the classes of the target application to inject tracing code ("bytecode tracing").

[User Guide](https://github.com/btraceio/btrace/wiki)
| [Maven Plugin](https://github.com/btraceio/btrace-maven)
| [Twitter](https://twitter.com/search?q=BTrace)
| [Weibo](http://s.weibo.com/weibo/BTrace)


### [javOSize](http://www.javosize.com/)
javOSize is a newly released platform that brings monitoring, diagnosing and unique repair capabilities together in a single pane of glass.

javOSize is not an APM tool. javOSize is not a profiler. javOSize is just the tool you need to keep your java applications up, running and fully functional.

[Docs](http://www.javosize.com/gettingStartedGUI/doc.html)
| [Twitter](https://twitter.com/search?q=javOSize)
| [Weibo](http://s.weibo.com/weibo/javOSize)


### [vjtop](https://github.com/vipshop/vjtools/tree/master/vjtop)
VJtop is a JVM monitoring tool to provide a dynamic real-time view of the busiest top 10 threads, which plays the similar role of the "top" command for viewing the host operation system.

[README Chinese](https://github.com/vipshop/vjtools/blob/master/vjtop/README.md)
| [README English](https://github.com/vipshop/vjtools/blob/master/vjtop/README_EN.md)
| [Weibo](http://s.weibo.com/weibo/vjtop)


### [vjmap](https://github.com/vipshop/vjtools/tree/master/vjmap)
VJMap prints per GC generation (Eden, Survivor, OldGen) object details of a given process , it is an advanced way to find the reasons of memory leak and fast-growing OldGen.

[README Chinese](https://github.com/vipshop/vjtools/blob/master/vjmap/README.md)
| [README English](https://github.com/vipshop/vjtools/blob/master/vjmap/README_EN.md)
| [Weibo](http://s.weibo.com/weibo/vjmap)


### [vjdump](https://github.com/vipshop/vjtools/tree/master/vjdump)
VJDump comes as a handy script for collecting diagnostic data for JVM during urgent failures to allow for complete analysis later.

[README Chinese](https://github.com/vipshop/vjtools/blob/master/vjdump/README.md)
| [README English](https://github.com/vipshop/vjtools/blob/master/vjdump/README_EN.md)
| [Weibo](http://s.weibo.com/weibo/vjdump)


### [vjmxcli](https://github.com/vipshop/vjtools/tree/master/vjmxcli)
VJJmxCli support connect to JVM via pid, no need to enable JMX at startup JVM options.

VJJmxCli can simulate the output of `jstat -gcutil`.

[README Chinese](https://github.com/vipshop/vjtools/blob/master/vjmxcli/README.md)
| [Weibo](http://s.weibo.com/weibo/vjmxcli)

# Topic

## Code Style

### Code Style Guide
[Google](https://google.github.io/styleguide/javaguide.html)
| [Oracle](http://www.oracle.com/technetwork/java/codeconvtoc-136057.html)
| [Alibaba](https://alibaba.github.io/Alibaba-Java-Coding-Guidelines/)
| [Vipshop](https://vipshop.github.io/vjtools/#/standard/)
| [Twitter](https://github.com/twitter/commons/blob/master/src/java/com/twitter/common/styleguide.md)
| [Spring](https://github.com/spring-projects/spring-framework/wiki/Spring-Framework-Code-Style)
| [Square](https://github.com/square/java-code-styles)


### Code Style Plugin
[Alibaba Java Coding Guidelines pmd implements and IDE plugin](https://github.com/alibaba/p3c)

[Vipshop Code Formatter](https://github.com/vipshop/vjtools/tree/master/standard/formatter)