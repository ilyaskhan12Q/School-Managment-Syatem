# School-Managment-Syatem
A complete School Management System built to handle student, teacher, class, and exam management. Includes attendance tracking, timetable scheduling, role-based access control, and reporting — designed for schools to digitize daily operations efficiently.
🚀 Setup Commands (First Time Only)
1. Navigate to Project Directory
cd /home/ilyas-khan/Desktop/schoool

bash


2. Install PHP Dependencies
composer install

bash


3. Install Node.js Dependencies (if needed for frontend assets)
npm install
npm run build

bash


4. Set Up Environment
cp .env.example .env
php artisan key:generate

bash


5. Run Database Migrations
php artisan migrate

bash


🏃‍♂️ Daily Run Commands
Start the Development Server
php artisan serve

bash


The application will be available at: http://127.0.0.1:8000 (or http://127.0.0.1:8001 if 8000 is busy)

📋 Additional Useful Commands
Clear Application Cache
php artisan cache:clear
php artisan config:clear
php artisan view:clear

bash


Reset Database (if needed)
php artisan migrate:fresh

bash


Create a New User Account
php artisan tinker

bash


Then in the tinker console:

User::create(['name' => 'Admin', 'email' => 'admin@school.com', 'password' => bcrypt('password')]);
exit

php


🎯 Quick Start Guide
Run the server: php artisan serve
Open browser: Go to http://127.0.0.1:8000
Register/Login: Create an account or login
Access Dashboard: Navigate to the school management dashboard
Start Managing: Add classes, students, teachers, and track attendance
The system is now fully functional and ready for use!
