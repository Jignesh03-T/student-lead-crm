# 📌 Student Lead CRM – Laravel Project

## 📖 Overview

Student Lead CRM is a customized Customer Relationship Management system built using Laravel. The project is developed by extending and modifying an open-source CRM foundation to meet specific business requirements related to student and lead management.

It demonstrates real-world software development practices including role-based access control, lead tracking workflows, API integrations, and interactive dashboard analytics. The system helps manage student inquiries, track leads efficiently, and monitor performance through a structured and secure interface.

This project highlights practical Laravel development skills such as backend customization, database design, authentication, and REST API usage.

---

## 🚀 Features

### 🔐 Role-Based Access Control

* Admin and user roles with controlled permissions
* Secure login and authentication system
* Different dashboards and access based on role

### 📊 Lead Management System

* Add, update, and delete student leads
* Track lead status (new, contacted, converted, etc.)
* Assign leads to specific users
* Lead history and activity tracking

### 📈 Dashboard Analytics

* Visual dashboard for monitoring leads
* Lead conversion and performance tracking
* Summary cards and statistics display

### 🔗 API Integration

* Integration with external APIs for data handling
* Demonstrates REST API usage in Laravel
* Data fetching and storage from external sources

### 🗄️ Database Management

* MySQL database integration
* Proper table relationships and migrations
* Efficient data storage and retrieval

---

## 🛠️ Tech Stack

* **Backend:** Laravel (PHP Framework)
* **Frontend:** Blade Templates, HTML, CSS, Bootstrap
* **Database:** MySQL
* **API:** REST API Integration
* **Authentication:** Laravel Auth System

---

## ⚙️ Installation & Setup

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/student-lead-crm.git
cd student-lead-crm
```

### Step 2: Install Dependencies

```bash
composer install
```

### Step 3: Setup Environment

Copy `.env.example` file and create `.env`

```bash
cp .env.example .env
```

Update database credentials inside `.env`:

```
DB_DATABASE=your_db_name
DB_USERNAME=root
DB_PASSWORD=
```

### Step 4: Generate App Key

```bash
php artisan key:generate
```

### Step 5: Run Migrations

```bash
php artisan migrate
```

### Step 6: Start Server

```bash
php artisan serve
```

Open in browser:

```
http://127.0.0.1:8000
```

---

## 📂 Project Structure

* **app/** → Controllers, Models, Middleware
* **routes/** → Web & API routes
* **resources/views/** → Blade templates (UI)
* **database/** → Migrations & seeders
* **public/** → Static assets

---

## 🎯 Learning Outcomes

* Practical Laravel project development
* Understanding of CRM workflow
* Role-based authentication implementation
* API integration handling
* Dashboard and analytics creation
* Real-world database management

---

## 🔮 Future Improvements

* Email & WhatsApp notifications for leads
* Advanced analytics dashboard
* Export leads to Excel/PDF
* Deployment on live server (AWS/Hostinger)
* Mobile responsive UI improvements

---

## 👨‍💻 Author

Developed as a practical Laravel project to demonstrate backend development, CRM customization, and real-world application features aligned with industry requirements.

## Output ScreenShots
<img width="1919" height="681" alt="Screenshot 2025-12-13 160056" src="https://github.com/user-attachments/assets/77a86327-7a97-49c3-90f1-b9e55c9aca0c" />
<img width="1890" height="842" alt="Screenshot 2025-12-13 160038" src="https://github.com/user-attachments/assets/5c60dc40-d098-4799-88da-0fa4e0c887d6" />
<img width="1266" height="501" alt="Screenshot 2025-12-13 162938" src="https://github.com/user-attachments/assets/70b0b7a4-83f6-4659-a390-3f51fe327dca" />


