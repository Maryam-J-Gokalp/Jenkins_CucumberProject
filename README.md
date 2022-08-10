# Jenkins Project
This framework is a basic to run jenkins automation project (basico projecto de cucumber usando jenkins project) 

## Running locally
WE To run locally *verify*. HTML reports should be generated under target/cucumber-html-reports
mvn verify

## Jenkins
Create a simple task by Install [Cucumber HTML report plugin](https://plugins.jenkins.io/cucumber-reports). 

mvn test

## Tags
Tags tags are **@smoke**, **@regression**. 
mvn test -Dcucumber.filter.tags="@smoke"
## Browsers
mvn test -DBROWSER=firefox
