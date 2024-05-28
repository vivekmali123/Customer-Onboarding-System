# Camunda Spring Boot Application
Spring Boot Application using [Camunda](http://docs.camunda.org).

# Customer On Boarding System
Customer onboarding is the process that a new customer goes through in order to start using a product or service that they've agreed to purchase. It covers the entire journey from the moment the sales team convinces them to move forward until they are fully integrated into using what your business has to offer. I built this project with prespective of Bank.

This project has been generated by the Maven archetype
[camunda-archetype-spring-boot-7.21.0](https://docs.camunda.org/manual/latest/user-guide/process-applications/maven-archetypes/).

## Used Camunda BPM, that allows organizations to pause business processes, implement changes, and re-execute them.
[BPMN Process](src/main/resources/process.bpmn)

## For using this project you need to download camunda modeler and integrate it with ide.

### Unit Test
You can run the JUnit test [ProcessTest](src/test/java/com/mbi/loan/originating/system/ProcessTest.java) in your IDE or using:

```bash
mvn clean test
```

### Running the application
we build and run the process application with Spring Boot.

#### Manually
1. Build the application using:

```bash
mvn clean package
```
2. Run the *.jar file from the `target` directory using:

```bash
java -jar target/loan-originating-system.jar
```

For a faster 1-click (re-)deployment see the alternatives below.

#### Maven Spring Boot Plugin
1. Build and deploy the process application using:

```bash
mvn clean package spring-boot:run
```

#### Your Java IDE
1. Run the project as a Java application in your IDE using CamundaApplication as the main class.

### Run and Inspect with Tasklist and Cockpit
Once you deployed the application you can run it using
[Camunda Tasklist](http://docs.camunda.org/latest/guides/user-guide/#tasklist)
and inspect it using
[Camunda Cockpit](http://docs.camunda.org/latest/guides/user-guide/#cockpit).

## Environment Restrictions
Built and tested against Camunda Platform version 7.21.0.
Requires JDK 17.

## Known Limitations

## License
[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

<!-- Tweet
New @Camunda example: Camunda Spring Boot Application - Spring Boot Application using [Camunda](http://docs.camunda.org). https://github.com/camunda-consulting/code/tree/master/snippets/loan-originating-system
-->
