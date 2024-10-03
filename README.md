# wkassignment
wk assignment file

**Overview**
This project contains a comprehensive test suite for a To-Do application, focusing on validating the core functionalities of adding, deleting, 
and updating to-do items. 
The tests are developed using Java, Selenium WebDriver, and Cucumber for behavior-driven development (BDD).

**Technologies Used**
**Java:** The primary programming language for implementing test cases.
**Selenium WebDriver:** Used for automating web browser interaction.
**Cucumber:** For writing tests in a readable format using Gherkin syntax.
**TestNG:** For managing test execution.
**Maven:** For project management and dependency management.
Allure: For generating test reports.

**Testing Frameworks and Patterns**
BDD Approach with Cucumber
We follow a Behavior-Driven Development (BDD) approach to ensure that the tests are readable and understandable for all stakeholders.

**Page Object Model (POM)**
The tests are structured using the Page Object Model (POM) design pattern. 
This helps to maintain a clear separation between test code and UI interaction logic, enhancing maintainability and reducing code duplication.

**Test Organization**
**Feature Files:** Located in the /src/test/resources/features directory. Each feature file contains scenarios written in Gherkin syntax.
**Step Definitions:** Located in the /src/test/java/stepDefinitions directory. This is where the Cucumber steps are implemented, linking the feature files with the code.
**Page Objects:** Located in the /src/main/java/pageObjects directory. This contains classes representing the pages of the application, encapsulating the logic for interacting with the UI elements.

**Getting Started
Prerequisites**
Java Development Kit (JDK) 8 or higher
Apache Maven
An IDE (Eclipse, IntelliJ IDEA, etc.)
A web browser (Chrome) and the corresponding WebDriver

**Positive Test Cases:**
1. Add a valid to-do item
2. Add multiple to-do items
3. Mark a single to-do as completed
4. Marking multiple to do items as completed


**Negative Test Cases:**
1. Try adding item with no text
2. Try adding item with one character
3. Edit a to-do item with an invalid input
4. Edit a to-do item to be empty
5. Marking an already deleted item
6. Marking an empty item


**Author -
Gaurav Patil.**
