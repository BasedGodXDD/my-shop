# my-shop
Описание сайта:
Сайт представляет собой интернет-магазин, где пользователи могут просматривать и покупать товары из трех основных категорий: электроника, книги и одежда. На сайте реализованы следующие функции:

Добавление и удаление товаров из корзины: Пользователь может добавлять понравившиеся товары в корзину для дальнейшего оформления заказа или удалять их, если передумал.
Фильтрация товаров: Доступен фильтр, позволяющий искать товары по их категориям (например, электроника, книги, одежда) и по названиям. Это упрощает навигацию и поиск нужных товаров.
Удобный интерфейс: Сайт имеет простой и интуитивно понятный интерфейс, что делает процесс покупок комфортным.
Руководство по запуску:
Подготовка проекта:

Убедитесь, что у вас установлены Node.js и npm.
Скачайте проект и перейдите в его директорию через командную строку.
дальше вам необходимо установить все зависимости.Клонируйте репозиторий. - git clone https://github.com/Zilebibka/my-shop/edit/main
далее перейдите в каталог проекта.
установите сами зависимости. - npm install; npm start
Запуск локального сервера с данными:

В командной строке выполните команду:
json-server --watch public/data.json --port 3001
Это запустит сервер, который будет предоставлять данные о товарах (например, названия, цены, категории) на локальном хосте http://localhost:3001.
Запуск сайта:

Откройте вторую командную строку (не закрывая первую) и выполните команду:
npm run dev
Это запустит фронтенд-часть сайта на локальном хосте http://localhost:5173.
Использование сайта:

Перейдите в браузере по адресу http://localhost:5173.
На главной странице вы увидите список товаров, которые можно фильтровать по категориям или искать по названиям.
Добавляйте товары в корзину, удаляйте их при необходимости и наслаждайтесь удобством интернет-магазина.
Примечание:
Убедитесь, что порты 3001 и 5173 не заняты другими процессами.
Если данные не подгружаются, проверьте, что сервер с данными (json-server) запущен и доступен
