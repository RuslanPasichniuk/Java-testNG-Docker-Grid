# Java/testNG/Selenium/Grid/Docker/Jenkins

## Summary

|                          |                                                                                           |
|--------------------------|-------------------------------------------------------------------------------------------|
|**Owner(s)**              | Ruslan Pasichniuk                                                                                          |
|**Artifact type:**        | .jar                                                                                |
|**Artifact name:**        | selenium-docker                                                                      |
|**Artifact URL:**         | N/A for now                                                                               |
|**CI URL:**               | inside container                                                                                |
|**Languages:**            | Java                                                                                      |
|**Blackbox Tests:**       | testNJ                                                                                  |
|**Distribution:**         | for fun                                                                                |

## Purpose

Here implemented a Data Driven - Test Automation Framework from scratch Using Java + TestNG;
Created Selenium Grid using Docker;
Tests are run inside a docker container;
Built a CI + CD pipeline from scratch using Jenkins, GitHub, DockerHub, AWS.

## Running Blackbox Tests

```
mvn clean 
mvn package -DskipTests
docker-compose up

in progress
 docker-compose up
 TODO build&push image from local DockerFile to DockerHub
```

##Running Our Automated Tests In AWS Cloud

```
0.03$ per day is so expensive for me 
```