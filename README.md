# お問い合わせフォーム

## 環境構築
Dockerのビルド

1. git clone リンク
2. docker-compose up -d
3. docker-compose exec app php artisan migrate
4. docker-compose exec app php artisan db:seed

## 使用技術
- Laravel 10.x
- PHP 8.x
- MySQL 8.x
- Docker, Docker Compose

## ER図
<img width="918" height="332" alt="Image" src="https://github.com/user-attachments/assets/70635f27-39ef-49d8-8146-975536f05445" />

## URL
- 開発環境：http://localhost/
- phpMyAdmin: http://localhost:8080/
