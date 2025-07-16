# プロジェクト名
My Laravel App

## 開発環境
- PHP 8.1-fpm
- Laravel 8.83.29
- MySQL 8.0.26
- Docker 使用

## セットアップ方法
```bash
git clone https://github.com/haruna-satoh/your-repo.git
cd your-repo
docker compose up -d
cd src
composer install
cp .env.example .env
php artisan key:generate