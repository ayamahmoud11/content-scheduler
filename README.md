# 📅 Content Scheduler

A full-stack Laravel + React web application for scheduling and managing social media posts across multiple platforms (Facebook, Twitter, Instagram, etc.).

---

## 🌟 Features

- ✅ User registration & login  
- 📝 Create, edit, and schedule posts  
- 📊 Dashboard to view upcoming posts  
- ⚙️ Toggle platforms (Facebook, Twitter, Instagram)  
- 🔐 JWT-based API authentication  
- 🎨 Facebook-style UI with blue navbar  
- 📦 Laravel backend & React frontend  

---

## 🛠️ Tech Stack

| Layer     | Technology                              |
|-----------|------------------------------------------|
| Frontend  | React, Tailwind CSS, Axios, React Router |
| Backend   | Laravel, Sanctum, MySQL                  |
| Other     | JWT, Vite, Laravel Queues, Caching       |

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ayamahmoud11/content-scheduler.git
cd content-scheduler
```
و```
### 2. Backend Setup (Laravel)
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
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
