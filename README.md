# IFB-Online-Challenge
- Selenium Data Driven Framework
IFB-Online-Challenge is a data-driven testing framework that uses Selenium to automate web-based applications. It is designed to simplify the process of creating and executing automated tests by separating test data from test logic.

Features
Data-driven approach: Test data is stored separately from the test scripts, allowing for easy modification and reuse of test cases.
Modularity: The framework is built using a modular approach, making it easy to add or remove functionality as needed.
Reporting: The framework generates detailed test reports in HTML format, making it easy to track test results and identify issues.
Cross-browser compatibility: The framework supports testing on multiple browsers, including Chrome, Firefox, and Safari.
Parallel testing: The framework supports parallel execution of test cases, reducing the overall test execution time

Requirements
Java 8 or higher
Maven 3.x
Selenium WebDriver
TestNG
IntelliJ

Installations
Clone this repository to your local machine.
Install the required dependencies by running mvn clean install in the root directory
OR
Import project as an existing Maven project in IntelliJ, File > Import > Maven > Existing Maven Projects > Next >
a. Browse to if-online-challenge
b. Ensure pom.xml is found
c. Finish.

Update the config.properties file to configure the test settings such as the browser type and test URL.
Write your test cases in the  src/test/java  directory using TestNG annotation and POM design pattern.

Contribution
Contributions are welcome! Please feel free to open a pull request or submit an issue if you find any bugs or have any suggestions for improvement.
