# Test Plan — SauceDemo

## 1. Objective

The objective of this test plan is to define the testing strategy, scope, and approach for the SauceDemo QA Project. The goal is to evaluate whether the application functions as expected and identify potential defects through different testing methodologies.

Testing will focus on the core functionalities of the SauceDemo application, including user authentication, product browsing, shopping cart management, and checkout processes. The project includes manual testing and planned test automation using Cypress to evaluate the application's behavior and achieve appropriate test coverage.

## 2. Scope

The scope of this test plan includes the following areas:

- User Authentication: Testing login functionality with valid and invalid credentials, as well as logout behavior.
- Product Browsing: Verifying product listings and sorting functionality.
- Shopping Cart Management: Testing the addition and removal of products from the shopping cart.
- Checkout Process: Validating the checkout flow, including customer information fields, input validation, and order completion.
- Test Automation: Developing Cypress automated tests for critical functionalities and regression testing.

## 3. Out of Scope

The following areas are considered out of scope for this test plan:

- Performance Testing: Formal load and stress testing will not be performed. Performance observations made during exploratory testing may be documented separately.
- Security Testing: Security vulnerability assessments and penetration testing are excluded from this project.
- Cross-Browser and Device Testing: Testing across multiple browsers and devices is excluded. Testing will be limited to the selected test environment.
- External Integration Testing: Testing integrations between SauceDemo and external systems or APIs is excluded from this test plan.

## 4. Test Environment

The test environment for the SauceDemo QA Project will consist of the following components:

- **Application**: SauceDemo (https://www.saucedemo.com/)
- **Operating System**: Windows 11
- **Browser**: Google Chrome
- **Test Automation Framework**: Cypress
- **Testing Types**: Manual exploratory testing and automated functional testing
- **Version Control**: Git and GitHub

## 5. Testing Types

The following testing types will be employed in the SauceDemo QA Project:

- **Exploratory Testing**: Manually exploring the application's login, product browsing, shopping cart management, and checkout functionalities to identify potential defects.
- **Functional Testing**: Verifying that the application's features behave as expected, including login, product sorting, shopping cart operations, and checkout validation.
- **Automated Testing**: Developing Cypress automated tests to cover critical functionalities, such as login, product browsing, shopping cart management, and checkout. These tests will support regression testing as the project evolves.
