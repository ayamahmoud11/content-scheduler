# 📅 Content Scheduler

A full-stack Laravel + React web application for scheduling and managing social media posts across multiple platforms (Facebook, Twitter, Instagram, etc.).

---

## Features:
- Register/Login/Logout
- Create, schedule, and manage posts
- Attach posts to multiple platforms
- Auto-publish via Job
- Post analytics + logs
- Sanctum-based API authentication

---

## 🛠️ Tech Stack

| Layer     | Technology                              |
|-----------|------------------------------------------|
| Frontend  | React, Tailwind CSS, Axios, React Router |
| Backend   | Laravel, Sanctum, MySQL                  |
| Other     | JWT, Vite, Laravel Queues, Caching       |

---
### API Routes
```bash
POST /api/register

POST /api/login

GET /api/posts

POST /api/posts

GET /api/analytics

GET /api/platforms

GET /api/logs
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
