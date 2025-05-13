Project: Create a Simple Spring Boot Application
Objectives

By the end of this project, you should be able to:

    Set up and configure a Spring Boot project.
    Build a REST API with basic endpoints.
    Use annotations like @RestController, @GetMapping, and @PostMapping to handle HTTP requests.
    Integrate the application with a simple database (H2 or MySQL).
    Perform CRUD operations (Create, Read, Update, Delete) using Spring Data JPA.

Project Description

You are tasked with developing a simple Spring Boot application. The application will:

    Create RESTful APIs for managing a list of students.
    Allow the user to perform CRUD operations on student data, such as adding, updating, deleting, and retrieving students.
    Use Spring Boot features like auto-configuration, embedded server, and Spring Data JPA for database interactions.

Instructions
Step 1: Setup the Project

    Use Spring Initializer 

    Links to an external site. to generate a new Spring Boot project.
        Add the necessary dependencies: Spring Web, Spring Data JPA, and H2 Database (or MySQL).
    Import the generated project into your preferred IDE (IntelliJ, Eclipse, etc.).

Step 2: Create the Student Entity

    Define a Student class to represent the structure of the data you’ll manage.
    Include fields like id, name, email, and age to represent student details.
    Configure this class as a database entity to allow persistence.

Step 3: Create the Student Repository

    Create a repository interface to handle database interactions.
    Use the repository to perform operations like saving, retrieving, updating, and deleting student records.

Step 4: Create the Student Controller

    Build a REST controller to expose the endpoints for your application.
    Define endpoints to perform CRUD operations on student data, such as:
        Get All Students
        Add a New Student
        Update a Student
        Delete a Student

Step 5: Configure the Application

    Use the application.properties file to configure the database (e.g., H2 or MySQL).
    Enable features like the H2 console for easier database visualization (if using H2).

Step 6: Run and Test the Application

    Start the Spring Boot application using the main() method in the Application class.
    Test the endpoints using tools like Postman, cURL, or your web browser.
    Verify that data can be created, retrieved, updated, and deleted successfully.

Learning Outcomes

By completing this project, you will:

    Understand how to set up and run a Spring Boot application.
    Learn to create RESTful APIs using controllers and annotations.
    Gain experience with database integration and CRUD operations using Spring Data JPA.
    Develop problem-solving skills by implementing real-world backend functionalities.
    Use tools like Postman to test and debug APIs.
