
# Docker Lab: Containerizing a Three-Tier Application
**INET 4031 - Introductions to Systems**

This lab introduces Docker and Docker Compose by having you containerize a
real, multi-service application. You will package three components: Apache,
Flask, and MariaDB. These will be packaged into separate containers and wired together so they function as a complete application.

The application code and scaffolding are provided. Your job is to complete the Dockerfiles, verify the stack runs correctly, and document your work below.

> **Directions and explanations for this lab are on the repository Wiki.**
> Refer to the Wiki pages for step-by-step instructions.

---

*The sections below are for you to fill out. Replace each placeholder with your own content before submitting. Having a detailed README is the best practice for showing your work in future GitHub repositories.*

---

# Project Overview

This project is a three-tier web application using Docker. It includes Apache as the web server, Flask as the backend, and MariaDB as the database. These services work together to handle requests and store data. Users interact with the website through the browser.

# Prerequisites

Docker and Docker Compose must be installed on the VM. You also need access to a Linux terminal or server. The project files must be cloned from GitHub. No other special setup is required.

# Getting Started

First, clone the repository to your machine. Go into the project folder using cd. Run docker compose up --build to start all services. Then open the browser to access the application.

# Configuration

The .env file stores important settings like database name, user, and password. These values are used by both Flask and MariaDB. You do not hardcode sensitive data in the files. Each teammate may need to adjust these values if needed.

# Verification

Run the check-lab.sh script to test if everything is working. If all checks pass, you will see “PASS” for each service. You can also open the website in a browser to confirm it loads. All services (db, app, web) should be healthy.


