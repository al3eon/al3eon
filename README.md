<h1 align="center">Привет 👋, меня зовут Лев</h1>
<h3 align="center">Python Backend-разработчик с математическим бэкграундом</h3>

### 👨‍💻 Обо мне

- 🎓 Завершил 14-месячный курс "Python-разработчик" в Яндекс Практикуме
- 📚 Высшее образование: бакалавриат + магистратура "Математика и компьютерные науки"
- 🔭 Ищу свою первую работу в качестве Python Backend-разработчика

### 🛠️ Стек

#### **Backend-фреймворки:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![Django REST Framework](https://img.shields.io/badge/DRF-ff1709?style=for-the-badge&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

#### **Базы данных и ORM:**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-100000?style=for-the-badge&logo=sqlalchemy&logoColor=white)

#### **Тестирование и инструменты:**
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

#### **Инфраструктура:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)


---
### 🚀 Мои основные проекты

#### **Foodgram — сервис рецептов с API** | [Код](https://github.com/al3eon/foodgram) 
---
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
