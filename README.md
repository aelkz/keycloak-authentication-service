# Authentication Service

[![Build Status](https://travis-ci.com/ArcanjoQueiroz/keycloak-authentication-service.svg?branch=master)](https://travis-ci.com/ArcanjoQueiroz/keycloak-authentication-service)

OAuth2 Authentication Service using JBoss Keycloak 9.0.2 + Legacy Authentication SPI using EJB 3 and JPA 2 + Oracle DB Support.

This is an Authentication Service built using **JBoss Keycloak** and with **Oracle 11g database** support. Furthermore, there is an implementation of **Service Provider Interface (SPI)** in order to allow the authentication through legacy authentication database tables structure.

The SPI example was built using **EJB 3**, **JPA (Hibernate)** and **JBoss Logging** support. You can access the source code (Maven) in the *spi* directory.

## Running the example

Inside the directory *examples*, type:

```sh
$ docker-compose up
```

The Keycloak run on port *9999* and the debug port is *8787*. The Oracle XE Database uses the default port (*1521*) and *8080* (Apex).

The installation of *Docker* and *Docker-Compose* is necessary in order to run the examples in your operating system.

## Administration Console

You can access the *Administration Console* through this [link](http://localhost:9999/auth).

## Licensing

[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0.html)
