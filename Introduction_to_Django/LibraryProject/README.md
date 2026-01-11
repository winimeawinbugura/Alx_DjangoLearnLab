# LibraryProject

## Introduction to Django Development Environment Setup

### Objective

This project introduces the basics of **Django** by setting up a development environment, creating a Django project, and running the development server. It serves as a foundation for understanding Django’s workflow and project structure.

---

## Project Description

**LibraryProject** is a basic Django project created to demonstrate:

* Django installation
* Project creation
* Running the Django development server
* Understanding the default Django project structure

---

## Requirements

* Python 3.x
* pip (Python package manager)
* Django

---

## Installation Steps

### 1. Install Django

Ensure Python is installed, then run:

```bash
pip install django
```

Verify installation:

```bash
django-admin --version
```

---

### 2. Create the Django Project

```bash
django-admin startproject LibraryProject
```

Navigate into the project directory:

```bash
cd LibraryProject
```

---

### 3. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

You should see the **default Django welcome page**, confirming the setup is successful.

---

## Project Structure Overview

```text
LibraryProject/
│
├── LibraryProject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── manage.py
└── README.md
```

### Key Files Explained

* **settings.py** – Contains configuration settings for the Django project.
* **urls.py** – Manages URL routing for the application.
* **manage.py** – Command-line utility used to interact with the Django project.

---

## Repository Information

* **GitHub Repository:** `Alx_DjangoLearnLab`
* **Directory:** `Introduction_to_Django`

---

## Author

**Winime A. Azumah**

