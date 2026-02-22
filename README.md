# Django-Kodnest

A Django-based project for Kodnest.

## Overview

This repository contains the Django-Kodnest application. It is set up for orchestrated development with automated issue tracking and webhook integrations.

## Getting Started

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run migrations: `python manage.py migrate`
4. Start the server: `python manage.py runserver`

## Project Structure

- `manage.py` - Django management script
- `requirements.txt` - Python dependencies
- `.github/` - GitHub Actions workflows and issue templates

## Contributing

This project uses an automated orchestrator agent for issue tracking and PR management. Issues are automatically assigned and worked on by the agent pipeline.
