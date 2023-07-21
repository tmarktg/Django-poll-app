# Django Poll App

![App Screenshot](app_screenshot.png)

## Description

Django Poll App is a web application built with Django that allows users to create and participate in polls. It provides a simple and intuitive interface for creating questions and choices, voting, and viewing poll results.

## Features

- Create polls with multiple-choice questions
- Allow users to vote on polls
- Display poll results in real-time
- Admin interface for managing polls and choices

## Installation

Follow these steps to set up the Django Poll App on your local machine:

1. Clone the repository:

```bash
git clone https://github.com/your-username/django-poll-app.git
cd django-poll-app

2. Create a virtual environment and activate it

python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install the required dependencies

pip install -r requirements.txt

4. Apply database migrations

python manage.py migrate

5. Create a superuser to access the admin interface

python manage.py createsuperuser

6. Start the development server

python manage.py runserver

7. Open your browser and go to http://localhost:8000 to access the app.

- Note if the python command is red in VSCode, use python3

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Django team for their fantastic web framework and documentation,
  follow step-by-step here: https://docs.djangoproject.com/en/4.2/intro/tutorial01/.
