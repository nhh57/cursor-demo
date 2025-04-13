# Technical Context

## Technology Stack
- Backend: Spring Boot, Spring MVC, Spring Security
- Database: Spring Data JPA, Hibernate ORM
- Connection Pool: HikariCP
- Validation: Jakarta Bean Validation (Hibernate Validator)
- API Documentation: SpringDoc OpenAPI
- Logging: SLF4J with Logback
- Testing: JUnit 5, Mockito, TestContainers
- Code Quality: SonarQube, CheckStyle, PMD

## Development Environment
- Java 17 or higher
- Maven for dependency management
- Spring Boot DevTools for rapid development
- Git for version control
- IDE with Spring support (IntelliJ IDEA or Eclipse STS)

## Build System
- Maven for build management
- Automated builds in CI/CD pipeline
- SonarQube scan integrated in build process
- CheckStyle and PMD checks during build

## Testing Framework
- Unit testing with JUnit 5 and Mockito
- Integration testing with @SpringBootTest
- Controller testing with @WebMvcTest
- Repository testing with @DataJpaTest
- Database testing with TestContainers

## Dependencies
- Spring Boot Starter Web
- Spring Boot Starter Data JPA
- Spring Boot Starter Security
- Spring Boot Starter Validation
- Spring Boot Starter Actuator
- SpringDoc OpenAPI
- HikariCP
- Logback

## APIs and External Services
- RESTful API endpoints documented with OpenAPI
- Spring Boot Actuator endpoints for monitoring
- Database connection (configurable)

## Deployment
- Dockerized deployment
- Support for Spring profiles for environment-specific configuration
- Health checks via Spring Boot Actuator

## Technical Constraints
- Java 17+ required
- PostgreSQL or compatible database
- CORS configuration for API access from web clients

## Tools and Utilities
- SonarQube for code quality analysis
- CheckStyle for code style enforcement
- PMD for code analysis
- Logback for logging configuration
- Spring Boot Actuator for monitoring 