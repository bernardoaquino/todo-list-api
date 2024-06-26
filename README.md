# todo-list-api

This repository contains the source code for a Task Management API (a To-Do List).

## Features

- **CRUD for Tasks**: Create, read, update, and delete tasks.
- **Authentication and Authorization**: Implementation of authentication and authorization using JWT with Spring Security.
- **Data Validation**: Validation of parameters received through HTTP routes.
- **Database Integration**: Use of a relational database for task persistence.
- **Deployment**: Deployment of the API on the Render platform.

## Technologies Used

- **Java**: Programming language used to develop the API.
- **Spring Boot**: Framework to facilitate the creation of Java applications.
- **Spring Security**: Spring module used to implement authentication and authorization.
- **JWT**: JSON Web Tokens, used for token-based authentication.
- **Database**: Integration with a relational database.
- **Render**: Cloud platform for application deployment.

## Getting Started

To run this application on your local machine, follow these steps:

### Prerequisites

- Java JDK 17 or later
- Maven
- Git (optional, for cloning the repository)

### Installation

1. **Clone the repository (optional):**
   If you have Git installed, you can clone the repository using the following command:

   ```bash
    git clone https://github.com/bernardoaquino/todo-list-api.git
   ```

   Alternatively, you can download the source code directly from the repository page.

2. **Build the application:**

Navigate to the root directory of the project in your terminal and run:

```bash
mvn clean install
```

This command will compile the application

### Running the Application

1. **Start the application:**
After building the application, you can run it using Maven with the following command:

```bash
mvn spring-boot:run
```

This will start the application on the default port (usually 8080).

2. **Accessing the API:**
With the application running, you can access the API endpoints through `http://localhost:8080/`. Use a tool like Postman or cURL to interact with the API.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.