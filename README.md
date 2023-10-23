
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

### Dependencies

- **cors (^2.8.5):** CORS (Cross-Origin Resource Sharing) middleware for Express, enabling secure cross-origin requests for your application.

- **dotenv (^16.3.1):** The dotenv library is used for managing environment variables and application configuration.

- **express (^4.18.2):** Express is a widely used Node.js web application framework, serving as the core of your application's server and routing.

- **mongoose (^7.5.0):** Mongoose is an Object-Data Modeling (ODM) library for MongoDB and provides an elegant solution for interacting with MongoDB databases.

- **mongoose-to-swagger (^1.5.1):** A library that helps generate Swagger documentation from Mongoose schemas, facilitating API documentation.

- **mongoose-unique-validator (^4.0.0):** A Mongoose plugin for adding validation to enforce unique values for specified fields in a Mongoose schema.

- **nodemon (^3.0.1):** Nodemon is a development dependency used to monitor changes in your source code files and automatically restart your Node.js application.

- **swagger-ui-express (^5.0.0):** Middleware for Express that provides Swagger UI for interacting with your API documentation.

- **winston (^3.10.0):** Winston is a widely used logging library for Node.js applications, enabling efficient logging of events and errors.

- **winston-daily-rotate-file (^4.7.1):** A transport module for Winston that allows log rotation on a daily basis.

- **winston-mongodb (^5.1.1):** A transport module for Winston that supports logging to a MongoDB database.

### DevDependencies

- **cross-env (^7.0.3):** A development dependency used for setting environment variables consistently across different platforms.

- **jest (^29.7.0):** Jest is a popular JavaScript testing framework used for writing and running unit tests.

- **supertest (^6.3.3):** Supertest is a library used with testing frameworks like Jest for making HTTP assertions and testing API endpoints.

Feel free to refer to this readme for an overview of the Products-App and the key components of its architecture.
