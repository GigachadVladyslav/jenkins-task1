# Task on Jenkins Topic

Here is a Java application that uses Maven as the build system. The goal is to set up Jenkins to automate the build and testing process for this application.
So, write a **Jenkinsfile** in the root of the repository and define there:
- [build](https://www.baeldung.com/maven-skipping-tests) steps and [unit tests](https://howtodoinjava.com/maven/maven-run-junit-tests/) steps
- set the **APP_PORT=9090** [environment variable](https://www.jenkins.io/doc/pipeline/tour/environment/) to run the application on port 9090
- create and running a Jenkins pipeline job

