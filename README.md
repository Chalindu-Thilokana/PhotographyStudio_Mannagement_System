# 📸 Photography Management System (Laravel 11 + Jetstream + Livewire)

A Laravel-based web application for managing a photography business. This system allows users to book appointments and admins to manage bookings, users, and packages.

## 🚀 Tech Stack

- **Laravel 11**
- **Laravel Jetstream (Livewire)**
- **Livewire 3**
- **Laravel Sanctum**
- **Tailwind CSS**
- **MySQL / MariaDB**

---

## 🔑 Features

### 🧑‍💼 For Users:
- Register & Login (Jetstream Authentication)
- View Available Photography Packages
- Book Appointments
- View Appointment Status (Approved / Pending)

### 🛠️ For Admins:
- Approve or Reject Appointments
- Add / Edit / Delete Photography Packages
- Manage Users
- Dashboard with stats (Appointments, Users, Packages)

---

## 🖥️ Requirements

- PHP ^8.2
- Composer
- Node.js & NPM
- MySQL or compatible DB

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/photography-management.git
cd photography-management

# Install PHP dependencies
composer install

# Install frontend dependencies
npm install && npm run build

# Copy and configure environment
cp .env.example .env
php artisan key:generate

# Set DB credentials in .env
php artisan migrate

# (Optional) Seed data
php artisan db:seed

# Serve the app
php artisan serve
