# CobSpecServer

## Description

An HttpServer conforming with CobSpec

## Dependencies

##### Execution
* Java 1.7

##### Testing
* JUnit
* Hamcrest

##### Build tool
* Gradle

## Run tests
`gradle test --info`

## Compile and run
`gradle shadowJar` will compile the *.jar file at `build/libs/cobspec-server.jar`.

The Server requires two arguments:

* `-p` for the port.
* `-d` for the directory to serve files from.

example: `java -jar build/libs/cobspec-server.jar -p 9999 -d ~`
