# Структура проекта под SPA React

src/
│
├── styles/
│ ├── vars.scss # Переменные SASS
│ ├── global.scss # Глобальные стили (сброс, шрифты, общие стили)
│ ├── components/ # Стили для компонентов
│ │ ├── \_header.scss # Стили для Header
│ │ ├── \_footer.scss # Стили для Footer
│ │ └── \_buttons.scss # Стили для кнопок (если есть)
│ ├── pages/ # Стили для страниц
│ │ ├── \_index.scss # Стили для главной страницы
│ │ ├── \_catalog.scss # Стили для каталога
│ │ ├── \_product.scss # Стили для страницы продукта
│ │ ├── \_cart.scss # Стили для корзины
│ │ └── \_registration.scss # Стили для регистрации
│ └── main.scss # Главный файл, который импортирует все стили
│
└── index.html # HTML-файл
