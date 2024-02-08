# CRUD-MINI-PROJECT
This is a simple CRUD (Create, Read, Update, Delete) application built using Python Django framework with SQLite database backend. It allows users to perform basic CRUD operations on a set of data.

# Features
Create: Add new items to the database.
Read: View existing items in the database.
Update: Modify existing items in the database.
Delete: Remove items from the database.

# Technologies Used
Python 3.x
Django 3.x
SQLite

# Setup
To set up and run this project locally on your machine, follow these steps:

Clone this repository to your local machine using git clone https://github.com/your-username/your-repo.git
Navigate to the project directory: cd your-repo
Install the required dependencies: pip install -r requirements.txt
Apply migrations to create the SQLite database: python manage.py migrate
Start the development server: python manage.py runserver
Visit http://127.0.0.1:8000/ in your web browser to access the application.

# Usage
Navigate to the home page to view existing items.
Use the provided forms to create, update, or delete items.

# Directory Structure
```bash
project/
│
├── your_app/                  # Main application directory
│   ├── migrations/            # Database migration files
│   ├── templates/             # HTML templates
│   ├── models.py              # Database models
│   ├── views.py               # Views/controllers
│   └── ...
│
├── project/                   # Django project settings
│   ├── settings.py            # Project settings
│   ├── urls.py                # Project URL configurations
│   └── ...
│
├── manage.py                  # Django management script
└── requirements.txt           # Project dependencies
```
# Contributing
Contributions are welcome! Feel free to open issues and pull requests.

# License
This project is licensed under the MIT License.

# Author
Agnal R 
<BR>
GitHub: Agnal-R
