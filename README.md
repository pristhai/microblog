# Flask Web App

This project is a Flask web application based on the Flask Mega-Tutorial by Miguel Grinberg. The app includes features such as user authentication, profile pages, and avatars.

## Features

- User login/logout and registration
- Profile page with user information and avatar
- User authentication using Flask-Login
- Password hashing with Werkzeug
- Database integration using SQLAlchemy

## Setup

### Prerequisites

- Python 3.12 or higher
- Flask
- Flask-Login
- SQLAlchemy
- Werkzeug

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/your-repository.git

2. Navigate to the project directory:
   ```bash
   cd your-repository

4. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate
   # On Windows, use `venv\Scripts\activate`

6. Install the required packages:
   ```bash
   pip install -r requirements.txt

8. Initialize the database:
   ```bash
   flask db upgrade

### Running the Application
To start the Flask development server, use:
```bash
flask run
```
The application will be available at http://127.0.0.1:5000.
