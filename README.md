# Flask TODO Application

A simple TODO list application built with Flask and SQLAlchemy.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This is a basic TODO list application developed using Flask, a lightweight WSGI web application framework in Python. The application uses SQLAlchemy as the ORM to interact with an SQLite database.

## Features

- Add new tasks
- View all tasks
- Mark tasks as completed
- Delete tasks

## Installation

### Prerequisites

- Python 3.6+
- pip (Python package installer)

### Steps

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/Albinmanuvel/Simple-Flask-Webapp-for-Todo-list.git
    cd flask-todo-app
    ```

2. **Create a Virtual Environment**:

    ```sh
    python -m venv env
    ```

3. **Activate the Virtual Environment**:

    On Windows:

    ```sh
    .\env\Scripts\Activate
    ```

    On macOS/Linux:

    ```sh
    source env/bin/activate
    ```

4. **Install Dependencies**:

    ```sh
    pip install -r requirements.txt
    ```

5. **Create the Database**:

    ```sh
    python create_db.py
    ```

6. **Run the Application**:

    ```sh
    python app.py
    ```

The application will be available at `http://127.0.0.1:5000/` or localhost5000 in the default web browser .

## Usage

### Adding a Task

1. Enter the task content in the input field.
2. Click "Add Task".

### Viewing Tasks

All tasks will be listed on the homepage in the order they were added.

### Marking a Task as Completed

Click the "Update" link next to the task to mark it as completed.

### Deleting a Task

Click the "Delete" link next to the task to remove it from the list.

### Updating a Task

Click the "Update" link next to the task to update the list.

## Project Structure

