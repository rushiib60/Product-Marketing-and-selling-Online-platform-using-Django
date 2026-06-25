# Online Product Marketing & Selling Platform

A Django-based e-commerce web application for online product marketing and selling, with integrated library and student management modules.

## Features

- Product listing, marketing, and sales management
- Library management system (books, authors, borrowing)
- Student portal integration
- Admin panel via Django's built-in admin interface
- SQLite database (zero-config, easy to swap for PostgreSQL/MySQL)

## Project Structure

```
├── manage.py           # Django management script
├── db.sqlite3          # SQLite database
├── library/            # Library app — core settings and config
├── librarian/          # Librarian app — book and author management
└── student/            # Student app — student records and portal
```

## Tech Stack

- **Framework:** Django (Python)
- **Database:** SQLite (default) / PostgreSQL
- **Frontend:** HTML, CSS, Bootstrap
- **Admin:** Django Admin

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/rushiib60/Product-Marketing-and-selling-Online-platform-using-Django.git
   cd Product-Marketing-and-selling-Online-platform-using-Django
   ```

2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scriptsctivate
   pip install django
   ```

3. Apply migrations:
   ```bash
   python manage.py migrate
   ```

4. Create a superuser (for admin access):
   ```bash
   python manage.py createsuperuser
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Open `http://127.0.0.1:8000` in your browser
   - Admin panel: `http://127.0.0.1:8000/admin`
