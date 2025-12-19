# Medicine Bank

A Laravel-based pharmacy management system for handling medicine orders efficiently.

## 🎯 Overview

Medicine Bank is a web application built with Laravel that streamlines the process of managing medicine orders. It provides an intuitive admin interface powered by Voyager for easy content management and order tracking.

## ✨ Features

- **Order Management**: Create, track, and manage medicine orders
- **Admin Dashboard**: Powerful Voyager admin panel for content management
- **Database Management**: MySQL backend for reliable data storage
- **User-Friendly Interface**: Clean and responsive design
- **Order Tracking**: Monitor order status and history

## 🛠️ Technical Stack

- **Framework**: Laravel (PHP)
- **Admin Panel**: [Voyager](https://voyager.devdojo.com/)
- **Database**: MySQL
- **Language**: PHP

## 📋 Prerequisites

- PHP >= 7.3
- Composer
- MySQL
- Node.js & NPM

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/touficSl/pharmacy.git
   cd pharmacy
   ```

2. **Install dependencies**
   ```bash
   composer install
   npm install
   ```

3. **Configure environment**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Setup database**
   - Create a MySQL database
   - Update `.env` with your database credentials
   - Import the SQL dump: `data_dump_31_05_2020.sql`
   ```bash
   php artisan migrate
   ```

5. **Install Voyager**
   ```bash
   php artisan voyager:install
   ```

6. **Run the application**
   ```bash
   php artisan serve
   ```

Visit `http://localhost:8000` to access the application.

## 📦 Database

A sample database dump is included: `data_dump_31_05_2020.sql`

Import it to get started with sample data.

## 🔧 Admin Panel

Access the Voyager admin panel at `/admin` after installation.

Default credentials will be created during Voyager installation.

## 👤 Author

**Toufic SL**
- GitHub: [@touficSl](https://github.com/touficSl)
- LinkedIn: [toufic-sleimanl]([https://github.com/touficSl](https://www.linkedin.com/in/toufic-sleiman))

## 📝 License

This project is open source and available under the MIT License.

---

For more information about Voyager, visit the [official documentation](https://voyager.devdojo.com/).
