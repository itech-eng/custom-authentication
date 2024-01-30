# Custom Authentication || A Complete Laravel Custom Authentication Solution 
Laravel custom authentication with google 2fa. A complete auth system like register, login, verify email, forgot password etc.

# Technologies Behind
-> Laravel-10 , A PHP Framework
-> Mysql Database
-> Eloquent ORM
-> Quiry Builder
-> Tailwind Css
-> Rest Api

# Requirements
-> node js
-> Composer
-> PHP 8.1^
-> mysql 8



# Installation Command
```bash
    composer install
```
if facing error try this
```bash
    composer install --ignore-platform-reqs
```
```bash
    php artisan key:generate
```
```bash
    php artisan migrate --seed
```
```bash
    php artisan storage:link
```
```bash
    yarn install
```
```bash
    yarn build
```

Then project run command is 
```bash
    php artisan serve
```

# General Features (api list)
```bash
    /auth/common-setting
```
```bash
    /auth/sign-up
```
```bash
    /auth/login
```
```bash
    /auth/verify-email
```
```bash
    /auth/forgot-password
```
```bash
    /auth/reset-password
```
```bash
    /user/profile
```
```bash
    /user/update-profile
```
```bash
    /user/change-password
```
```bash
    /logout
```