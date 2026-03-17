# Postman-API-TestingP-Portfolio
Automated API Testing project using Postman and JavaScript for Restful-Booker API.

# 🚀 API Testing Portfolio: Hotel Booking System

## 📌 Project Overview
This project contains automated tests for the **Restful-Booker API**. 
The goal was to demonstrate end-to-end (E2E) API testing, including authentication, data integrity, and request chaining.

## 🛠️ Tech Stack
* **Tool:** Postman
* **Scripting:** JavaScript
* **Environment:** Postman Environments for dynamic variables
* **API Documentation:** [Restful-Booker](https://restful-booker.herokuapp.com/)

## 🛠️ Challenges & Solutions
  
Challenge: The API returns 404 Not Found instead of 403 Forbidden during a DELETE request with an invalid token if the ID doesn't exist.

Solution: I implemented conditional testing logic using JavaScript to handle both status codes, ensuring the test suite remains robust and doesn't fail due to API design specifics.

## ⚙️ Prerequisites

Postman Desktop Agent
Internet connection (access to https://restful-booker.herokuapp.com)

## 🧪 Scenarios Covered
1. **Auth:** Generating a security token for restricted access.
2. **Create Booking (POST):** Dynamic creation of booking data with automated ID extraction.
3. **Get Details (GET):** Validation of data integrity and data types (numbers, booleans).
4. **Delete (DELETE):** Secure deletion using Authorization tokens.

## 📊 How to Run
1. Download the `.json` files from this repo.
2. Import them into your Postman.
3. Select the `Restful Booker API` environment.
4. Run the **Collection Runner**.

## ✅ Test Results
* Status Code Validations
* Response Time Checks (< 800ms)
* JSON Schema & Data Integrity Checks

## Test Results
<img width="1438" height="1133" alt="results" src="https://github.com/user-attachments/assets/df9bc6db-9f01-4a1e-80be-920572e44a06" />
