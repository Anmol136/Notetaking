# Tkinter Note-Taking App with MySQL

This Python application provides a simple note-taking system using Tkinter for the GUI and MySQL for database storage. Users can register, log in securely, add notes with titles and content, and view existing notes.

## Features

- **Registration and Authentication**: Users can register with unique credentials and securely log in to manage their notes.
  
- **Note Management**: Add new notes, view existing notes, and maintain a list of personal notes stored in a MySQL database.

## Setup

1. **Prerequisites**:
   - Python 3.x installed on your system
   - `tkinter` library (included in standard Python installations)
   - `mysql-connector-python` (install via `pip install mysql-connector-python`)

2. **MySQL Database Setup**:
   - Create a MySQL database named `notetaking`.
   - Adjust the database connection details (`host`, `user`, `password`) in the script (`notetaking_app.py`) to match your MySQL setup.

3. **Running the Application**:
   - Run `python notetaking_app.py` to start the application.
   - Use the login interface to access note management features.

## Usage

- **Registration**: New users can register with a username, email, phone number, and password.
  
- **Note Creation**: Logged-in users can add new notes with titles and content.
  
- **Note Viewing**: Users can view existing notes by selecting them from a list.

## Contributing

Contributions and feedback are welcome! Follow these steps to contribute:

1. Fork the repository and clone it locally.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Commit your changes with descriptive commit messages.
5. Push your branch to your fork and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
