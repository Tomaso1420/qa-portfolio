# QA Portfolio

## About Me

QA Engineer with a technical background in backend development.

This portfolio includes practical projects in manual testing, API testing, working with Postman and Swagger, creating checklists, writing bug reports, and basic test automation in Java.

---

## Skills

### Testing

* Functional testing
* API testing
* Requirements analysis
* Creating checklists and bug reports
* Positive and negative testing
* HTTP status code and JSON response validation
* Authorization testing
* Basic understanding of client-server architecture

### Tools

* Postman
* Swagger / OpenAPI
* Git, GitHub, GitLab
* Maven
* Docker
* PostgreSQL

### Programming & Databases

* Java
* JUnit 5
* Mockito
* AssertJ
* Python
* FastAPI
* SQL basics
* REST API
* JSON
* JWT basics
* RabbitMQ basics
* Redis basics

---

## Portfolio Structure

```text
qa-portfolio/
│
├── postman_restful_booker/
│   ├── Booker.postman_collection.json
│   └── README.md
│
├── swagger_api_testing/
│   ├── checklist.xlsx
│   ├── bug_report.xlsx
│   └── README.md
│
├── java_autotests_student_api/
│   ├── studenttestexamples.zip
│   └── README.md
│
├── backend_projects/
│   ├── NormTasks_Testing.md
│   ├── Sudoku_Project_Testing.md
│   └── DocValidatorBot_Testing.md
```

---

## Projects

### 1. Postman API Testing — Restful Booker

Folder: `postman_restful_booker`

A practical project for testing the Restful Booker REST API using Postman.

What was done:

* Created a Postman collection
* Implemented requests for working with bookings
* Configured getting a list of bookings
* Configured getting a booking by id
* Implemented authorization token creation
* Added requests for creating, updating, and deleting a booking
* Used environment variables
* Implemented saving `booking_id`
* Implemented saving `token`
* Added Basic authentication
* Added basic status code checks
* Added JSON schema validation using tv4

Tools:

`Postman`, `REST API`, `JSON`, `Basic Auth`, `Token Auth`, `tv4`

---

### 2. Swagger API Testing

Folder: `swagger_api_testing`

A practical project for manual API testing using Swagger documentation.

What was done:

* Analyzed API documentation in Swagger
* Created a testing checklist
* Performed positive and negative checks
* Checked required fields
* Checked input data validation
* Created bug reports
* Added steps to reproduce for found defects
* Described actual and expected results
* Specified defect priorities

Files:

* `checklist.xlsx` — API testing checklist
* `bug_report.xlsx` — bug reports for found defects

Tools:

`Swagger`, `REST API`, `Excel`, `Checklist`, `Bug Report`

---

### 3. Java Autotests — Student API

Folder: `java_autotests_student_api`

A practical project for implementing and automating a requirement check for a Student API.

Requirement:

when searching for a student via `GET /api/v1/students/{id}`, if the student does not exist in the database, the API should return the `404` status code.

What was done:

* Analyzed the requirement
* Implemented handling for the case when a student does not exist in the database
* Added an exception for a missing student
* Prepared basic autotests
* Automated a negative scenario check
* Checked service behavior when searching for a student by a non-existing id

Tools:

`Java`, `Spring Boot`, `JUnit 5`, `Mockito`, `AssertJ`, `Maven`, `Git`

---

### 4. Backend Projects

Folder: `backend_projects`

This section contains descriptions of backend projects where I participated as a developer and tester.
These projects demonstrate my understanding of server-side logic, REST API, databases, authorization, and backend services.

---

#### DocValidator Bot

Repository: https://github.com/Tomaso1420/doc-validator-bot

An AI bot for analyzing legal documents and preparing legal texts. The bot had real users, and during development I gained experience working in Scrum.

Implemented:

* User document upload
* AI-based document risk analysis
* Processing documents in different formats
* Searching for relevant information using RAG
* Generating responses for users
* Handling invalid files
* Creating templates for legal documents
* Backend logic for user interaction

Stack:

`Python`, `FastAPI`, `RAG`, `ChromaDB`, `Telegram Bot API`, `OCR`

---

#### NormTasks

Repository: https://github.com/Tomaso1420/NormTasks

A backend project for a Kanban board used to manage projects and tasks for a small web studio. The project was completed during an internship.

Implemented:

* User registration and authorization
* JWT authorization
* Project management
* Board management
* Task management
* Moving tasks between columns
* Interaction with PostgreSQL
* Running the project with Docker

Stack:

`Python`, `FastAPI`, `PostgreSQL`, `Docker`, `JWT`, `REST API`

---

#### Sudoku Project

Repository: https://github.com/Tomaso1420/sudoku-project

A REST API application for generating and solving Sudoku with asynchronous task processing.

Implemented:

* Creating tasks via API
* Sudoku generation
* Sudoku solving
* Getting a task by id
* Storing task statuses
* Handling `pending`, `processing`, `done`, and `failed` statuses
* Asynchronous processing with a worker
* Interaction with PostgreSQL
* Running services with Docker

Stack:

`Python`, `FastAPI`, `PostgreSQL`, `RabbitMQ`, `Docker`, `REST API`

---

## Contacts

GitHub: https://github.com/Tomaso1420
Email: [Artem82005@mail.ru](mailto:Artem82005@mail.ru)
Telegram: @Tomaso1420
