# Project Overview

This API allows users to:

- Register and authenticate
- Create, read, update, and delete posts
- Follow other users
- Like and comment on posts
- View their own posts and the posts of users they follow

## Features

### User Authentication:
- Secure user registration and login using Django's built-in authentication system.
- Implement robust password hashing and salting.

### Post Management:
- Create, read, update, and delete posts with rich text formatting (optional).
- Implement pagination and filtering for efficient data retrieval.

### User Interactions:
- Follow other users and view their posts.
- Like and comment on posts.
- Implement notifications for new followers, likes, and comments.

### Data Validation:
- Validate user input using Django's built-in validators and custom validation logic.
- Handle potential errors gracefully and provide informative error messages.

### Testing:
- Write unit tests for all API endpoints to ensure code quality and reliability.
- Implement integration tests to verify the overall system functionality.

## Technologies Used

- **Django**: A high-level web framework for Python.
- **Django REST Framework**: A powerful toolkit for building RESTful APIs with Django.
- **PostgreSQL**: (or another suitable database) for data storage.
- **Python**: The programming language.
- **Git**: For version control.

## Project Structure

```plaintext
social_media_api/
├── social_media_api/  # Django app
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── tests.py
│   ├── urls.py
│   └── ...
├── config/  # Project-level settings
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── ...
├── requirements.txt
├── README.md
└── ...
```

## Getting Started

### Clone the repository:

```bash
git clone https://github.com/Thabangmontja/alx_DjangoLearnLab.git
cd alx_DjangoLearnLab/social_media_api
```

### Create a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate  # On macOS/Linux
source venv/Scripts/activate  # On Windows
```

### Install dependencies:

```bash
pip install -r requirements.txt
```

### Run migrations:

```bash
python manage.py migrate
```

### Create a superuser:

```bash
python manage.py createsuperuser
```

### Run the development server:

```bash
python manage.py runserver
