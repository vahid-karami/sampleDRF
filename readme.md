# Django REST Framework – Basic API (Learning Project)

A simple REST API built with **Django** + **Django REST Framework (DRF)** as a personal learning project.  
This repo follows the same core structure as a “basic API with DRF” tutorial: model → serializer → view → URL routing.

## Features

- Django project with a DRF-powered API
- JSON responses
- Example endpoints (list/create, retrieve/update/delete if enabled)
- Clean, beginner-friendly structure

---

## Tech Stack

- Python 3.10+ (works on 3.9+ too)
- Django
- Django REST Framework

---

## Project Structure (example)

├── manage.py
├── requirements.txt
├── README.md
├──     sampleDRF/
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
└── app/
├── init.py
├── admin.py
├── apps.py
├── migrations/
├── models.py
├── serializers.py
├── views.py
├── urls.py
└── tests.py

