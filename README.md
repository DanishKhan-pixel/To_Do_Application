# Task Management App (Django)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)


## Introduction

This is a Task Management App built using Django. It provides a platform for users to manage their tasks efficiently. The app includes user authentication, task creation, update, deletion, search, and filtering by status. Additionally, it has error handling and can be easily containerized using Docker.

## Features

1. **User Authentication:**
   - User registration (Signup)
   - User login and logout
   - Password reset functionality

2. **Task Management:**
   - Users can create new tasks.
   - Users can update and delete their tasks.
   - Users can view their tasks.
   - Users Search tasks.
   - Users download tasks list in form of json and csv 

3. **Front End:**
   - I Used Bootstrap5 for App Front End.
   - Using django-crispy forms for better look and validation.

4. **Search Functionality:**
   - Users can search for tasks by title and Status.

5. **Task Filtering:**
   - Users can filter their tasks by status.

6. **Error Messaging Handling:**
   - The app provides comprehensive error handling and user-friendly error messages.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python (3.6 or higher)
- Django (3.2 or higher)


## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone <repository_url>
2. Navigate to the project directory:
    ```bash
   cd task_management_app
3. Create a virtual environment (recommended) and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate
4. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
## Usage

1. Migrate the database:

   ```bash
   python manage.py migrate
2. Create a superuser to manage the admin panel:

    ```bash
    python manage.py createsuperuser
3. Start the development server:

    ```bash
    python manage.py runserver
4. Access the app in your web browser at http://localhost:8000/.

5. To access the admin panel, go to http://localhost:8000/admin/ and log in with the superuser credential.





