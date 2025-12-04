<h1 align="center">Привет 👋, меня зовут Лев</h1>
<h3 align="center">Python Backend-разработчик</h3>

### 👨‍💻 Обо мне

- Завершил 14-месячный курс "Python-разработчик" в Яндекс Практикуме
- Высшее образование: бакалавриат + магистратура "Математика и компьютерные науки"
- Ищу свою первую работу в качестве Python Backend-разработчика

### 🛠️ Стек

**Backend-фреймворки:**

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/DRF-ff1709?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Базы данных и ORM:**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-100000?style=for-the-badge&logo=sqlalchemy&logoColor=white)

**Инфраструктура и DevOps:**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Инструменты и экосистема:**

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Дополнительно:**

![APScheduler](https://img.shields.io/badge/APScheduler-1A1A1A?style=for-the-badge&logoColor=white)
![Selenium](https://img.shields.io/badge/-selenium-%2343B02A?style=for-the-badge&logo=selenium&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)


---
### 🚀 Мои основные проекты

#### **Review Parser & Widget — парсер отзывов + виджет** | [Код](https://github.com/al3eon/review-parser-widget)
Сервис для парсинга отзывов из ВКонтакте и Яндекс.Карт с REST API и встраиваемым web‑виджетом для сайтов.  
Продакшн‑готовое решение: сбор отзывов по расписанию, хранение, API и фронтовый виджет для отображения.

**Основное:**
- парсинг отзывов (Selenium)
- планировщик: ночной сбор + резервные копии БД
- REST API для отзывов и статистики
- встраиваемый виджет на Web Components (адаптивный дизайн)

**DevOps:**
- Docker + docker compose (prod и dev окружения)
- Nginx reverse‑proxy + HTTPS (Let’s Encrypt)
- CI/CD на GitHub Actions: тесты → сборка образов → деплой на сервер → нотификации в Telegram

**Стек:** Python, FastAPI, SQLAlchemy, SQLite, Selenium, Docker, Nginx, GitHub Actions

---
#### **Foodgram — сервис рецептов с API** | [Код](https://github.com/al3eon/foodgram) 
Платформа для публикации рецептов с избранным, подписками и корзиной покупок.  
Полностью разработал backend и собрал production-инфраструктуру.

**Основное:**
- Django REST API
- модели, сериализаторы, permissions
- избранное, подписки, корзина, генерация списка покупок
- оптимизация запросов

**DevOps:**
- Docker + docker-compose
- Nginx reverse-proxy
- CI/CD на GitHub Actions (линтеры → сборка образов → деплой → миграции)

**Стек:** Django, DRF, PostgreSQL, Docker, Nginx, GitHub Actions

---
#### **API Yamdb — система отзывов и рейтингов** | [Код](https://github.com/al3eon/api_yamdb)
Платформа с рецензиями на произведения: фильмы, книги и музыку.

**Роль:** Тимлид в команде из 3 разработчиков  
**Основное:**
- построение API: категории, жанры, произведения, отзывы, комментарии
- ролевая модель доступа (user, moderator, admin)
- регистрация через email + confirmation_code → JWT
- каскадное удаление связанных сущностей
- загрузка и очистка данных из CSV (Users, Titles, Genres и др.)

**Стек:** Django REST Framework, JWT, PostgreSQL

---
#### **QRKot — благотворительный фонд на FastAPI** | [Код](https://github.com/al3eon/cat_charity_fund)
API для управления пожертвованиями и проектами фонда.  
Пожертвования автоматически распределяются по открытым проектам по принципу **FIFO**.

**Основное:**
- асинхронный FastAPI + SQLAlchemy 1.4
- модели, CRUD-слой, схемы на Pydantic
- ролевая модель + JWT-аутентификация (FastAPI Users)
- инвестиционная логика: распределение донатов по проектам
- Alembic-миграции
- валидаторы, проверки прав, обработка ошибок

**Интеграция с Google:**
- экспорт данных фонда в Google Sheets
- загрузка отчётов в Google Drive
- автоматический отчёт по закрытым проектам (сортировка по скорости сбора)

**Стек:** FastAPI, SQLAlchemy, Pydantic, Alembic, FastAPI Users, aiogoogle

---
#### **Fake Data API — генератор синтетических данных** | [Код](https://github.com/al3eon/fake-data-api)
Высокопроизводительный генератор до 2.5 млн строк реалистичных данных с веб-интерфейсом.

**Основное:**
- генерация данных в форматах CSV, TXT, XLSX
- упаковка в ZIP/7z архивы
- автоматическая очистка временных файлов
- веб-интерфейс и API
- архитектура на основе паттернов (Фабрика, Стратегия) для легкого расширения

**Стек:** FastAPI, Pydantic, Mimesis, OpenPyXL, py7zr, паттерны проектирования


---
#### **Blogicum** | [Код](https://github.com/al3eon/blogicum)
Cоциальная сеть: публикации, категории, профили и комментарии.

**Основное:**
- архитектура приложения, модели, ORM
- просмотр, создание, редактирование и удаление постов
- регистрация, авторизация, профили пользователей
- отложенные публикации, изображения, пагинация
- система комментариев и проверка прав
- кастомные страницы ошибок и навигация

**Стек:** Django, Bootstrap, SQLite

---
### 📫 Связь со мной

- **Telegram:** [@alieeon](https://t.me/alieeon)
- **Email:** [al3eon@yandex.ru](mailto:al3eon@yandex.ru)
- **GitHub:** [al3eon](https://github.com/al3eon)
