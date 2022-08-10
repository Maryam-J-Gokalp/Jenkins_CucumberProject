# Jenkins Project
Basic cucumber framework used for running automation tests on Jenkins.

## Running locally
To run locally and generate HTML reports, use this maven goal *verify*. HTML reports should be generated under target/cucumber-html-reports
mvn verify

## Jenkins
Create a simple task by Install [Cucumber HTML report plugin](https://plugins.jenkins.io/cucumber-reports). 

mvn test

## Tags
Tags tags are **@smoke**, **@regression**. 
mvn test -Dcucumber.filter.tags="@smoke"
## Browsers
mvn test -DBROWSER=firefox
