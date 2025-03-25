# Matrimony Website

## Overview
This is a basic matrimony website developed using Django for a DBMS (Database Management System) project. The platform allows users to register, create profiles, browse other profiles, and connect with potential matches.

## Features
- User authentication (Login, Registration)
- Profile creation and management
- Search and filter profiles
- Connect with other users
- Admin panel for managing users and profiles

## Technologies Used
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite
- **Environment Management:** Virtual Environment

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/username/matrimony-website.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Matrimony-Website-django-main
    ```
3. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```
4. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5. Apply database migrations:
    ```bash
    python manage.py migrate
    ```
6. Create a superuser for admin access:
    ```bash
    python manage.py createsuperuser
    ```
7. Run the server:
    ```bash
    python manage.py runserver
    ```

## Usage
- Visit `http://127.0.0.1:8000` in your browser.
- Register a new account or log in.
- Create or edit your profile.
- Search and filter profiles.
- Connect with other users.
- Access the admin panel at `http://127.0.0.1:8000/admin` using your superuser credentials.

## File Structure
```
.
├── db.sqlite3
├── manage.py
├── matrimony
│   ├── settings.py
│   ├── urls.py
│   ├── models.py
│   ├── views.py
│   ├── templates
│   ├── static
└── README.md
```

## License
This project is licensed under the MIT License.

## Acknowledgments
- Developed as part of a DBMS project.
- Thanks to all contributors and open-source libraries used.

---
For further queries, contact the project author via GitHub.

