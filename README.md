## ✨ Inventory Management System

Inventory Management System with Laravel 10 and MySql.
## 😎 Features
- POS
- Orders
  - Pending Orders
  - Complete Orders
  - Pending Due
- Purchases
  - All Purchases
  - Approval Purchases
  - Purchase Report
- Products
- Customers
- Suppliers

## 🚀 How to Use

1. Go into the repository 

```bash
cd inventory-management-system
```

2. Install Packages 

```bash
composer install
```


3. Copy `.env` file 

```bash

cp .env.example .env

```

4. Generate app key 

```bash
php artisan key:generate
```

5. Setting up your database credentials in your `.env` file.
6. Seed Database: 

```bash

php artisan migrate:fresh --seed

```
7. Create Storage Link

```bash
php artisan storage:link
```

8. Install NPM dependencies 

```bash

npm install && npm run dev

```
9. Run 

```bash

php artisan serve

```
10. Try login with email: 

```bash

admin@admin.com

```
and password: 

```bash

password

```
