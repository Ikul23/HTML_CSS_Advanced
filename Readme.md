# Структура проекта магазина под переход на SPA React

│project/

├── public/
│ ├── index.html # Главная страница

│ ├── product.html # Страница продукта

│ ├── catalog.html # Страница каталога продуктов

│ ├── cart.html # Страница корзины

│ ├── cregitration.html # Страница регистрации

│ ├── assets/
│ │ └── images/ # Изображения

├── src/

│ ├── styles/ # SCSS и скомпилированные CSS

│ │ ├── main.scss # Главный файл SCSS

│ │ ├── main.css # Скомпилированный CSS

│ │ ├── global.scss # Глобальные стили

│ │ ├── components/ # Стили для компонентов
│ │ │ ├── \_header.scss
│ │ │ ├── \_footer.scss
│ │ │ └── \_buttons.scss
│ │ │ └── \_features.scss
│ │ │ └── \_filter-sort.scss
│ │ │ └── \_pagination.scss

│ │ └── pages/ # Стили для страниц
│ │ ├── \_index.scss
│ │ ├── \_catalog.scss
│ │ ├── \_product.scss
│ │ ├── \_cart.scss
│ │ └── \_registration.scss
