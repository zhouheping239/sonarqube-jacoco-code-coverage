[![CI](https://github.com/tkgregory/sonarqube-jacoco-code-coverage/actions/workflows/gradle.yml/badge.svg)](https://github.com/tkgregory/sonarqube-jacoco-code-coverage/actions/workflows/gradle.yml)

Repository to accompany article _[How To Test Code Coverage Using SonarQube and Jacoco](https://gradlehero.com/how-to-measure-code-coverage-using-sonarqube-and-jacoco/)_.

[<img src="How-to-measure-code-coverage-using-SonarQube-and-Jacoco.jpg" width="500px"/>](https://gradlehero.com/how-to-measure-code-coverage-using-sonarqube-and-jacoco/)

## Pre-requisites
* JDK 8+
* Docker

## Running

#### Running SonarQube
`./gradlew composeUp`

This will run SonarQube at [locahost:9000](http://localhost:9000).
The default login is *admin/admin*, then you will need to set a new password.

#### Running a SonarQube scan
Wait for SonarQube to start, then run:

`./gradlew sonarqube`

## Stopping
`./gradlew composeDown`

## SonarQube version
This example runs against the *lts* version of SonarQube (currently SonarQube 8.9).

## Need further support?
Contact me if you need help at tom@tomgregory.com.

### Reference
https://www.youtube.com/watch?v=jrksCo-M1Ns
https://jenkinshero.com/sonarqube-quality-gates-in-jenkins-build-pipeline/
https://www.youtube.com/watch?v=6BTOd0X8UCs
