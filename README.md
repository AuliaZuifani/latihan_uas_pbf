BACKEND
1. git clone-> link nya
2. open vsCode, composer install
3. di .env bagian default.database ganti ke nama db nya kita
4. php spark serve kalo db sudah di insertin semuanya.


FRONTEND
1. composer create-project laravel/laravel nama_folder

2. ke http controller lalu buat controller sesuai nama tabel contoh (mahasiswaController.php)

3. ke resource masuk ke views nya terus bikin crud nya tapi harus bikin folder dulu contoh (mahasiswa) di dalemnya bikin crud create.blade.php lalu edit.blade.php lalu index.blade.php

4. ke routes->web.php
Route::resource('dosen_wali', \App\Http\Controllers\DosenWaliController::class);
kalo sudah jangan lupa bikin folder layouts di dalemnya bikin app.blade.php

5. kalo sudah crud composer install
6. php artisan key:generate
7. php artisan serve

kalo ada perubahan:
php artisan config:clear
php artisan view:clear


GITHUB
1. git init
2. git add .
3. git commit -m "initial commit"
4. git remote add origin https://github.com/kamu/sistem-promosi.git (salin link repo yang sudah dibikin)
5. git branch -M main
6. git push -u origin main

https://github.com/AuliaZuifani/latihan_uas_pbf
