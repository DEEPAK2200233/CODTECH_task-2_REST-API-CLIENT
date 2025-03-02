# CODTECH_task-2_REST-API-CLIENT
## Project Overview
The REST API Client is a Java-based application designed to consume public REST APIs, fetch real-time data, and present it in a structured format. This project was developed as part of the CODTECH Internship Task 2, requiring the implementation of an HTTP-based API client capable of handling JSON responses efficiently.

The primary objective of this project is to retrieve and parse data from external web services, such as weather updates, user details, or other publicly available datasets. The application was built and executed in IntelliJ IDEA, ensuring a smooth development workflow with proper error handling and structured output formatting.

## Technology Stack
- Programming Language: Java
- HTTP Handling: HttpURLConnection, OkHttp (alternative)
- JSON Parsing: org.json library / Gson
- Development Environment: IntelliJ IDEA / Eclipse
-  Data Processing: Java Collections, Streams API
-  API Used: Public REST APIs (e.g., OpenWeatherMap, JSONPlaceholder)

## Project Workflow in Notepad++
### Step 1: Setting Up the API Client
- The program initializes an HTTP connection to fetch data from a public REST API.
- The API URL is specified, and a GET request is sent using HttpURLConnection.
- The response is read using an input stream, and the JSON data is stored as a string.
#### Execution Output (Console - API Call Success)
- API request sent successfully!
- Response received from API!

### Step 2: Parsing JSON Response
1. The response data is processed using the org.json library.
2. JSON keys are extracted to retrieve relevant information (e.g., title, temperature, user details).
3. The parsed data is then formatted for better readability.

### Step 3: Displaying Data in a Structured Format
- The extracted information is displayed in the console in a structured manner.
- Proper formatting ensures that users can easily interpret the output.
- If an error occurs, an exception handling mechanism prints an error message.

#### Execution Output
![image](https://github.com/user-attachments/assets/41ca2d27-ad91-431f-be9e-e4c1694dea2c)
---
## Key Features Implemented
**REST API Integration** – Fetches real-time data from public REST APIs using HTTP requests.
JSON Parsing – Extracts and processes relevant information from JSON responses.
Efficient Data Handling – Uses Java Collections and Streams API for structured data processing.
Error Handling & Robustness – Implements exception handling to manage API failures and invalid responses.
Scalability – Designed to handle multiple API requests efficiently for future extensions.
---

