
# Products-App Readme

## Overview

**Products-App** is a Node.js and MongoDB-based application designed for efficiently managing products and users. It provides functionality for user creation and product purchases.

## Application Architecture

### Model Directory
Within the "model" directory, you'll find definitions for two core entities: "Products" and "Users." These models serve as the foundation for data representation within our application.

### Controllers Directory
The "controllers" directory contains individual controller files for each entity - "Products" and "Users." These controllers are responsible for executing CRUD operations specific to their respective entities, ensuring seamless data management within the app.

### Routers Directory
In the "routers" directory, you'll discover router files dedicated to "Products" and "Users" entities. These routers act as entry points to trigger CRUD actions performed by the controllers. They define the routes and actions that can be performed within the application.

### index.js
In the "index.js" file, we centralize and configure all the necessary middleware components for the proper functioning of our application. These middleware components encompass authentication, validation, error handling, and more.

### server.js
The "server.js" file serves as the entry point for launching the application. It's responsible for setting up the server, handling incoming requests, and directing them to the appropriate router and controller for processing.

### logger.js
The "logger.js" file plays a pivotal role in our application's logging mechanism. It captures and records essential information, events, and errors, aiding in effective monitoring and troubleshooting.

## Summary

In summary, our application follows SOA principles, leveraging Node.js and MongoDB. With a focus on the "model," "controllers," and "routers" directories, along with key configurations in "index.js," "server.js," and "logger.js," we ensure that our app runs smoothly. It offers CRUD functionality for both "Products" and "Users" entities, maintaining a robust and organized structure. Additionally, we use Swagger for API documentation and management (please refer to the "swagger.js" file for more information).

## Dependencies

Here's a list of dependencies used in our application:

- **dotenv (^0.0.2)**: The `dotenv` library is used for managing environment variables and application configuration. It allows you to load settings, such as API keys, database connection strings, and other environment-specific values from a `.env` file into your application. These variables can be accessed throughout your code, enabling you to securely store and manage sensitive data without hardcoding it directly into your source files.

- **express (^4.18.2)**: Express is a widely used Node.js web application framework. It is the core of your application's server and routing. You can create routes, handle requests, and define middleware using Express to build the HTTP endpoints for your API.

- **express-validator (^7.0.1)**: Express-validator is a middleware for Express that helps validate and sanitize request data. It's essential for ensuring that data submitted to your application through API requests is valid and safe, preventing common security vulnerabilities like SQL injection or cross-site scripting.

- **mysql (^2.18.1)**: The "mysql" dependency is a Node.js MySQL driver, indicating that your application might use a MySQL database to store and retrieve data. It's crucial for interacting with your database and executing SQL queries for CRUD operations on your data.

- **typeorm (^0.3.17)**: TypeORM is an Object-Relational Mapping (ORM) library for TypeScript and JavaScript, which allows you to work with databases using TypeScript classes and entities. It's often used for defining your data models and handling database operations. This suggests that you might use TypeORM to manage your "Products" and "Users" entities in a more object-oriented way.

- **nodemon (^3.0.1)**: Nodemon is a development dependency used to monitor changes in your source code files. It automatically restarts your Node.js application whenever you make changes. This is especially helpful during development, as it saves you the effort of manually restarting the server every time you modify your code.

Feel free to refer to this readme for an overview of the Products-App and the key components of its architecture.
