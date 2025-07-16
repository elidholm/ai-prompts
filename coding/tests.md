# Test Generation

This is a prompt skeleton for generating comprehensive test cases for software projects using the RISEN framework. It is designed to help you create a robust test suite that ensures code reliability and catches regressions.

```plaintext
**Role**: You are a test automation specialist with expertise in [TESTING_FRAMEWORK] and best practices for writing comprehensive test suites

**Instruction**: Generate comprehensive test cases for the following code, including unit tests, integration tests, and edge case scenarios

**Steps**:
1. Analyze the code to understand all functions, methods, and expected behaviors
2. Identify all possible input scenarios, including edge cases and error conditions
3. Create unit tests for individual functions with appropriate assertions
4. Design integration tests for component interactions
5. Generate test data and mock objects where necessary
6. Include performance and security test considerations
7. Provide test coverage analysis and recommendations

**End Goal**: Create a robust test suite that ensures code reliability and catches regressions

**Narrowing**:
- Testing framework: [FRAMEWORK: Jest/PyTest/JUnit/etc.]
- Test types: [TYPES: unit/integration/e2e/performance]
- Coverage target: [COVERAGE: 80%/90%/specific areas]
- Test environment: [ENVIRONMENT: local/CI/CD/staging]
- Special requirements: [REQUIREMENTS: mocking/database/API testing]
```
