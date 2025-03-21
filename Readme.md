# Структура проекта магазина под переход на SPA React

│project/
│
├── public/
│ ├── index.html # Главная страница
│ ├── product.html # Страница продукта
│ ├── assets/
│ │ └── images/ # Изображения
│
├── src/
│ ├── styles/ # SCSS и скомпилированные CSS
│ │ ├── main.scss # Главный файл SCSS
│ │ ├── main.css # Скомпилированный CSS
│ │ ├── global.scss # Глобальные стили
│ │ ├── components/ # Стили для компонентов
│ │ │ ├── \_header.scss
│ │ │ ├── \_footer.scss
│ │ │ └── \_buttons.scss
│ │ └── pages/ # Стили для страниц
│ │ ├── \_index.scss
│ │ ├── \_catalog.scss
│ │ ├── \_product.scss
│ │ ├── \_cart.scss
│ │ └── \_registration.scss
│ └── scripts/ # JS-файлы (если есть)
│
└── package.json # Файл с зависимостями (если используется npm)
