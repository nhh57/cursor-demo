# Active Context

## Current Focus
Establishing coding standards and best practices for a Spring Boot application with rule files that enforce these standards through an AI assistant.

## Recent Changes
- Created core code quality standards that apply to all code
- Defined Spring Boot application structure standards
- Established standards for Spring Data JPA usage
- Created security implementation standards for Spring Security
- Defined validation patterns for robust input validation
- Established testing practices for comprehensive test coverage
- Defined API documentation standards with SpringDoc OpenAPI
- Created logging standards using SLF4J and Logback

## Next Steps
- Implement example application following established standards
- Create additional specialized standards for error handling
- Develop standards for caching strategies
- Create standards for microservice communication patterns
- Establish monitoring and observability standards

## Active Decisions
- Constructor injection: Preferred over field injection for better testability
- Package by feature: Organizing code by feature rather than by layer
- Consistent exception handling: Centralized with @ControllerAdvice
- Documentation-first approach: All APIs must be documented with OpenAPI
- Test-driven development: Tests should be written before implementation

## Current Challenges
- Balancing prescriptive standards with developer flexibility
- Ensuring standards are easy to understand and follow
- Implementing practical examples that demonstrate standards
- Integrating standards checking into the development workflow

## Key Insights
- Code quality standards are most effective when enforced automatically
- Spring Boot best practices should focus on maintainability and security
- Well-documented APIs significantly improve developer experience
- Consistent logging patterns are essential for troubleshooting
- Constructor injection makes dependencies explicit and improves testability

## Implementation Preferences
- Using Cursor rules to enforce coding standards
- Implementing standards as auto-attached rules by file pattern
- Including both good and bad examples for clearer understanding
- Creating comprehensive standards documents with concise rules

## Ongoing Experiments
- Testing effectiveness of AI-enforced coding standards
- Evaluating different rule organization approaches
- Exploring automated code quality checking tools integration

## Important Notes
- Standards should evolve based on project needs and feedback
- Rules should be specific enough to be useful but not overly restrictive
- Examples are crucial for understanding how to apply standards correctly 