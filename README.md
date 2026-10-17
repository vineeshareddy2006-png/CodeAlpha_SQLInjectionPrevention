# CodeAlpha_SQLInjectionPrevention
# SQL Injection Prevention System

## Objective
To demonstrate how parameterized SQL queries help prevent SQL injection attacks.

## Technologies Used
- Python
- SQLite
- Password hashing using PBKDF2-HMAC with SHA-256

## Features
- User registration and login
- Password hashing with a random salt
- Parameterized SQL queries
- Testing correct and incorrect passwords
- Testing a SQL injection-style username

## Result
The system accepts valid login details and rejects incorrect credentials and the tested SQL injection-style input.

## Limitation
This is a local demonstration project. It does not include cloud deployment, AES-256 encryption, or a capability-code mechanism.
