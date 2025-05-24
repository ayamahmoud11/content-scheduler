# 📅 Content Scheduler

A full-stack Laravel + React web application that allows users to create, schedule, and manage social media posts across multiple platforms such as Twitter, Instagram, and LinkedIn.

---

## 🚀 Features

- User registration, login, and logout (with Laravel Sanctum)
- Create, schedule, and edit posts
- Attach posts to multiple platforms
- Auto-publishing of scheduled posts (via Laravel job scheduler)
- Post analytics and activity logs
- API authentication using Bearer Tokens

---

## 🛠️ Tech Stack

| Layer     | Technology                              |
|-----------|------------------------------------------|
| Frontend  | React, Tailwind CSS, Axios, React Router |
| Backend   | Laravel 12, Sanctum, MySQL               |
| Utilities | JWT, Vite, Laravel Queues, Caching       |

---

## 🔗 API Endpoints

```http
POST     /api/register         - Register new user
POST     /api/login            - Login and get token
POST     /api/logout           - Logout user
GET      /api/posts            - List all posts
POST     /api/posts            - Create a new post
GET      /api/posts/{id}       - Show single post
PUT      /api/posts/{id}       - Update post
DELETE   /api/posts/{id}       - Delete post
GET      /api/platforms        - List available platforms
GET      /api/analytics        - Post analytics
GET      /api/logs             - Activity logs
```


## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ayamahmoud11/content-scheduler.git
cd content-scheduler
```

### 2. Backend Setup (Laravel)
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```
### 3. Frontend Setup (React)
```bash
Copy
Edit
cd frontend
npm install
npm run dev
```
### 4. Run The project Port 
```bash
http://localhost:5173/
```
