**OneCognizant Website Automation Project**
**Project Overview**
This project automates the validation of various functionalities on the OneCognizant website. The automation scripts are designed to:

Verify if the user account is logged in and the displayed information is correct.
Check the functionality of all headers and subheaders by clicking each one and printing the results in the console.
Navigate to the Ethics and Compliance page, validate the navigation, and verify that all links and headers on this page are functioning correctly by printing the title and reference links in the console.

**Tools and Technologies**
Selenium (Java): For browser automation.
Cucumber: For behavior-driven development (BDD) and writing test scenarios.
Extent Reports: For generating detailed test reports.
Maven: For project build and dependency management.
Page Object Model (POM): For maintaining clean and reusable code.
TestNG: For test execution and management.

**Test Scenarios**
1. Account Login Validation
Verify if the user is logged in.
Print the user information in the console.
2. Header and Subheader Validation
Click each header and subheader.
Print the results in the console.
3. Ethics and Compliance Page Validation
Navigate to the Ethics and Compliance page.
Verify the navigation and print the title and reference links of each page in the console.

**Reporting**
The test results are generated using Extent Reports.
Reports can be found in the target/reports directory after test execution.

**Contributing**
Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.
