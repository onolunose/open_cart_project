# E-commerce Automation Testing Framework
About The Project 
Welcome to the Open Cart E-commerce Automation Framework! This project aims to automate user interactions on the Open Cart e-commerce platform. We are using Selenium WebDriver for browser automation, Python as the binding language,and Pytest for test management. The framework follows the Page Object Model (POM).

Why This Project is Useful 
Maintainability: By following the Page Object Model, the code is organized and easy to update.
Scalability: The framework can be easily extended to add more tests as the e-commerce platform grows.
Reusability: Common functions and methods can be reused across different test cases.
Reporting: Generates detailed test reports to quickly identify and fix any issues.

Getting Started 

Prerequisites: Install the following Packages/plugins:
Python 3.x
Selenium WebDriver
Pytest (5.4.3 Preferred)
Webdriver-manager
Pytest-html
Pytest-xdist
Openpyxl
Allure-pytest

Installation
1. Clone the Repository
2. Install Required Packages/plugins
   Navigate to the project directory and install the required packages from the `prerequisites.txt` file.
3. Running Tests
Execute the following command to run your tests:
pytest -n <NUM_OF_CORES> --html=reports/report.html --self-contained-html
4. Generating Reports
Generate Allure reports

Getting Help 
If you encounter any issues or have questions about the project, please open an issue on GitHub.



