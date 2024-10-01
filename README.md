# Project Title: Trello REST API Testing Project

## Project Description:

The Trello REST API Testing Project focuses on automating the testing of Trello's API endpoints to ensure their functionality, reliability, and performance. This project includes building a comprehensive suite of API test cases that cover core functionalities such as creating, updating, and deleting boards, lists, and cards within Trello, using automated tools like Postman, Newman, and Jenkins.

## The project implements the following key components:

### API Requests:
API requests were constructed for Trello's key operations, such as managing boards, lists, and cards. The requests utilized Trello's RESTful API and were configured to test both standard functionality and edge cases, ensuring robust coverage.

### Automated Testing in Postman:
Test cases were automated using Postman, leveraging its capabilities to run collections of API requests and validate responses. Test scripts were written in JavaScript to perform detailed checks such as status code validation, response body structure verification, and ensuring correct error handling.

### Newman Integration:
Postman collections were executed using Newman, a command-line tool that enables API tests to run in Continuous Integration (CI) environments. This allowed for the automation of API test runs as part of the CI/CD pipeline.

### CI with Jenkins:
Jenkins was integrated to automate the test execution process. Jenkins jobs were configured to trigger the execution of Newman test scripts, running API tests on each code commit or scheduled time. Test reports were generated and displayed within Jenkins, allowing for continuous monitoring and feedback on the API's performance.

### API Authentication:
API authentication was implemented using OAuth 2.0 to ensure secure access to the Trello API. Tests covered various authentication scenarios, including token generation, expiration, and renewal, validating that all authentication mechanisms work as expected.

This project demonstrates the ability to automate API testing, integrate with CI tools, and ensure secure and reliable API interactions using modern testing frameworks.
