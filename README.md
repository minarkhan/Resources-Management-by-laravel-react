# Quickstart

### 1. Clone Repository
```sh
$ git clone https://github.com/minarkhan/Resources-Management-by-laravel-react.git
```

### 2. BackEnd Installation
```sh
$ cd BackEnd
$ composer install
or
$ composer update
```

### 3. Environment Setup
```sh
$ clone .env.example as .env
$ DB_DATABASE=(db_name)
```

### 4. Run BackEnd
```sh
$ php artisan key:generate
$ php artisan migrate
$ php artisan storage:link
$ php artisan serve
$ Open http://localhost:8000/api as API URL
```

### 5. FrontEnd Installation
```sh
$ cd ../
$ cd FrontEnd
$ npm install
```

### 6. Run FrontEnd
```sh
$ npm start
$ open http://localhost:3000
```
### Note : 
```sh
$ If Uploaded file not showing... than
$ Delete Storage folder from /Public folder & Run cli:
$ php artisan storage:link
```
# Happy Coding...


