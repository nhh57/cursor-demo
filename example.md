Before diving into the best practices, please note that you may need to adapt the globs depending on your specific project structure.

---
name: spring-boot-best-practices.mdc
description: Best practices for Spring Boot applications
globs: **/*.{java}
---

- Use `@SpringBootApplication` on the main class
- Externalize configuration using `application.properties` or `application.yml`
- Implement proper exception handling with `@ControllerAdvice`
- Use `@Transactional` for database transactions
- Enable Spring Boot Actuator for monitoring and management

---
name: spring-data-jpa-best-practices.mdc
description: Best practices for using Spring Data JPA
globs: **/*.{java}
---

- Use Spring Data repositories for CRUD operations
- Implement custom queries using `@Query` annotation
- Use `@Entity` and `@Table` for proper entity mapping
- Implement lazy loading for associations
- Use `@Transactional` for managing transactions

---
name: spring-security-best-practices.mdc
description: Best practices for implementing Spring Security
globs: **/*.{java}
---

- Use method-level security with `@PreAuthorize` and `@PostAuthorize`
- Implement proper password encoding with `BCryptPasswordEncoder`
- Use JWT for stateless authentication
- Implement CSRF protection
- Use role-based access control with `@Secured` or `@RolesAllowed`

---
name: spring-boot-validation-best-practices.mdc
description: Best practices for input validation in Spring Boot
globs: **/*.{java}
---

- Use `@Valid` annotation for object validation
- Implement custom validators using `@Constraint` and `ConstraintValidator`
- Use `@RequestBody` with `@Valid` for request body validation
- Implement proper error handling for validation exceptions
- Use `@Size`, `@NotNull`, and other built-in constraints

---
name: spring-boot-testing-best-practices.mdc
description: Best practices for testing Spring Boot applications
globs: **/*.{java}
---

- Use `@SpringBootTest` for integration tests
- Implement unit tests with `@Test` and Mockito for mocking
- Use `@WebMvcTest` for controller tests
- Implement database tests with TestContainers
- Use `@DataJpaTest` for repository tests

---
name: springdoc-openapi-best-practices.mdc
description: Best practices for using SpringDoc OpenAPI
globs: **/*.{java}
---

- Use `@Operation` and `@Parameter` for detailed API documentation
- Implement proper security scheme documentation
- Use `@ApiResponse` for documenting possible responses
- Enable SpringDoc UI for interactive API exploration
- Use `@Schema` for documenting DTOs and entities

---
name: hibernate-orm-best-practices.mdc
description: Best practices for using Hibernate ORM
globs: **/*.{java}
---

- Use proper mapping annotations like `@JoinColumn` and `@OneToMany`
- Implement eager and lazy loading strategies
- Use `@Fetch` for optimizing data retrieval
- Implement proper caching strategies
- Use `@Formula` for calculated fields

---
name: hikaricp-best-practices.mdc
description: Best practices for using HikariCP
globs: **/*.{java}
---

- Configure connection pool settings in `application.properties`
- Use `HikariDataSource` for database connections
- Monitor and tune pool size based on application needs
- Implement proper connection validation
- Use `leakDetectionThreshold` to detect connection leaks

---
name: slf4j-logback-best-practices.mdc
description: Best practices for logging with SLF4J and Logback
globs: **/*.{java,xml}
---

- Use SLF4J API for logging
- Configure Logback in `logback.xml`
- Implement proper log levels (DEBUG, INFO, WARN, ERROR)
- Use MDC for adding context to logs
- Implement asynchronous logging for performance

---
name: spring-devtools-best-practices.mdc
description: Best practices for using Spring DevTools
globs: **/*.{java,properties}
---

- Enable DevTools in `application.properties`
- Use live reload for automatic application restarts
- Implement remote debugging with DevTools
- Use property defaults for development-specific configurations
- Implement proper caching strategies during development

---
name: checkstyle-best-practices.mdc
description: Best practices for using CheckStyle
globs: **/*.{java,xml}
---

- Configure CheckStyle in `checkstyle.xml`
- Implement consistent coding style across the project
- Use severity levels to prioritize code issues
- Integrate CheckStyle with your build tool
- Regularly review and update CheckStyle rules

---
name: pmd-best-practices.mdc
description: Best practices for using PMD
globs: **/*.{java,xml}
---

- Configure PMD in `pmd.xml`
- Use PMD to detect common coding issues and potential bugs
- Implement custom rules for project-specific requirements
- Integrate PMD with your build tool
- Regularly review and update PMD rules

---
name: sonarqube-best-practices.mdc
description: Best practices for using SonarQube
globs: **/*.{java,properties}
---

- Set up SonarQube server and integrate with your CI/CD pipeline
- Configure SonarQube properties in `sonar-project.properties`
- Use SonarQube to analyze code quality and security
- Implement SonarQube quality gates for automated checks
- Regularly review and address SonarQube findings