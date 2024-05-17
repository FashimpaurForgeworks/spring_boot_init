# Getting Started

### Reference Documentation

For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.5/maven-plugin/reference/html/#build-image)
* [Spring Boot Testcontainers support](https://docs.spring.io/spring-boot/docs/3.2.5/reference/html/features.html#features.testing.testcontainers)
* [Testcontainers RabbitMQ Module Reference Guide](https://java.testcontainers.org/modules/rabbitmq/)
* [Testcontainers Kafka Modules Reference Guide](https://java.testcontainers.org/modules/kafka/)
* [Testcontainers MySQL Module Reference Guide](https://java.testcontainers.org/modules/databases/mysql/)
* [Testcontainers Postgres Module Reference Guide](https://java.testcontainers.org/modules/databases/postgres/)
* [Spring for RabbitMQ](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#messaging.amqp)
* [Spring for RabbitMQ Streams](https://docs.spring.io/spring-amqp/reference/stream.html)
* [Contract Stub Runner](https://cloud.spring.io/spring-cloud-contract/reference/htmlsingle/index.html#features-stub-runner)
* [Spring Configuration Processor](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#appendix.configuration-metadata.annotation-processor)
* [Spring Data JDBC](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#data.sql.jdbc)
* [Spring Data JPA](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#data.sql.jpa-and-spring-data)
* [Spring Data Redis (Access+Driver)](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#data.nosql.redis)
* [Spring Data Reactive Redis](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#data.nosql.redis)
* [Rest Repositories](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#howto.data-access.exposing-spring-data-repositories-as-rest)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#using.devtools)
* [Docker Compose Support](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#features.docker-compose)
* [Spring for Apache Kafka](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#messaging.kafka)
* [Apache Kafka Streams Support](https://docs.spring.io/spring-kafka/docs/current/reference/html/#streams-kafka-streams)
* [Apache Kafka Streams Binding Capabilities of Spring Cloud Stream](https://docs.spring.io/spring-cloud-stream/docs/current/reference/htmlsingle/index.html#_kafka_streams_binding_capabilities_of_spring_cloud_stream)
* [OAuth2 Authorization Server](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web.security.oauth2.authorization-server)
* [OAuth2 Client](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web.security.oauth2.client)
* [OAuth2 Resource Server](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web.security.oauth2.server)
* [Okta Spring Boot documentation](https://github.com/okta/okta-spring-boot#readme)
* [Spring REST Docs](https://docs.spring.io/spring-restdocs/docs/current/reference/htmlsingle/)
* [Spring Security](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web.security)
* [Testcontainers](https://java.testcontainers.org/)
* [Thymeleaf](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web.servlet.spring-mvc.template-engines)
* [Spring Web Services](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#io.webservices)
* [Spring Reactive Web](https://docs.spring.io/spring-boot/docs/3.2.5/reference/htmlsingle/index.html#web.reactive)

### Guides

The following guides illustrate how to use some features concretely:

* [Messaging with RabbitMQ](https://spring.io/guides/gs/messaging-rabbitmq/)
* [Using Spring Data JDBC](https://github.com/spring-projects/spring-data-examples/tree/master/jdbc/basics)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/)
* [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/)
* [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/)
* [Accessing Neo4j Data with REST](https://spring.io/guides/gs/accessing-neo4j-data-rest/)
* [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/)
* [Samples for using Apache Kafka Streams with Spring Cloud stream](https://github.com/spring-cloud/spring-cloud-stream-samples/tree/master/kafka-streams-samples)
* [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/)
* [Okta-Hosted Login Page Example](https://github.com/okta/samples-java-spring/tree/master/okta-hosted-login)
* [Custom Login Page Example](https://github.com/okta/samples-java-spring/tree/master/custom-login)
* [Okta Spring Security Resource Server Example](https://github.com/okta/samples-java-spring/tree/master/resource-server)
* [Securing a Web Application](https://spring.io/guides/gs/securing-web/)
* [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/)
* [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/)
* [Handling Form Submission](https://spring.io/guides/gs/handling-form-submission/)
* [Producing a SOAP web service](https://spring.io/guides/gs/producing-web-service/)
* [Building a Reactive RESTful Web Service](https://spring.io/guides/gs/reactive-rest-service/)

## OAuth 2.0 and OIDC with Okta

If you don't have a free Okta developer account, you can create one with [the Okta CLI](https://cli.okta.com):

```bash
$ okta register
```

Then, register your Spring Boot app on Okta using:

```bash
$ okta apps create
```

Select **Web** > **Okta Spring Boot Starter** and accept the default redirect URIs.

### Docker Compose support

This project contains a Docker Compose file named `compose.yaml`.
In this file, the following services have been defined:

* mysql: [`mysql:latest`](https://hub.docker.com/_/mysql)
* postgres: [`postgres:latest`](https://hub.docker.com/_/postgres)
* rabbitmq: [`rabbitmq:latest`](https://hub.docker.com/_/rabbitmq)
* redis: [`redis:latest`](https://hub.docker.com/_/redis)

Please review the tags of the used images and set them to the same as you're running in production.

### Testcontainers support

This project
uses [Testcontainers at development time](https://docs.spring.io/spring-boot/docs/3.2.5/reference/html/features.html#features.testing.testcontainers.at-development-time).

Testcontainers has been configured to use the following Docker images:

* [`confluentinc/cp-kafka:latest`](https://hub.docker.com/r/confluentinc/cp-kafka)
* [`mysql:latest`](https://hub.docker.com/_/mysql)
* [`postgres:latest`](https://hub.docker.com/_/postgres)
* [`rabbitmq:latest`](https://hub.docker.com/_/rabbitmq)
* [`redis:latest`](https://hub.docker.com/_/redis)

Please review the tags of the used images and set them to the same as you're running in production.

