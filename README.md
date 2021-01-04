[![CircleCI](https://circleci.com/gh/springframeworkguru/mssc-beer-inventory-service.svg?style=svg)](https://circleci.com/gh/springframeworkguru/mssc-beer-inventory-service)
# MSSC Beer Inventory Service

This repository contains source code examples used to exercise Spring Boot Microservices course on Udemy.

Forked from [springframeworkguru / mssc-beer-inventory-service](https://github.com/springframeworkguru/mssc-beer-inventory-service/tree/initial-project). Starting branch for this repository is [develop](https://github.com/Qkiz288/mssc-beer-inventory-service/tree/develop) branch.

In order to run the application with local MySQL DB:
 - MySQL service has to be installed locally.
 - When running the main class, in `Edit Configuration / VM Options` add `-Dspring.profiles.active=localmysql` profile. 