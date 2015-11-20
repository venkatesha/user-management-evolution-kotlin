# Migration From Java to Kotlin

## Background
This repository demonstrates the evolution of a Java/SpringBoot based
application to a Kotlin/SpringBoot application.

## Running

### Prerequisites

* RabbitMQ must be running.

### Running the platform services

Use `./run-platform.sh` to run and `./stop-platform.sh` to stop.

### Running the applications

Use `./run-apps.sh` to run and `./stop-apps.sh` to stop.

### Running tests

1. Run the platform services
1. Run the applications
1. Run the tests with `./gradlew systemTests:test`

## Windows users

Substitute `gradlew.bat` for `./gradlew`.
