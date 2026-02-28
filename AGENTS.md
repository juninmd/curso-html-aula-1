```markdown
# AGENTS.md Guidelines

These guidelines outline the specific practices and principles for developing AI coding agents within this repository. Adherence to these principles is crucial for maintaining a robust, maintainable, and scalable codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Core Functionality Reuse:** Each agent should have a clearly defined, single responsibility.  Avoid duplicating logic across different agents.
*   **Component Patterns:**  Favor component-based design where possible.  Components should have specific, well-defined interfaces and implementations.
*   **Abstraction:** Create abstract classes or interfaces to represent common agent behavior, reducing code duplication.
*   **Standardized Functions:**  Define standard functions for common tasks across multiple agents.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:** Strive for the shortest possible code that achieves the intended functionality.
*   **Readability:** Prioritize clear and understandable code. Use meaningful variable and function names.
*   **Avoid Complexity:**  Keep algorithms and data structures as simple as possible. Resist premature optimization.
*   **Modular Design:** Break down complex tasks into smaller, self-contained modules.

## 3. SOLID Principles

*   **Single Responsibility:** Each class/module should have a single, well-defined purpose.
*   **Open/Closed Principle:**  The agent's interface should be open for extension but closed for modification.  New features shouldn’t require rewriting existing code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients shouldn't be forced to bound to methods they don't use.
*   **Dependency Inversion Principle:**  High-level modules (agents) should not depend on low-level modules (implementation details).

## 4. YAGNI (You Aren't Gonna Need It)

*   **Future-Proofing:** Only implement functionality that is currently required.  Avoid adding features that are not yet needed.
*   **Refactoring:** Refactor code only when it is genuinely necessary to improve its maintainability and performance.  Don't refactor just because it's "good practice."

## 5. Development Workflow & Coding Standards

*   **Unit Testing:** All code must be thoroughly tested with unit tests.
*   **Test Coverage:** Aim for 80% test coverage.  Implement comprehensive test suites covering all critical functionality.
*   **Code Reviews:** All code changes must be reviewed by at least two other developers.
*   **Documentation:**  Provide clear and concise documentation for all functions, classes, and modules.
*   **Version Control:**  Use Git for version control.  Commit frequently with meaningful messages.

## 6. File Size & Structure

*   **Maximum Code Length:** Each file should not exceed 180 lines of code.
*   **Modular Structure:**  Organize files into logical modules with well-defined interfaces.
*   **Naming Conventions:**  Use consistent naming conventions for variables, functions, and classes.
*   **Comments:**  Provide clear and concise comments where necessary to explain complex logic.

## 7.  Specific Requirements (Example - Adapt as Needed)

*   **Agent Initialization:** All agents should have a clear initialization sequence.
*   **Data Storage:**  Define a consistent mechanism for data storage.
*   **API Design:**  All agent APIs should be well-documented and easy to use.
*   **Error Handling:** Implement robust error handling with informative error messages.

## 8.  Tools & Technologies (Examples – Adapt to Project)

*   **IDE:**  Use an IDE (e.g., VS Code, IntelliJ) with code formatting and linting.
*   **Linters:**  Implement a linter (e.g., ESLint) to enforce coding standards.
*   **Static Analysis:** Utilize static analysis tools (e.g., SonarQube) to detect potential issues.

## 9.  Reporting & Monitoring

*   **Progress Tracking:**  Use a task management system (e.g., Jira) to track progress on tasks.
*   **Bug Reporting:**  Establish a clear process for reporting and tracking bugs.
*   **Code Quality Metrics:**  Monitor code quality metrics (e.g., Cyclomatic Complexity) to identify areas for improvement.

## 10.  Governance

*   **Code Ownership:** Assign ownership of specific modules/agents to individuals or teams.
*   **Design Reviews:** Conduct regular design reviews to ensure architectural consistency.
*   **Documentation Updates:**  Keep documentation up to date with changes to the code.

```