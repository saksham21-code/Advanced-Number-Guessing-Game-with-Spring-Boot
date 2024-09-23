# Advanced Number Guessing Game with Spring Boot

## Overview

The Advanced Number Guessing Game is a web application developed using Spring Boot. This game allows users to guess a randomly generated number within a specified range through a RESTful API. The application provides feedback on whether the guess is too high or too low and keeps track of the user's attempts.

## Features

- RESTful API for number guessing
- Random number generation
- Configurable range for the random number
- Feedback on guesses (too high, too low)

## Technologies Used

- Java
- Spring Boot
- Spring MVC
- Maven
- REST API

## Setup and Running the Application

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- Apache Maven

### Steps

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/Advanced-Number-Guessing-Game-with-Spring-Boot.git
    cd Advanced-Number-Guessing-Game-with-Spring-Boot
    ```

2. **Build the project**:
    ```sh
    mvn clean install
    ```

3. **Run the application**:
    ```sh
    mvn spring-boot:run
    ```

4. **Access the application**:
    Open your browser and navigate to `http://localhost:8080`


### Start a New Game

### Make a Guess
- **Description**: Submits a guess for a given game ID and returns feedback.
- **Request Body**:
    ```json
    {
      "gameId": "string",
      "guess": "number"
    }
    ```
- **Response**:
    ```json
    {
      "status": "string",
      "message": "string",
      "attempts": "number"
    }
    ```




