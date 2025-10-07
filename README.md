Лабораторная работа №2.

👨‍💻 Автор
ФИО: Есева Виктория Евгеньевна
Группа: 3МО-2 🎓

🎯 Цель работы

Научиться конфигурировать веб-сервер Nginx для работы с PHP через PHP-FPM.
Освоить базовые принципы PHP (на примере phpinfo()).
Повторить основы HTML: работа с формами, различными типами полей ввода.
Освоить базовую обработку форм с помощью JavaScript без перезагрузки страницы.


🚀 Запуск проекта
# Перейти в папку lab2
cd lab2

# Запустить контейнеры
docker-compose up -d --build

🌐 Доступные страницы

PHP: http://localhost:8080/index.php

Форма заявки в библиотеку: http://localhost:8080/form.html

📁 Структура проекта
lab2/
├── docker-compose.yml         # Конфигурация Docker
├── nginx/                     
│   └── default.conf           # Конфигурация Nginx
├── www/
│   ├── index.php              # PHP info страница
│   ├── form.html              # Форма заявки
│   └── js/
│       └── script.js          # JS для обработки формы
├── screenshots/               # Скриншоты работы
│   ├── PHP.png
│   └── form.png
└── README.md                  # Документация

📸 Скриншоты работы

Страница PHP
<img width="1725" height="978" alt="image" src="https://github.com/user-attachments/assets/68b29bd5-5fa3-466a-9d70-849a0d1cd6af" />


🎬 Форма заявки в библиотеку
<img width="1321" height="870" alt="image" src="https://github.com/user-attachments/assets/03edef23-c54b-4902-9b34-77ac1add4227" />


Форма включает:

👤 Имя пользователя (text)

🎟️ Номер билета (number)

📚 Жанр книги (select)

🗓️ Срок аренды (radio buttons)

💻 Электронная версия (checkbox)

📝 Обработка на JavaScript без перезагрузки страницы


✅ Результат

Веб-сервер успешно настроен для работы с PHP через PHP-FPM.

Реализована интерактивная HTML-форма с обработкой на JavaScript

Данные из формы отображаются под формой без перезагрузки страницы
