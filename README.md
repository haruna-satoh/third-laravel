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
```

言語ファイルの日本語化

以下のパッケージを使用しています。
```bash
composer require laravel-lang/lang:~7.0 --dev
cp -r vendor/laravel-lang/lang/src/ja resources/lang/
```
config/app.phpで日本語の設定をしています。
```bash
'locale' => 'ja',
```