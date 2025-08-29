Configurasi Laravel + vuejs
1. Sudo apt update
2. Install php
    terminal : sudo apt install php php-cli php-fpm php-json php-common php-mysql php-zip php-gd php-mbstring php-curl php-xml
3. Cek version php
    terminal : php -v
4. Sudo apt install composer
5. Create project pertama dengan nama first_project
    terminal : composer create-project laravel/laravel first_project
6. Untuk lingkungan development, pakai serverweb bawaan laravel aja dulu
    terminal : php artisan serve --host=192.168.3.13 --port=8000
7. Buka akses firewall port 8000
    terminal : sudo ufw allow 8000

Configurasi postgree
1. sudo apt update
2. Instal Paket PostgreSQL
    terminal : sudo apt install postgresql postgresql-contrib
3. Otentikasi dan Pembuatan User,  Beralih ke User postgres,
   dan buat user postgres
    terminal : sudo -i -u postgres
4. Masuk ke shell psql
    terminal : psql
5. Konfigurasi Kata Sandi
    a. Masuk ke mode psql, dan ketikkan
        terminal : password \postgrest
    b. Masukkan password baru 
    c. /p/master/p/ exit
6. exit untuk masuk ke direktori project laravel anda
7. Untuk masuk ke user postgre => 
    terminal : sudo -i -u postgres