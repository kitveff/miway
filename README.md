# Mi'Way — Вязаные изделия ручной работы

Лендинг для хендмейд-мастера Китаевой Мили. Корзины, домики для питомцев, сумочки, брелки и подарочные наборы — всё ручной работы из Санкт-Петербурга.

## Стек

- Чистый HTML5 + CSS (без фреймворков)
- Google Fonts: Cormorant Garamond, Jost
- Локальный шрифт: Hamilton Signature Cyrillic
- Scroll-анимации через IntersectionObserver
- Адаптивная вёрстка: 375 / 768 / 1280 / 1920px

## Структура проекта

```
MiWay/
├── index.html            # Основной файл сайта
├── fonts/                # Локальные шрифты
├── author_photo/         # Фото автора
├── baskets_photo/        # Фото корзин
├── colors_photo/         # Фото цветов/пряжи
├── instruments_photo/    # Фото инструментов
├── pet_house_image/      # Фото домиков для питомцев
└── working_video/        # Видео процесса работы
```

## Запуск

Откройте `index.html` в браузере или используйте любой статический сервер:

```bash
# Python
python3 -m http.server 8080

# Node.js (npx)
npx serve .
```

## Деплой

Сайт — статический, подходит для:

- [GitHub Pages](https://pages.github.com)
- [Netlify](https://netlify.com) (drag & drop папки)
- [Vercel](https://vercel.com)
