# Company Corporate Portal

A dynamic corporate website with a Content Management System (CMS), developed using the Laravel framework.

## Project Overview

The Company Corporate Portal provides a platform to present company information and manage website content dynamically through an administrative panel.

## Technologies Used

- PHP
- Laravel
- MySQL
- HTML5
- CSS3
- JavaScript
- Bootstrap (if used in the project)

## Key Features

- Dynamic corporate website
- Admin authentication and dashboard
- Dynamic content management
- Database-driven website sections
- Responsive user interface
- Contact and inquiry management

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/tarifhasan18/Company_Corporate_Portal.git
```

### 2. Enter the project directory

```bash
cd Company_Corporate_Portal
```

### 3. Install PHP dependencies

```bash
composer install
```

### 4. Configure environment

```bash
copy .env.example .env
```

### 5. Generate application key

```bash
php artisan key:generate
```

### 6. Configure the database

Update the database credentials in the `.env` file.

### 7. Run migrations

```bash
php artisan migrate
```

### 8. Create storage link

```bash
php artisan storage:link
```

### 9. Install frontend dependencies (if required)

```bash
npm install
npm run build
```

### 10. Start the application

```bash
php artisan serve
```

Open `http://127.0.0.1:8000` in your browser.

## Developer

**MD. Tarif Hasan**
