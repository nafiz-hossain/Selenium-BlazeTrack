# Selenium Automation Framework Terms and Concepts

## PageObjects
Page Object Model (POM) is a design pattern used in Selenium automation. It suggests creating an object repository for web UI elements on a web page. These objects represent various components on the page and provide methods to interact with them.

**Example**: 
Let's say you have a login page with username and password fields and a login button. In PageObjects, you would create methods like `enterUsername`, `enterPassword`, and `clickLoginButton` to interact with these elements.

## ActionDriver
ActionDriver is a component responsible for performing actions such as clicking buttons, typing in text fields, selecting options from dropdowns, etc., on web elements.

## Utility Component
Utility components contain reusable functions or methods that perform common tasks across the automation framework. These can include functions for handling waits, taking screenshots, logging, etc.

## Config com Folders
This likely refers to the configuration files and folders in your automation project. It could include configurations for different environments (like development, testing, production), logging configurations, and more.

## IndexPage
This could be a representation of the homepage or the starting point of your web application. It typically contains links or elements to navigate to other pages.

## Scroll
This refers to scrolling the web page, either vertically or horizontally, to bring certain elements into view.

## LoginPage
Represents the page where users input their credentials to log in to the application.

## Click
Action to simulate a mouse click on a web element, like a button or a link.

## util-screenShot
A utility method or class for capturing screenshots of the web page during test execution, useful for debugging or reporting.

## ExtentClass
This might refer to a class or component responsible for generating ExtentReports, which are detailed HTML reports of test execution results.

## POM.xml
This is the Project Object Model (POM) file in Maven, which manages the project's build, dependencies, and plugins.

## HomePage
The main page of the application where users land initially.

## ProductPage
A page where products are displayed or managed.

## Sendkeys
An action to simulate typing text into an input field on a web page.

## Select
Action to choose an option from a dropdown or select element.

## Log
Logging is a way to track events and actions during test execution, useful for debugging and analysis.

## extent-config.xml
Configuration file for ExtentReports, specifying settings like report format, destination, etc.

## log4j.xml
Configuration file for Log4j, a logging utility for Java, used to control logging behavior.

## TestData
Data used for testing, often stored separately from test code for easy maintenance and reuse.

## ScreenShot Configuration
Configuration settings related to capturing screenshots during test execution.

## Listeners
Components that listen to specific events during test execution and perform actions based on those events, such as logging, capturing screenshots, etc.

## config.properties
Properties file containing configuration settings for the automation framework.

## Drivers
WebDriver instances used to automate interactions with the web browser.

## AddtoCart
Action to add a product to the shopping cart.

## Waits
Selenium provides different types of waits to handle synchronization issues between the test script and the web application.

## DataProviders
Mechanism to supply test data to test methods, often used with TestNG.

## testng.xml
Configuration file for TestNG, specifying test suite, test cases, and other parameters.

## Logs
Output generated during test execution, containing information about test steps, errors, etc.

## OrderPage
A page where users can place orders for products.

## ExtentReports
A reporting library used to generate interactive and detailed HTML reports of test execution results.
