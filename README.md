# SmartTodo

SmartTodo is a simple To-Do List web application developed using Django and Python.

## Features

- Add new tasks
- View all tasks
- Edit existing tasks
- Delete tasks
- Mark tasks as completed or pending
- Manage tasks through Django Admin Panel
- Store task data in a database

## Technologies Used

- Python
- Django
- SQLite
- HTML
- Django Templates

## Project Structure

- `config/` - Main Django project configuration
- `tasks/` - Django application for managing tasks
- `templates/` - HTML templates
- `manage.py` - Django project management file

## How to Run the Project

1. Create and activate the virtual environment.
2. Install the required packages.
3. Run database migrations.
4. Start the Django development server.

```bash
python -m pip install -r requirements.txt
python manage.py migrate
python manage.py runserver