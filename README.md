# Java Developer Roadmap

> Roadmap to becoming a [Java](https://g.co/kgs/bzeRda) developer in 2024:

Below you can find a chart demonstrating the paths that you can take and the libraries that you would want to learn to
become a Java developer. I made this chart as a tip for everyone who asks me, "What should I learn next as a Java
developer?"

[中文版](./i18n/zh-CN/ReadMe-zh-CN.md)

## Disclaimer

> The purpose of this roadmap is to give you an idea about the landscape. The road map will guide you if you are
> confused about what to learn next, rather than encouraging you to pick what is hip and trendy. You should grow some
> understanding of why one tool would be better suited for some cases than the other and remember hip and trendy does
> not
> always mean best suited for the job

## Give a Star! :star:

If you like or are using this project to learn or start your solution, please give it a star. Thanks!

## Roadmap

![Roadmap](java-developer-roadmap.png)

## Resources

1. Prerequisites

    - [Java](https://www.java.com/en/download/)
    - [Gradle](https://gradle.org/)
      or [Maven](https://maven.apache.org/)
    - [SQL](https://www.w3schools.com/sql/default.asp)

2. General Development Skills

    - Learn GIT, create a few repositories on GitHub, share your code with other people
    - Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)
    - Don't be afraid of using Google, [Power Searching with Google](http://www.powersearchingwithGoogle.com/)
    - Read a few books about algorithms and data structures
    - Learn about implementation of a basic Authentication
    - Solid principles, etc

3. CLI Tools
    1. [args4j](http://args4j.kohsuke.org/)
    2. [JCommander](http://jcommander.org/)
    3. [airline](https://github.com/airlift/airline)

4. Web Frameworks + Routers

    1. [Spring](https://spring.io/)
    2. [Play Framework](https://www.playframework.com/)
    3. [Spark](http://sparkjava.com/)
    4. [dropwizard](https://www.dropwizard.io/en/stable/)
    5. [nanohttpd](https://github.com/NanoHttpd/nanohttpd)

5. Databases

    1. Relational
        1. [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-2017)
        2. [PostgreSQL](https://www.postgresql.org/)
        3. [MariaDB](https://mariadb.org/)
        4. [MySQL](https://www.mysql.com/)
        5. [Oracle](https://www.oracle.com/database/)
    2. Cloud Databases
        - [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db)
        - [DynamoDB](https://aws.amazon.com/dynamodb/)
    3. Search Engines
        - [ElasticSearch](https://www.elastic.co/)
        - [Opensearch](https://opensearch.org/)
        - [Algolia](https://www.algolia.com/)
    4. NoSQL
        - [MongoDB](https://www.monJavadb.com/)
        - [Redis](https://redis.io/)
        - [Apache Cassandra](http://cassandra.apache.org/)
        - [Clickhouse](https://clickhouse.com/)
        - [InfluxDB](https://www.influxdata.com/)
        - [CouchDB](http://couchdb.apache.org/)

6. ORMs

    1. [Hibernate](https://hibernate.org/)
    2. [Ebean](https://ebean.io/)

7. Caching

    1. [Caffeine](https://github.com/ben-manes/caffeine)
    2. [EHCache](http://www.ehcache.org/)
    3. [Cache2k](https://cache2k.org/)
    4. Distributed Cache
        1. [Java-Redis](https://github.com/xetorthio/jedis)
        2. [Java-Memcached](https://redislabs.com/lp/memcached-java/)
        3. [Infinispan](http://infinispan.org/)

8. Logging

    1. Log Frameworks
        - [Zap](https://github.com/uber-Java/zap)
        - [TinyLog](http://www.tinylog.org/)
        - [log4j](https://logging.apache.org/log4j)
    2. Log Management System
        - [ELK Stack](https://www.elastic.co/what-is/elk-stack)
        - [Sentry.io](http://sentry.io)
        - [Loggly.com](https://loggly.com)
        - [Tracer](https://github.com/zalando/tracer)

9. Real-Time Communication
    1. [Socket.IO](https://socket.io/)
    2. [atmosphere](https://github.com/Atmosphere/atmosphere)
    3. [webbit](https://github.com/webbit/webbit)

10. API Clients

    1. REST
        - [okhttp](https://square.github.io/okhttp/)
        - [retrofit](https://square.github.io/retrofit/)
    2. [GraphQL](https://graphql.org/)

11. Good to Know

    - [Beanvalidation](https://beanvalidation.org/)
    - [bouncycastle](https://www.bouncycastle.org/java.html)
    - [gson](https://github.com/google/gson)
    - [Apache Shiro](https://shiro.apache.org/)
    - [JJWT](https://github.com/jwtk/jjwt)
    - [RxJava](https://github.com/ReactiveX/RxJava)

12. Testing

    1. Unit, Behavior, Integration, Load Testing
        - [JUnit](http://junit.org/)
        - [JMeter](https://jmeter.apache.org/)
        - [CitrusFramework](https://citrusframework.org/)
        - [Gatling](https://gatling.io/)
        - [Tsung](http://tsung.erlang-projects.org/)
        - [Mockito](https://site.mockito.org/)
        - [Assertj](https://joel-costigliola.github.io/assertj)

    2. E2E Testing
        - [Selenium](https://github.com/tebeka/selenium)
        - [Wiremock](https://wiremock.org/)
        - [Testcontainers](https://testcontainers.com/)

13. Task Scheduling

    - [Aurora](https://aurora.apache.org/)
    - [elasticjob](https://github.com/elasticjob/elastic-job-lite)
    - [Sundial](https://github.com/knowm/Sundial)
    - [cron-utils](https://github.com/jmrozanec/cron-utils)

14. MicroServices

    1. Message-Broker
        - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-javascript.html)
        - [Apache Kafka](https://www.npmjs.com/package/kafka-node)
        - [ActiveMQ](https://github.com/apache/activemq)
        - [Apache Pulsar](https://pulsar.apache.org/)
    2. Message-Bus
        - [mbassador](https://github.com/bennidi/mbassador)
        - [rmq](https://github.com/xetorthio/rmq)
    3. Frameworks
        - [Apollo](https://spotify.github.io/apollo/)
        - [lagom-framework](https://www.lightbend.com/lagom-framework)
        - [micronaut](https://micronaut.io/)
        - [eureka](https://github.com/Netflix/eureka)
        - [helidon](https://helidon.io/#/)
        - [armeria](https://github.com/line/armeria)
    4. RPC
        - [Protocol Buffers](https://github.com/protocolbuffers/protobuf)
        - [gRPC-Java](https://github.com/grpc/grpc-java)
        - [thrift](https://thrift.apache.org/)

15. [Java-Patterns](https://github.com/iluwatar/java-design-patterns)

## Wrap Up

If you think the roadmap can be improved, please do open a PR with any updates and submit any issues. Also, I will
continue to improve this, so you might want to star this repository to revisit.

Idea from : [Golang Developer Roadmap](https://github.com/Alikhll/golang-developer-roadmap)

## Contribution

The roadmap is built using [Draw.io](https://www.draw.io/). Project file can be found at `java-developer-roadmap.xml`
file. To modify it, open draw.io, click **Open Existing Diagram** and choose `xml` file with project. It will open the
roadmap for you. Update it, upload and update the images in readme and create a PR (export as png with 400% zoom and
minify that with [Compressor.io](https://compressor.io/compress)).

- Open a pull request with improvements
- Discuss ideas in issues
- Spread the word

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)