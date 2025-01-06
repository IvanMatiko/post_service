# Post Service

## Overview
Post Service is a backend application for managing posts within a system. It provides comprehensive APIs for creating, reading, updating, and deleting posts, along with managing associated metadata such as tags, categories, and authors.

## Features
- **Post Management:** Create, retrieve, update, and delete posts.
- **Tag and Category Association:** Link posts with relevant tags and categories.
- **Author Integration:** Manage authors and associate them with posts.
- **Pagination and Filtering:** Efficiently retrieve posts with support for pagination and advanced filters.
- **Swagger Documentation:** Automatically generated API documentation for developers.

## Getting Started

### Prerequisites
- Java 17
- Docker (optional for containerized deployment)
- Gradle

### Steps
1. Clone the repository:
   git clone https://github.com/IvanMatiko/post_service.git
   cd post_service
   
 2. Build the project:
   ./gradlew build

 3. Run the application:
    ./gradlew bootRun
 
 4. Optional (Build and run with Docker):
    docker build -t post-service .
    docker run -p 8080:8080 post-service


   # API Endpoints
GET /posts: Retrieve a list of posts.

POST /posts: Create a new post.

GET /posts/{id}: Retrieve details of a specific post.

PUT /posts/{id}: Update an existing post.

DELETE /posts/{id}: Delete a post by ID.

For detailed API specifications, refer to the Swagger documentation.

# Technologies Used
Java: Primary programming language.

Spring Boot: Framework for building the backend service.

Postgres: DataBase.

Redis: cache and message's broker.

Gradle: Build tool for project automation.

Swagger: API documentation tool.

Docker: For building and deploying the service in a containerized environment.
   
    

 
