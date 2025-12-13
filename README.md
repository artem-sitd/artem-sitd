## 🧑‍💻 Обо мне

Привет! Я Python backend-разработчик, специализирующийся на создании надёжных, масштабируемых и поддерживаемых систем. В своей работе я делаю упор на архитектуру, чистый код, документацию и автоматизацию. Умею выстраивать эффективный backend: от проектирования базы данных и бизнес-логики до CI/CD, деплоя и мониторинга в проде.

---

## 🛠️ Стек технологий

### Backend
- **Python 3.** — основной язык
- **Django / DRF**, **FastAPI**, **Flask**
- **Celery** (Redis, RabbitMQ), **WebSockets**
- **REST API**, **OpenAPI / Swagger**, **OAuth2 / JWT**
- **Асинхронность** — `asyncio`, `httpx`, `aiogram`

### DevOps / CI/CD
- **Docker**, Docker Compose
- **Git**, GitHub / GitLab, **GitLab CI/CD**
- **Makefile**, bash-скрипты
- **Nginx**, systemd
- Управление окружениями: venv, pipenv, poetry

### Базы данных / кэш / брокеры
- **PostgreSQL** (включая индексацию, транзакции, SQL-оптимизацию)
- **MongoDB** (в т.ч. для логов и истории изменений)
- **Redis** (брокер, кэш, rate limit)

### Тестирование и качество кода
- **Pytest**, **UnitTest**
- Покрытие: `coverage`
- Линтинг и автоформатирование: `flake8`, `black`, `isort`
- Pre-commit хуки

### Документация и API
- Markdown, reStructuredText
- Swagger / drf-yasg
- Автогенерация документации, changelog

### Фронтенд (базово)
- HTML / CSS / Bootstrap
- React (на уровне API-интеграций)
- Redux DevTools

### Дополнительно
- Linux / Windows (рабочие окружения, shell-скрипты)
- Логирование (`logging`, Sentry, Promtail)
- cron, Celery beat
- Интеграции: платёжки, SMS, внешние API

---

## 🚀 Проекты

- [**collage_photo**](https://github.com/artem-sitd/collage_photo) — генерация фото-коллажей с возможностью настройки сетки и размеров.
  <ins>Стэк: Python 3.10, Pillow (PIL).</ins>

- [**CRM**](https://github.com/artem-sitd/CRM) — полнофункциональная CRM-система: Django, Celery, Redis, PostgreSQL, рассылки, задачи.
<ins>Стэк: Python 3.10, Django, PostgreSQL, Celery, Redis, Docker & Docker Compose. </ins>


- [**Data_Uploader**](https://github.com/artem-sitd/Data_Uploader) — загрузка, хранение и анализ Excel/CSV-файлов. Включён анализ пиков и визуализация.
<ins>Стэк: Python 3.10, Flask, PostgreSQL, SQLAlchemy. </ins>


- [**image-processing-api**](https://github.com/artem-sitd/image-processing-api) — FastAPI-сервис для обработки изображений (ресайз, поворот, фильтры, base64).
<ins>Стэк: Python 3.10+, FastAPI, PostgreSQL, MinIO (S3), Alembic, Poetry, Docker & Docker Compose. </ins>


- [**link-shortener**](https://github.com/artem-sitd/link-shortener) — Telegram-бот для сокращения ссылок с хранением в MongoDB и историей переходов.
<ins>Стэк: Python 3.10+, FastAPI, aiogram, Nginx, Docker & Docker Compose. </ins>


- [**memes_api**](https://github.com/artem-sitd/memes_api) — API для хранения и выдачи мемов. Загрузка в S3, поиск, фильтрация.
<ins>Стэк: Python 3.10+, FastAPI, SQLAlchemy, PostgreSQL, MinIO (S3), Alembic (миграции), Pytest, Docker & Docker Compose. </ins>


- [**notice_f**](https://github.com/artem-sitd/notice_f) — бот-уведомлятор на Django + Aiogram. Рассылка по дате, задачи через Celery.
<ins>Стэк: Python 3.10+, Django 4.x, Django REST Framework, PostgreSQL, Celery, Redis, Gunicorn, Docker & Docker Compose.</ins>
 

- [**request_rate_limit**](https://github.com/artem-sitd/request_rate_limit) — реализация лимитирования запросов через FastAPI и Redis.
<ins>Стэк: Python 3.10+, Flask, Redis, python-dotenv, unittest, Docker & Docker Compose. </ins>


- [**salary_aggregate_bot**](https://github.com/artem-sitd/salary_aggregate_bot) — агрегатор зарплат с MongoDB, фильтрацией и Telegram-интерфейсом.
<ins>Стэк: Python 3.10+, FastAPI, aiogram, MongoDB, Docker & Docker Compose, pytest. </ins>


- [**ServicesStatusFastapi**](https://github.com/artem-sitd/ServicesStatusFastapi) — FastAPI-сервис мониторинга состояния внешних/внутренних API.
<ins>Стэк: Python 3.10+, FastAPI, PostgreSQL, Alembic, Docker & Docker Compose. </ins>
  

- [**synchron**](https://github.com/artem-sitd/synchron) — Утилита синхронизации между локальной директорией и облачным хранилищем Яндекс.Диск. Поддерживает автоматическое обновление, удаление и загрузку файлов на основе сравнения имен и хэшей.
<ins>Стэк: python, requests, yandex api. </ins>


- [**todo_TG_bot**](https://github.com/artem-sitd/todo_TG_bot) — Telegram-бот для создания и управления задачами. Django + Aiogram + Celery.
<ins>Стэк: Python 3.10+, aiogram, PostgreSQL, Celery, Redis, Docker & Docker Compose.</ins>

  
- **API_HH (private) — Python-инструмент автоматизации работы с API HH.ru**  Скрипт для поиска и автоматического отклика на вакансии через HeadHunter API, использует OAuth2, REST-запросы и обработку JSON-ответов. Практическая интеграция с внешними API и автоматизации HR-процесса.
<ins>Стэк: python, requests, api hh.ru (на декабрь 2025 hh прекратил поддержку апи). </ins>

- [**Flaskter**](https://github.com/artem-sitd/Flaskter) - Flaskter — это минималистичное Flask-приложение (Сервис микроблогов), демонстрирующее архитектуру с вынесенной бизнес-логикой и модульной структурой. 
В проекте реализованы авторизация, работа с базой данных и REST-эндпоинты. Используются шаблоны, Blueprints и разделение слоёв для удобства масштабирования. 
Репозиторий служит базой для разработки более сложных backend-сервисов на Flask.
<ins>Стэк: python, gunicorn, flask-restful, sqlalchemy, pytest, alembic, pytest, requests. </ins>


- [**telebot_hotel**](https://github.com/artem-sitd/telebot_hotel) Telegram-бот на Python с использованием Telebot и ORM Peewee для поиска и сортировки отелей (через АПИ rapidapi) по разным критериям (цена, расстояние от центра), с историей запросов и базой данных.
<ins>Стэк: python, peewee, pyTelegramBotAPI, requests. </ins>


- [**online_store**](https://github.com/artem-sitd/online_store_meg) Интернет-магазин с backend на Django REST Framework и SQLite, реализующий каталог, корзину, заказ и оплату, а также профили пользователей и фильтрацию товаров под Swagger-документацию.
<ins>Стэк: python, djangorestframework, Pillow, PyJWT, requests. </ins>
  
---

📌 Основные интересы:
- Высоконагруженные API
- Микросервисная архитектура
- Telegram-боты
- Интеграции с внешними сервисами
- Docker-окружения и деплой
- Производительность, кэширование, логирование

---

## 📈 GitHub Статистика

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=artem-sitd&show_icons=true&theme=default)
