# gitlab

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=bugs)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=coverage)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=diegobotia_gitlab&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=diegobotia_gitlab)
[![CI/CD Pipeline](https://github.com/diegobotia/gitlab/actions/workflows/build.yml/badge.svg)](https://github.com/diegobotia/gitlab/actions/workflows/build.yml)


Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random Aircraft
* Get application version
* health check

Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk

### Folders Structure

In the folder `src` is located the main code of the app

In the folder `test` is located the unit tests

### How to install it

Execute:

```shell
$ mvnw spring-boot:run
```
to download the node dependencies

### How to test it

Execute:

```shell
$ mvnw clean install
```

### How to get coverage test

Execute:

```shell
$ mvwn -B package -DskipTests --file pom.xml
```