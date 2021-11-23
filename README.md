# Laravel-React-Auth
Cách chạy:
- Cài XAMPP
- Bật XAMPP Control Panel, start Apache và MySQL
- Vào trình duyệt mở http://localhost/phpmyadmin, chọn New, gõ auth vào ô Database name và chọn Create
- Vào trang https://getcomposer.org/doc/00-intro.md, tải và cài đặt Composer
- Mở terminal, cd đến thư mục Auth, gõ các lệnh: composer update, npm install
- Vào file config/mail.php, tìm dòng 'from' => ['address' => 'xxx', sửa xxx thành email của mình
- Vào file .env, tìm chỗ MAIL_USER, MAIL_PASSWORD, điền vào (để server xác nhận mail admin)
- Vào terminal gõ lệnh php artisan serve, mở trình duyệt vào địa chỉ 127.0.0.1:8000 
