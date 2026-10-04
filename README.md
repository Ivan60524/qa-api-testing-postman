# API Testing Automation - Postman & Reqres

## 📌 Project Overview
This project contains an automated API testing collection developed to validate backend functionality using **Postman** and JavaScript test assertions. It covers the complete **CRUD** (Create, Read, Update, Delete) lifecycle against the Reqres test environment.

## 🛠️ Tech Stack & Tools
* **Tool:** Postman
* **Language:** JavaScript (for test scripts)
* **API Target:** Reqres (https://reqres.in)
* **Environment Management:** Collection Variables (`base_url`)

## 🧪 Test Scenarios Implemented
1. **GET (Read):** Retrieves a list of users, validates `200 OK` status code, evaluates response time performance (< 500ms), and parses JSON payloads.
2. **POST (Create):** Registers a new user profile (`Ivan Suarez`, `QA Automation Engineer`) and asserts the `201 Created` status code.
3. **PUT (Update):** Modifies existing user data and verifies updated parameters via automated JSON assertions.
4. **DELETE (Delete):** Removes a user resource and validates the `204 No Content` status code.

## 🚀 How to Run This Project
1. Download the `Reqres_API_Testing.postman_collection.json` file from this repository.
2. Open **Postman**, click on **Import**, and select the downloaded file.
3. Run the collection individually or via the Postman Collection Runner.
