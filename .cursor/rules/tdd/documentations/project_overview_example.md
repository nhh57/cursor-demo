# Project Overview

## Project Structure
The project follows Layer Architecture principles with clear separation of concerns:

```
project/
   ├── src/main/java/       - Main source code
   │   ├── controller/      - Handles HTTP requests and responses
   │   ├── service/         - Contains business logic
   │   ├── repository/      - Manages data access and persistence
   ├── src/main/resources/ - Configuration files and resources
   └── src/test/           - Unit and integration tests
       ├── controller/      - Tests for controllers
       ├── service/         - Tests for services
       └── repository/      - Tests for repositories
```