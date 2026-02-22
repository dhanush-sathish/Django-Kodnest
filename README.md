# Django-Kodnest

A Django-based web application for the Kodnest learning and coding platform.

## Overview

Django-Kodnest is a web application built with the Django framework, designed to support the Kodnest coding education platform. It provides backend services and APIs for managing courses, users, and learning content.

## Prerequisites

- Python 3.8+
- pip
- virtualenv (recommended)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/dhanush-sathish/Django-Kodnest.git
   cd Django-Kodnest
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Project Structure

```
Django-Kodnest/
├── manage.py
├── requirements.txt
├── README.md
└── kodnest/
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

## License

MIT
