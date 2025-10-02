# 🔐 Auth System - Laravel 12 & Vue 3

Proyecto de autenticación personalizada con **Laravel 12 (Backend)** y **Vue 3 (Frontend)**.

## 📂 Estructura
- `backend/` → API con Laravel 12 (registro, login, protección de rutas)
- `frontend/` → SPA con Vue 3 (interfaz de usuario con TailwindCSS)

## 🚀 Tecnologías
- Laravel 12
- Vue 3
- TailwindCSS
- MySQL / SQLite
- Vite
- GitHub

## ⚙️ Instalación

### Backend (Laravel 12)
```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
