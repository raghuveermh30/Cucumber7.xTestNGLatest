# Cucumber7.xTestNGLatest

Cucumber7.xTestNGLatest

This repository contains a Proof of Concept (POC) for running Cucumber tests in parallel using TestNG with Cucumber 7.x. The project demonstrates how to set up and configure your test framework to execute Cucumber scenarios in parallel with TestNG.

Prerequisites
Java 8 or higher Maven 3.x

Project Structure
![image](https://github.com/user-attachments/assets/26669e44-03c1-4480-a517-c566809e6849)


Usage
Clone the repository: git clone https://github.com/naveenanimation20/Cucumber7.xTestNGLatestPOC.git

Navigate to the project directory:
cd Cucumber7.xTestNGLatest

Run the tests with Maven:
mvn clean test

The tests will execute in parallel, and you can view the test results in the target/cucumber-reports directory.

Customization
To adjust the level of parallelism, edit the testng.xml file and update the thread-count attribute to the desired number of threads:

<suite name="Cucumber Parallel Suite" verbose="1" parallel="tests" thread-count="2"> You can also add or remove elements in the testng.xml file to control the number of parallel test executions.
