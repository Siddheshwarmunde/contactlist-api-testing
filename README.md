📌 Contact List API Testing Project
🔎 Project Overview

This project demonstrates end-to-end API testing of a Contact List REST application using Postman. The objective was to validate functionality, authentication, CRUD operations, response correctness, and data integrity across all available endpoints.

🎯 Objectives

Validate REST API functionality

Verify authentication & authorization

Test CRUD operations

Validate response status codes

Verify response data

Ensure data persistence

Identify defects

🛠 Tools & Technologies

Postman

REST APIs

JSON

Excel

GitHub

🧪 Testing Scope
👤 User Module

Create User

Get Profile

Update User

Login

Logout

📇 Contact Module

Add Contact

Get Contact List

Get Single Contact

Update Contact

Partial Update Contact

📋 Test Cases Executed
TC ID	Endpoint	Method	Scenario	Expected Status
TC01	/users	POST	Create user with valid data	201
TC02	/users/me	GET	Fetch logged-in user profile	200
TC03	/users/me	PATCH	Update user details	200
TC04	/users/login	POST	Login with valid credentials	200
TC05	/contacts	POST	Add new contact	201
TC06	/contacts	GET	Retrieve contacts list	200
TC07	/contacts/{id}	GET	Fetch single contact	200
TC08	/contacts/{id}	PUT	Update full contact	200
TC09	/contacts/{id}	PATCH	Partial update contact	200
TC10	/users/logout	POST	Logout user	200
✔ Validations Performed

Status code verification

Response body validation

Authentication validation

Endpoint verification

Data integrity validation

Error handling validation

🔐 Authentication Testing

Bearer token authentication was validated by dynamically capturing token values and using them across secured API endpoints.

📊 Execution Summary
Total Tests	Passed	Failed
10	10	0

Result: All APIs executed successfully with expected responses.

🐞 Defect Handling

Sample defects were documented to demonstrate bug reporting capability:

Duplicate data validation

Invalid input handling

Empty payload validation

🧠 Skills Demonstrated

API Testing

Test Case Design

Debugging API Failures

Authentication Testing

Response Validation

Data Verification

Structured Test Documentation

📁 Project Structure
Collection/
Environment/
Screenshots/
TestCases/
Reports/
README.md
▶ How To Run Tests

Import collection.json into Postman

Import environment file

Select environment

Run collection

🎓 Learning Outcome

This project demonstrates practical knowledge of API testing concepts and real-world testing workflow using industry-standard practices.

👤 Author

Siddheshwar Munde
