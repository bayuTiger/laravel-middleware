# 【Laravel】 Middlewareを使ってみよう

## 環境

- Laravel: 8.6.2
- Vue.js: 2.6.12
- PHP: 8.0.8
- Composer: 2.5.1
- Node.js: 19.3.0

```zsh
// envのDB接続部を書き換えておく
php artisan migrate:fresh
composer require laravel/ui
php artisan ui vue --auth
npm install
npm install resolve-url-loader@^5.0.0 --save-dev --legacy-peer-deps
npm install vue-loader@^15.9.8 --save-dev --legacy-peer-deps
composer require laravel/pint --dev
npm run dev
php artisan serve
```

## 概要

## テーブル作成(migration, model)

## 