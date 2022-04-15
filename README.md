# Vdirect.github.io

# VDirect
 This project is made in PHP using Laravel Framework.

# Installation

#### 1. Clone the repository 

#### 2. Set the basic config
Edit example.env to .env <br />
Put your db username and password here with DB_DATABASE=vdirect and also set mailtrap details. <br />

    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=vdirect
    DB_USERNAME=root
    DB_PASSWORD=

    MAIL_DRIVER=smtp
    MAIL_HOST=smtp.mailtrap.io
    MAIL_PORT=2525
    MAIL_USERNAME=null
    MAIL_PASSWORD=null
    MAIL_ENCRYPTION=null

#### 3. Install Dependencies
    composer install
    npm install
    npm run dev                

#### 4. Migrate Database
    php artisan migrate:fresh
    php artisan db:seed

#### 5. Serve application
    php artisan serve
