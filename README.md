# Software Developer Tutoring

This repository contains all sources and steps to replay the Webinar "Create an API in 15 Minutes".

## Create an API in 15 Minutes

The demo has two parts:

1. The REST Service, implemented in Spring Boot and with OpenAPI YAML generation and Swagger UI: https://github.com/WildCodeSchool/sea-openapi-server
2. The REST Client, a minimalistic sample for source code generation from OpenAPI YAML and usage in a Java/Spring application: https://github.com/WildCodeSchool/sea-openapi-client

## Prerequisites

To replay the demo, the following applications must be available locally:

* Unrestricted Internet Access for Maven usage
* Local IDE installation, eg. IntelliJ or Eclipse (optional). You can download IntelliJ CE here: https://www.jetbrains.com/idea/download/
* Java 11+ (might be included in IDE)
* Maven 3+ (might be included in IDE)

## Setup

* In your IDE, import from VCS, ie. the service or the client repository URLs

Follow the instructions in the service and client repository READMEs.  
Start the REST Service first to be able to access the application with the REST Client.
