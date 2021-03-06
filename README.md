# Java framework for Cadence [![Build Status](https://travis-ci.com/uber-java/cadence-client.svg?branch=master)](https://travis-ci.com/uber-java/cadence-client) [![Javadocs](https://www.javadoc.io/badge/com.uber.cadence/cadence-client.svg)](https://www.javadoc.io/doc/com.uber.cadence/cadence-client)


[Cadence](https://github.com/uber/cadence) is a distributed, scalable, durable, and highly available orchestration engine we developed at Uber Engineering to execute asynchronous long-running business logic in a scalable and resilient way.

`cadence-client` is the framework for authoring workflows and activities in Java.

If you are authoring in Go, see [Go Cadence Client](https://github.com/uber-go/cadence-client).

## Samples

For samples, see [Samples for the Java Cadence client](https://github.com/uber/cadence-java-samples).

## Run Cadence Server

Run Cadence Server using Docker Compose:

    curl -O https://raw.githubusercontent.com/uber/cadence/master/docker/docker-compose.yml
    docker-compose up

If this does not work, see instructions for running the Cadence Server at https://github.com/uber/cadence/blob/master/README.md.

## Get CLI

[CLI is avaialable as an executable or as a docker image](https://github.com/uber/cadence/blob/master/tools/cli/README.md)

# Build a configuration

Add *cadence-client* as a dependency to your *pom.xml*:

    <dependency>
      <groupId>com.uber.cadence</groupId>
      <artifactId>cadence-client</artifactId>
      <version>2.4.1</version>
    </dependency>
    
or to *build.gradle*:

    compile group: 'com.uber.cadence', name: 'cadence-client', version: '2.4.1'

# Documentation

The documentation on how to use the Cadence Java client is [here](https://cadenceworkflow.io/docs/javaclient/).

Javadocs for the client API are located [here](https://www.javadoc.io/doc/com.uber.cadence/cadence-client).

