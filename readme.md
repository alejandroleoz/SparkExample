
Spark example with Velocity template
==============

This is a very simple and quick example of Spark + Velocity.

Pre-requisites
---------------
* Maven
* Java 8 (support for Lambda expressions)

Build
---------------
mvn clean install

Run
---------------
java -cp target/SparkExample-1.0-SNAPSHOT-jar-with-dependencies.jar mago.examples.App

Usage
-------------
GET http://localhost:4567/hello     -> plain hardcoded TXT response
GET http://localhost:4567/velocity  -> TXT from velocity template
GET http://localhost:4567/json      -> JSON response

