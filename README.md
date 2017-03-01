 lagom-scala-wordcount

This is a Scala Sbt project that demonstrates the legacy word count example using the Lagom Framework.
This is a microservices based Kafka Producer/Consumer application where in the one is the producer which produces data in Kafka and persist events in Cassandra Db. The other service consumes data from Kafka and gives the word count of the words.
Here, we are using embedded Kafka and Cassandra. You can use external ones as well. For that you just need to uncomment the last 4 lines the build.sbt and install Kafka and Cassandra on your machine.

Setting up the development environment:

https://github.com/piyushknoldus/lagom-scala-wordcount/wiki/Setting-up-the-development-environment

Json Formats for different Rest services:

https://github.com/piyushknoldus/lagom-scala-wordcount/wiki/Json-Formats-for-different-Rest-services

Tools Integrated:

https://github.com/piyushknoldus/lagom-scala-wordcount/wiki/Tools-Integrated

Screen Shots: