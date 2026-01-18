# Blog-API-advanced_ver2
🚀 Features

- 🔐 JWT Authentication (login/sign-up)

- 👤 Custom User Model

- 📰 Blog Posts CRUD

- 🗂️ Category and Tag Management

- 💬 Comment System

- 🔎 Filtering, pagination, and search support



| Component     | Technology              |
| ------------- | ----------------------- |
| Backend       | Django 5.x              |
| API Framework | Django REST Framework   |
| Auth          | JWT (Simple JWT)        |
| Database      | PostgreSQL (via Docker) |
| Deployment    | Docker & Docker Compose |


- 📝 REST-style API design

- 🛠 Configurable via .env and settings



Blog_management_API_V4/
├── project/                       # Django project config
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── account/                       # User models, serializers, views
├── blog/                          # Blog management (posts, categories, etc.)
├── requirements.txt              # Python dependencies
├── docker-compose.yml            # Docker services
├── Dockerfile                    # Docker image build
└── .env                          # Environment variables (not committed)

