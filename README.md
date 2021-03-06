# Kafka Testkit 

[![Build Status](https://travis-ci.org/datamountaineer/kafka-testkit.svg?branch=master)](https://travis-ci.org/datamountaineer/kafka-testkit)
[<img src="https://img.shields.io/badge/latest%20release-v0.7-blue.svg?label=latest%20release"/>](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.datamountaineer%22%20AND%20a%3A%22kafka-testkit%22)

This bundles various kafka test utilities that are not published to maven repositories.

Components are sources from:

- http://github.com/confluentinc/schema-registry
- http://github.com/confluentinc/examples


#Releases


| Version | Kafka Version | Confluent Version |
| ------- | --------------| ----------------- |
|0.7|1.0.0 |4.0.0|
|0.6||3.3.0|
|0.5||3.2.0|
|0.4||3.1.1|
|0.1||3.0.0|


```bash
#maven
<dependency>
	<groupId>com.datamountaineer</groupId>
	<artifactId>kafka-testkit</artifactId>
	<version>0.7</version>
</dependency>

#sbt
libraryDependencies += "com.datamountaineer" % "kafka-testkit" % "0.7"

#gradle
'com.datamountaineer:kafka-testkit:0.7'
```
