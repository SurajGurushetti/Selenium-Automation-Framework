# Selenium Automation Framework

A Selenium WebDriver automation testing framework built with **Java** to
automate key functionalities of the **Demo Web Shop** application. The
project is designed to support reusable, maintainable, and data-driven
test automation.

## Project Overview

This framework focuses on automating important e-commerce workflows,
such as:

-   User login
-   Product search and selection
-   Add to cart
-   Checkout flow

The framework follows the **Page Object Model (POM)** design pattern to
keep page locators and actions separate from test scripts.

## Tech Stack

  Technology           Purpose
  -------------------- ----------------------------------------------------
  Java                 Programming language
  Selenium WebDriver   Browser automation
  TestNG               Test execution and test management
  Maven                Dependency and build management
  Apache POI           Reading test data from Excel (data-driven testing)
  Jenkins              Continuous integration and automated execution
  Extent Reports       Test execution reporting

## Framework Design

The project uses the Page Object Model (POM):

-   **Page classes:** Store web element locators and page-level actions.
-   **Test classes:** Contain test scenarios and assertions.
-   **TestNG:** Organizes and executes test cases.
-   **Excel test data:** Supports data-driven test execution through
    Apache POI.
-   **Reports:** Extent Reports can be used to generate execution
    reports.

## Prerequisites

Install the following before running the project:

1.  Java JDK (17 or a version compatible with the project)
2.  Maven
3.  Eclipse IDE or another Java IDE
4.  Google Chrome browser
5.  Git

Check your installations:

``` bash
java -version
mvn -version
git --version
```

## Clone the Repository

``` bash
git clone https://github.com/SurajGurushetti/Selenium-Automation-Framework.git
cd Selenium-Automation-Framework
```

Open the project in Eclipse as an existing Maven project, or open it in
your preferred IDE.

## Run the Tests

From the directory containing the project's `pom.xml`, run:

``` bash
mvn clean test
```

To run the suite through TestNG, use the project's configured
`testng.xml` file if one is present:

``` bash
mvn test
```

Make sure the browser and driver configuration required by the project
are available before execution.

## Test Scenarios

The framework is intended to cover these e-commerce scenarios:

  Module            Example test scenario
  ----------------- -------------------------------------------------
  Login             Verify login with valid and invalid credentials
  Product           Search for a product and verify the result
  Product details   Open a product and verify its details
  Shopping cart     Add a product and verify it appears in the cart
  Checkout          Validate the checkout workflow

## Key Features

-   Selenium WebDriver automation using Java
-   Page Object Model for reusable page components
-   TestNG-based test organization and execution
-   Data-driven testing using Excel and Apache POI
-   Maven-based dependency management
-   Jenkins integration for CI execution
-   Extent Reports for test execution reporting

## Notes

-   Update browser, URL, and test-data configuration according to your
    local environment.
-   Do not commit real usernames, passwords, access tokens, or other
    secrets. Keep sensitive values in local configuration or environment
    variables.
-   The exact test suite and commands depend on the configuration files
    included in the repository.

## Author

**Suraj Gurushetti**

-   GitHub: [SurajGurushetti](https://github.com/SurajGurushetti)
-   Repository: [Selenium Automation
    Framework](https://github.com/SurajGurushetti/Selenium-Automation-Framework)

------------------------------------------------------------------------

If you find this project useful, feel free to star the repository.
