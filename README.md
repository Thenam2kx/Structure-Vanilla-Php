# Structure-Vanilla-Php

## Clone code
```
git clone https://github.com/Thenam2kx/Structure-Vanilla-Php.git

```


## Cài đặt frontend

```
1. cd Frontend
2. yarn
3. yarn dev
4. truy cập (http://localhost:3000)
```

## Cài đặt backend

```
1. cd Backend
2. composer install
3. php -S localhost:8000 -t backend
4. truy cập (http://localhost:8000)

```

Structure-Vanilla-Php/
│
├── node_modules/
├── frontend/
│   ├── public/
│   │   ├── images/
│   │   ├── index.html
│   │   ├── product.html
│   │   ├── cart.html
│   │   └── checkout.html
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── main.js
│   │   ├── style.css
│   ├── .gitignore
│   ├── .prettierrc
│   ├── index.html
│   ├── jsconfig.json
│   ├── package.json
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── vite.config.js
│   ├── yarn.lock
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   │   ├── ProductController.php
│   │   │   ├── CartController.php
│   │   │   └── UserController.php
│   │   ├── models/
│   │   │   ├── ProductModel.php
│   │   │   ├── CartModel.php
│   │   │   └── UserModel.php
│   │   ├── views/
│   │   │   ├── home.php
│   │   │   ├── product.php
│   │   │   ├── cart.php
│   │   │   └── checkout.php
│   │   └── index.php
│   ├── vendor/
│   │   └── autoload.php
│   ├── .htaccess
│   ├── composer.json
│   ├── index.php