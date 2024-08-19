# Coding exercises I completed during Fundmore.ai's software engineer training program.

## Technology stack
* Sequelize: https://sequelize.org/docs/v6/getting-started/
* PostgreSQL: https://www.postgresql.org/docs/current/
* NodeJS: https://nodejs.org/docs/latest/api/
* NestJS: https://docs.nestjs.com/
* AWS: https://docs.aws.amazon.com/
* Serverless: https://www.serverless.com/framework/docs
* Angular: https://angular.dev/overview

## Chapter 1: Introduction to NodeJS

### Learning Resources
- [NodeJS Documentation](https://nodejs.org/docs/latest/api/)

### Exercises

#### Beginner
- **Task:** Create a simple NodeJS application.
  - **Requirements:**
    - Read a text file (`input.txt`) and print its content to the console.
  - **Objective:** Learn basic file operations and console logging.
  - **Resources:** [NodeJS FS Module](https://nodejs.org/docs/latest/api/fs.html)

#### Intermediate
- **Task:** Develop a RESTful API with Express.
  - **Requirements:**
    - Create endpoints for CRUD operations on a list of books (`title`, `author`, `publication year`).
    - Use JSON for request and response bodies.
    - Store the data in memory (no database).
  - **Objective:** Understand basic routing, request handling, and JSON responses.
  - **Resources:** [Express.js Documentation](https://expressjs.com/)

#### Advanced
- **Task:** Implement middleware in your Express application.
  - **Requirements:**
    - Create middleware for logging request details (method, URL, timestamp).
    - Create middleware for error handling to return a JSON error response with status code.
  - **Objective:** Learn middleware integration and advanced request processing.
  - **Resources:** [Express Middleware](https://expressjs.com/en/guide/using-middleware.html)

## Chapter 2: Introduction to PostgreSQL

### Learning Resources
- [PostgreSQL Documentation](https://www.postgresql.org/docs/current/)

### Exercises

#### Beginner
- **Task:** Install PostgreSQL and create a database.
  - **Requirements:**
    - Create a database named `library`.
    - Create a table named `users` with columns `id`, `name`, and `email`.
  - **Objective:** Get familiar with PostgreSQL installation and basic SQL commands.
  - **Resources:** [PostgreSQL Installation](https://www.postgresql.org/download/)

#### Intermediate
- **Task:** Write SQL queries to manipulate the `users` table.
  - **Requirements:**
    - Insert at least 3 records into the `users` table.
    - Update the email of one user.
    - Delete one user.
    - Select all users and print the results.
  - **Objective:** Practice basic SQL operations and understand CRUD operations in SQL.
  - **Resources:** [PostgreSQL SQL Commands](https://www.postgresql.org/docs/current/sql-commands.html)

#### Advanced
- **Task:** Create a complex database schema.
  - **Requirements:**
    - Create a table named `orders` with columns `id`, `user_id`, `product_name`, and `order_date`.
    - Establish a one-to-many relationship between `users` and `orders` using `user_id` as a foreign key.
    - Write queries to fetch users with their orders.
  - **Objective:** Learn about database normalization and relationship modeling.
  - **Resources:** [PostgreSQL Foreign Keys](https://www.postgresql.org/docs/current/tutorial-fk.html)

## Chapter 3: Introduction to Sequelize

### Learning Resources
- [Sequelize Documentation](https://sequelize.org/docs/v6/getting-started/)

### Exercises

#### Beginner
- **Task:** Set up Sequelize in a NodeJS project.
  - **Requirements:**
    - Connect Sequelize to a PostgreSQL database.
    - Define a model named `User` with fields `name` and `email`.
  - **Objective:** Learn to configure Sequelize and define models.
  - **Resources:** [Sequelize Models](https://sequelize.org/docs/v6/core-concepts/model-basics/)

#### Intermediate
- **Task:** Implement CRUD operations using Sequelize.
  - **Requirements:**
    - Perform CRUD operations (create, read, update, delete) on the `User` model.
    - Use Sequelize methods to handle database interactions.
  - **Objective:** Practice using Sequelize for basic database operations.
  - **Resources:** [Sequelize CRUD Operations](https://sequelize.org/docs/v6/core-concepts/model-querying-basics/)

#### Advanced
- **Task:** Define associations between models.
  - **Requirements:**
    - Define a `Post` model with fields `title` and `content`.
    - Establish a one-to-many relationship between `User` and `Post`.
    - Write queries to fetch users with their posts.
  - **Objective:** Understand associations and complex querying.
  - **Resources:** [Sequelize Associations](https://sequelize.org/docs/v6/core-concepts/assocs/)

## Chapter 4: Introduction to NestJS

### Learning Resources
- [NestJS Documentation](https://docs.nestjs.com/)

### Exercises

#### Beginner
- **Task:** Create a basic NestJS application.
  - **Requirements:**
    - Create one module, controller, and service.
    - Implement a simple GET endpoint that returns "Hello, NestJS!".
  - **Objective:** Get familiar with the NestJS framework structure.
  - **Resources:** [NestJS First Steps](https://docs.nestjs.com/first-steps)

#### Intermediate
- **Task:** Build a RESTful API in NestJS.
  - **Requirements:**
    - Create CRUD endpoints for a `Task` resource (`title`, `description`, `status`).
    - Use DTOs for data transfer and validation.
  - **Objective:** Learn about DTOs, validation, and request handling in NestJS.
  - **Resources:** [NestJS Controllers](https://docs.nestjs.com/controllers)

#### Advanced
- **Task:** Integrate Sequelize with NestJS.
  - **Requirements:**
    - Set up Sequelize in a NestJS application.
    - Create models for `User` and `Post`.
    - Implement endpoints to manage users and their posts.
  - **Objective:** Combine NestJS with Sequelize for database interactions.
  - **Resources:** [NestJS with Sequelize](https://docs.nestjs.com/techniques/database#sequelize-integration)

## Chapter 5: Introduction to Angular

### Learning Resources
- [Angular Documentation](https://angular.io/docs)

### Exercises

#### Beginner
- **Task:** Set up an Angular application.
  - **Requirements:**
    - Create a new Angular project.
    - Create a simple component that displays "Hello, Angular!".
  - **Objective:** Get familiar with Angular setup and basic components.
  - **Resources:** [Angular Getting Started](https://angular.io/start)

#### Intermediate
- **Task:** Develop a basic Angular application.
  - **Requirements:**
    - Create components for listing and adding `Products`.
    - Implement a service to manage product data.
  - **Objective:** Learn about services, components, and data binding in Angular.
  - **Resources:** [Angular Components and Services](https://angular.io/guide/component-interaction)

#### Advanced
- **Task:** Build a full-featured Angular application.
  - **Requirements:**
    - Create components for listing, adding, updating, and deleting `Orders`.
    - Implement routing to navigate between different views.
    - Integrate form validation.
  - **Objective:** Understand advanced component interactions, routing, and form handling.
  - **Resources:** [Angular Forms and Routing](https://angular.io/guide/forms-overview)

## Chapter 6: Introduction to AWS

### Learning Resources
- [AWS Documentation](https://docs.aws.amazon.com/)

### Exercises

#### Beginner
- **Task:** Create an S3 bucket using the AWS Management Console.
  - **Requirements:**
    - Create a bucket named `my-internship-bucket`.
    - Upload a file to the bucket.
  - **Objective:** Learn the basics of S3 and the AWS Console.
  - **Resources:** [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html)

#### Intermediate
- **Task:** Set up an EC2 instance.
  - **Requirements:**
    - Launch an EC2 instance with Amazon Linux 2.
    - SSH into the instance.
    - Deploy a simple NodeJS application that returns "Hello, EC2!".
  - **Objective:** Understand EC2 instances and basic deployment.
  - **Resources:** [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/index.html)

#### Advanced
- **Task:** Create a Lambda function.
  - **Requirements:**
    - Create a Lambda function that triggers on an S3 event (e.g., file upload).
    - The function should log the event details.
  - **Objective:** Learn about serverless functions and event-driven architecture.
  - **Resources:** [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/index.html)

## Chapter 7: Introduction to Serverless Framework

### Learning Resources
- [Serverless Framework Documentation](https://www.serverless.com/framework/docs)

### Exercises

#### Beginner
- **Task:** Set up a Serverless project.
  - **Requirements:**
    - Deploy a simple Lambda function that returns "Hello, World!".
  - **Objective:** Understand the basics of the Serverless Framework.
  - **Resources:** [Serverless Getting Started](https://www.serverless.com/framework/docs/getting-started/)

#### Intermediate
- **Task:** Deploy a REST API with Serverless.
  - **Requirements:**
    - Create multiple endpoints using API Gateway and Lambda functions.
    - Implement CRUD operations for a `Product` resource.
  - **Objective:** Learn about API Gateway integration and multi-endpoint APIs.
  - **Resources:** [Serverless API Gateway](https://www.serverless.com/framework/docs/providers/aws/events/apigateway/)

#### Advanced
- **Task:** Implement a Serverless application with DynamoDB.
  - **Requirements:**
    - Integrate DynamoDB for data storage.
    - Implement CRUD operations for a `Customer` resource.
  - **Objective:** Understand integration with AWS services and advanced configurations.
  - **Resources:** [Serverless DynamoDB](https://www.serverless.com/framework/docs/providers/aws/guide/resources/)

