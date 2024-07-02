# Tkinter Note-Taking Application with MySQL Integration

This Python script implements a simple note-taking application using Tkinter for the GUI and MySQL for database storage. Users can register, log in, add notes, and view existing notes through a graphical interface.

## Features

- **Registration**: Allows users to register with a username, email, phone number, and password.
- **Login**: Registered users can log in securely with their credentials.
- **Note Management**: Users can add new notes, view existing notes, and manage note content.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.x
- tkinter library (included in standard Python installations)
- MySQL Connector for Python (`mysql-connector-python`)

## Setup

1. **MySQL Database Setup**:
   - Create a MySQL database named `notetaking`.
   - Modify the database connection details (`host`, `user`, `password`) in the script (`notetaking_app.py`) to match your MySQL setup.

2. **Installing Required Packages**:
   ```bash
   pip install mysql-connector-python
