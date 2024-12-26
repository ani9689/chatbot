# ChatbotAI Application

## Overview

ChatbotAI is a Spring Boot application designed to create a chatbot using the OpenAI API. This application leverages modern technologies to provide a seamless experience for building and managing chatbots.

## Features

- Spring Boot 3.x Support
- Thymeleaf integration for UI
- Spring Web for RESTful APIs
- Validation and Configuration Processor
- Lombok for reducing boilerplate code
- DevTools for live code reloading
- Unit Testing with Spring Boot Test

## Prerequisites

- JDK 21
- Maven or Gradle for build management

## Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-repo/ChatbotAI.git
cd ChatbotAI
```

### 2. Update Maven Dependencies

Ensure the following dependencies are included in your `pom.xml`:

```xml
<parent>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-parent</artifactId>
    <version>3.2.12</version> <!-- Replace with latest version if necessary -->
    <relativePath/>
</parent>

<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-thymeleaf</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-validation</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-devtools</artifactId>
        <scope>runtime</scope>
        <optional>true</optional>
    </dependency>
    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <optional>true</optional>
    </dependency>
    <dependency>
        <groupId>com.konghq</groupId>
        <artifactId>unirest-java</artifactId>
        <version>3.14.5</version>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
</dependencies>
```

### 3. Build and Run the Application

- **Using Maven**:
    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

- **Using Gradle**:
    ```bash
    ./gradlew clean build
    ./gradlew bootRun
    ```

### 4. Testing

Run unit tests using:

```bash
mvn test
```

or 

```bash
./gradlew test
```

