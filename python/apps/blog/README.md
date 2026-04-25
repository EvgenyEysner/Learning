# Django Blog Platform 🚀

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Django](https://img.shields.io/badge/Django-4.1-green.svg)

A feature-rich blog platform built with Django framework ✨

## Features 🌟

- 👤 Custom user authentication
- 📝 Blog posts with tagging system
- 💬 Comment system
- 🔍 Full-text search functionality
- 📨 Email sharing
- 📱 Responsive Bootstrap design
- 📰 RSS feed support
- ⚡ Fast pagination

## Tech Stack 💻

- Python
- Django
- PostgreSQL
- Bootstrap 5
- Docker

## Installation 🛠️

1. Clone the repository:

```bash
git https://github.com/EvgenyEysner/blog.git
cd blog
```

2. Build and run with Docker:

```bash
docker-compose up --build
```

3. Create a superuser:

```bash
docker-compose exec backend python manage.py createsuperuser
```

## Environment Variables 🔐

Create a `.env` file in the root directory:

```
DJANGO_DEBUG=True
DJANGO_SECRET_KEY=your-secret-key
DJANGO_DATABASE_URL=postgres://user:pass@db:5432/blog
DJANGO_SERVER_URL=http://localhost:8000
```
