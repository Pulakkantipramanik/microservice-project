# Microservice Basic (Spring Boot)

This is a minimal Spring Boot microservice example.

## Requirements
- Java 17+ installed
- Maven installed

## How to run
1. Extract the zip and open a terminal in the project root.
2. Build the project:
   ```
   mvn clean package
   ```
3. Run the JAR:
   ```
   java -jar target/microservice-basic-0.0.1-SNAPSHOT.jar
   ```
   or run with Maven:
   ```
   mvn spring-boot:run
   ```
4. Open in browser or use curl:
   ```
   http://localhost:8080/api/hello
   ```

## Docker (optional)
Build:
```
docker build -t microservice-basic:latest .
```
Run:
```
docker run -p 8080:8080 microservice-basic:latest
```
# microservice-project
