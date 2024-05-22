# RPG Game Admin Panel

This project is a role-playing game (RPG) admin panel implemented in Java using the Spring Boot framework. The application provides a RESTful API for managing player accounts, and the admin panel is a web interface for interacting with the API.

## Project Overview

The project encompasses several key features, including:

- **Admin Panel:** A user-friendly web interface that allows you to view and manage player accounts.
- **Player Operations:** The admin panel supports various operations such as creating new player accounts, updating existing accounts, and deleting accounts.
- **Pagination:** The admin panel includes pagination functionality to navigate through the player list.

## Setup and Configuration

### Prerequisites

- Java 1.8
- Maven
- MySQL 8.0.30
- Tomcat 9
- Hibernate 5.6.11.Final

### Installation

1. **Clone the Project Repository:** Clone the repository to your local machine.
2. **Open the Project:** Open the project in your preferred IDE (e.g., IntelliJ IDEA).
3. **Build the Project:** Build the project using Maven (`mvn clean install`).
4. **Download and Install Tomcat 9:** Follow the official Tomcat documentation for installation instructions.
5. **Configure the Program Launch through IDEA:** Follow the official IntelliJ IDEA documentation for configuration instructions.
6. **Run the Program:** Execute the `Main` class to start the application.

## Usage

Ensure that the Spring Boot application is running to handle API requests. Open the HTML admin panel (`index.html`) in a web browser. The panel allows you to view and manage player accounts.

## Built With

- **Spring Boot:** The framework used for the backend.
- **Hibernate:** Used to interact with the MySQL database.
- **MySQL:** The database used.
- **jQuery:** Used for asynchronous communication.
- **P6Spy:** Used for database connection spying.
