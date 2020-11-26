# instagram_laravel

過去に作成したもののアップロード



## インストール

laravel・データベースの環境(mysql)は持っていることが前提

```shell
git clone https://github.com/SakaiTaka23/OrganizeNote-ver2.git
cd oraganizenote-ver2 

cp .env.example .env

composer install
php artisan key:generate
データベースを作成
.envファイルのデータベース、ユーザーネーム、パスワードの修正
php artisan migrate:fresh
php artisan serve
```

