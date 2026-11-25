# VowelCounter
A simple Java application that counts vowels in a text string.
## Requirements
- Java 21
- Maven 3.9.6
## Build the application
```bash
mvn clean compile
```
## Run the tests
```bash
mvn test
```
## Package the application
```bash
mvn clean package
```
## Run the application
```bash
java -jar target/vowel-counter-1.0.0.jar "Hello World"
```
Expected output:
```text
Input: Hello World
Number of vowels: 3
```
## Jenkins CI/CD
The project includes a Jenkinsfile that builds, tests and packages
the application automatically.
