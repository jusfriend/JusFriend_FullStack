Tahapan instalasi di local
1. download composer
2. download laragon
3. buat folder, clone projek dari branch master

konfigurasi db
buat database mysql

konfigurasi web
1. buka folder projek di vscode
2. buka terminal di folder projek, install laravel pake command "composer install"
3. buka file .env, ganti database name dan username
4. buka terminal, run command php artisan migrate
5. run command php artisan serve untuk jalanin server nya
6. (additional) terminate server pake ctrl + c

push github untuk add new fitur (jangan langsung ke master)
1. buat branch masing masing
2. push update ke branch masing-masing 
