# java-cli-maven-surefire-findbugs-jacoco-junit-test-car-data

## Description
Analyze source code for potential bugs.
A POC for sprimg app using JUnit
framework with jacoco and surefire
plugins.

## Tech stack
- java
- maven
	- findbugs
  - spring
  - junit
  - surefire
  - jacoco

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://github.com/eugenp/tutorials/tree/master/maven-modules/maven-integration-test)
- [Jacoco config](https://www.baeldung.com/jacoco)
