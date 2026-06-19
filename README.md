# automated-software-installation

# AI-Powered Software Approval and Deployment System

## Overview

This project automates the software approval and deployment process in an enterprise environment. The system uses AI-powered email parsing to validate software installation requests, generate installation jobs, and securely deploy approved software to employee machines.

The solution follows a client-server architecture where the server validates approval requests and generates job files, while client agents execute approved installations after performing security checks.

---

## Features

* AI-based approval email parsing using NVIDIA AgentIQ / DeepSeek
* Automated software request validation
* Software policy verification
* Device mapping and authorization checks
* Secure SHA-256 hash verification
* Automated software installation
* Real-time installation notifications
* Installation logging and reporting
* Admin dashboard for monitoring requests and deployments

---

## Architecture

### Server Side

* FastAPI backend
* AI-powered email parsing
* Approval validation
* Job file generation
* Logging and monitoring dashboard

### Client Side

* C#/.NET background agent
* Periodic job polling
* Installer hash verification
* Software installation execution
* User notifications
* Log generation and reporting

---

## Technology Stack

### Backend

* Python
* FastAPI
* NVIDIA AgentIQ
* DeepSeek LLM

### Frontend

* HTML
* CSS
* JavaScript

### Client Agent

* C#
* .NET

---

## Workflow

1. Employee raises software installation request.
2. AI extracts information from approval emails.
3. Server validates software policies and approvals.
4. Job files are generated for approved requests.
5. Client agent polls the server for assigned jobs.
6. Installer integrity is verified using SHA-256.
7. Software is installed automatically.
8. Installation logs are uploaded to the server.

---

## My Contribution

I worked on the Client Side Agent implementation using C# and .NET.

Responsibilities:

* Polling the server for installation jobs
* Verifying installer hashes before execution
* Executing software installations
* Displaying installation notifications
* Uploading execution logs to the server
* Supporting scheduled and background execution

---

## Future Enhancements

* Active Directory integration
* Role-based access control
* Enhanced reporting dashboard
* Real-time notification system
* Support for additional deployment platforms

---

## Disclaimer

This project was developed as part of an internship project for learning and demonstration purposes.
