# Spring Boot REST API Exercise

## Goal

The goal of this exercise is to learn how to use GitHub Copilot, using an exercise that consist of building a REST API using Spring Boot.

## Exercises

We have created a Spring Boot project with some files already created, you can find the project in the folder **exercisefiles/springboot**. 

Let's start copiloting!!!

### 1. Create the code to handle a simple GET request

Move to the [DemoController.java](exercisefiles/springboot/copilot-demo/src/main/java/com/microsoft/hackathon/copilotdemo/controller/DemoController.java) file and start writing the code to handle a simple GET request. In this first exercise, we have provided a comment that describes the code you need to generate. Just press enter and wait a couple of seconds, Copilot will generate the code for you.

> Tip: If nothing happens, then change the comment (add a word or 2) - sometimes Copilot needs a little nudge.

Then, create a new unit test for the case when no key is provided in the request.

### 2. Dates comparison

New operation under /diffdates that calculates the difference between two dates. The operation should receive two dates as parameter in format dd-MM-yyyy and return the difference in days. 

Additionally, create a unit test that validates the operation.

From now on, you will have to create the unit tests for every new operation. Wasn't it easy with Copilot? 

### 3. Validate the format of a spanish phone 

Validate the format of a spanish phone number (+34 prefix, then 9 digits, starting with 6, 7 or 9). The operation should receive a phone number as parameter and return true if the format is correct, false otherwise. 

### 4. Validate the format of a spanish DNI

Validate the format of a spanish DNI (8 digits and 1 letter). The operation should receive a DNI as parameter and return true if the format is correct, false otherwise. 

### 5. From color name to hexadecimal code

Based on existing colors.json file under resources, given the name of the color as path parameter, return the hexadecimal code. If the color is not found, return 404

### 6. Jokes creator

Create a new operation that call the API https://api.chucknorris.io/jokes/random and return the joke.

### 7. URL parsing

Given a url as query parameter, parse it and return the protocol, host, port, path and query parameters. The response should be in Json format.

### 8. List files and folders 

List files and folders under a given path. The path should be a query parameter. The response should be in Json format.

### 9. Word counting

Given the path of a file and count the number of occurrence of a provided word. The path and the word should be query parameters. The response should be in Json format.

### 10. Zipping

Create a zip file with the content of a given folder. The path of the folder should be a query parameter.











