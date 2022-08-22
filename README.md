# goit-js-hw-07

## Задание 1 - галерея изображений

Создай галерею с возможностью клика по её элементам и просмотра полноразмерного изображения в модальном окне. Посмотри демо видео работы галереи.

1. Создание и рендер разметки по массиву данных galleryItems и предоставленному шаблону элемента галереи.
2. Реализация делегирования на `div.gallery` и получение url большого изображения.
3. Подключение скрипта и стилей библиотеки модального окна `basicLightbox.` Используй CDN сервис `jsdelivr` и добавь в проект ссылки на минифицированные `(.min)` файлы библиотеки.
4. Открытие модального окна по клику на элементе галереи. Для этого ознакомься с документацией и примерами.
5. Замена значения атрибута `src` элемента `<img>` в модальном окне перед открытием. Используй готовую разметку модального окна с изображением из примеров библиотеки basicLightbox.

## Разметка элемента галереи

Ссылка на оригинальное изображение должна храниться в data-атрибуте `source` на элементе `<img>`, и указываться в `href` ссылки. Не добавляй другие HTML теги или CSS классы кроме тех, что есть в этом шаблоне.
