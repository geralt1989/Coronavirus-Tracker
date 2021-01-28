[![Build Status](https://travis-ci.com/geralt1989/Coronavirus-Tracker.svg?branch=master)](https://travis-ci.com/geralt1989/Coronavirus-Tracker) [![CodeFactor](https://www.codefactor.io/repository/github/geralt1989/coronavirus-tracker/badge)](https://www.codefactor.io/repository/github/geralt1989/coronavirus-tracker)

# Coronavirus-Tracker
This application lists the current number of cases reported across the globe.

## Installing
### Running the application with IDE

There are several ways to run a Spring Boot application on your local machine. One way is to execute the main method in the com.arc.sbtest.SBtemplateApplication class from your IDE.

Download the zip or clone the Git repository.
- Unzip the zip file (if you downloaded one)
- Open Command Prompt and Change directory (cd) to folder containing pom.xml
- Open Eclipse
  - File -> Import -> Existing Maven Project -> Navigate to the folder where you unzipped the zip
  - Select the project
- Choose the Spring Boot Application file (search for @SpringBootApplication)
- Right Click on the file and Run as Java Application

### Running the application with Maven
Alternatively you can use the Spring Boot Maven plugin like so:

$ git clone https://github.com/geralt1989/Coronavirus-Tracker.git

$ cd Spring-Boot-Application-Template

$ mvn spring-boot:run
