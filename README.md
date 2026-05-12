<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=500&color=2B7BE4&center=true&vCenter=true&width=600&lines=Artem+Sitdikov;Python+Backend+Developer;FastAPI+%2F+Django+%2F+Async+Systems" alt="Header" />
</p>

<p align="center">
  <a href="https://github.com/artem-sitd"><img src="https://img.shields.io/badge/GitHub-artem--sitd-2B7BE4?logo=github" /></a>
  <a href="https://pypi.org/project/fastapi-arq/"><img src="https://img.shields.io/badge/PyPI-fastapi--arq-2B7BE4?logo=pypi" /></a>
  <img src="https://img.shields.io/badge/Python-3.11%2B-2B7BE4?logo=python" />
  <img src="https://img.shields.io/badge/FastAPI-0.111%2B-2B7BE4?logo=fastapi" />
</p>

---

## 🇷🇺 Привет! / 🇬🇧 Hello!

**RU:** Python backend-разработчик. Специализируюсь на надёжных, масштабируемых системах: от проектирования БД и бизнес-логики до CI/CD, деплоя и мониторинга. Убеждённый сторонник чистой архитектуры, документации как части кода и автоматизации всего, что автоматизируется.

**EN:** Python backend engineer focused on reliable, scalable systems — from database design and business logic to CI/CD, deployment, and monitoring. I believe in clean architecture, docs-as-code, and automating everything automatable.

---

## 🚀 Featured Project

<p align="center">
  <a href="https://github.com/artem-sitd/fastapi-arq">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=artem-sitd&repo=fastapi-arq&theme=default&border_color=2B7BE4" />
  </a>
</p>

**fastapi-arq** — декоратор-обёртка, интегрирующая arq (async Redis queue) в FastAPI без boilerplate. Первая опубликованная библиотека на PyPI.

**fastapi-arq** — a decorator-style wrapper that integrates arq (async Redis queue) into FastAPI without boilerplate. My first PyPI package.

```python
from fastapi_arq import FastArq

arq = FastArq(app, "redis://localhost:6379")

@arq.task(max_tries=3)
async def send_email(ctx: dict, user_id: int): ...
```

---

## 🛠️ Tech Stack

<table>
  <tr>
    <th colspan="2" align="center">Backend</th>
  </tr>
  <tr>
    <td width="120"><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3.11%2B-3776AB?logo=python" />
    </td>
  </tr>
  <tr>
    <td><b>Frameworks</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-0.111%2B-009688?logo=fastapi" />
      <img src="https://img.shields.io/badge/Django-5.x-092E20?logo=django" />
      <img src="https://img.shields.io/badge/DRF-black?logo=django" />
      <img src="https://img.shields.io/badge/Flask-black?logo=flask" />
      <img src="https://img.shields.io/badge/aiohttp-black?logo=aiohttp" />
    </td>
  </tr>
  <tr>
    <td><b>Async</b></td>
    <td>
      <img src="https://img.shields.io/badge/asyncio-3776AB?logo=python" />
      <img src="https://img.shields.io/badge/Celery-37814A?logo=celery" />
      <img src="https://img.shields.io/badge/ARQ-2B7BE4?logo=redis" />
      <img src="https://img.shields.io/badge/aiogram-2CA5E0?logo=telegram" />
      <img src="https://img.shields.io/badge/httpx-2B7BE4" />
      <img src="https://img.shields.io/badge/WebSockets-010101" />
    </td>
  </tr>
  <tr>
    <td><b>Databases</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql" />
      <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb" />
      <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis" />
      <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite" />
    </td>
  </tr>
  <tr>
    <td><b>ORM</b></td>
    <td>
      <img src="https://img.shields.io/badge/SQLAlchemy-2.x-D71F00?logo=sqlalchemy" />
      <img src="https://img.shields.io/badge/Django_ORM-092E20?logo=django" />
      <img src="https://img.shields.io/badge/Peewee-2B7BE4" />
      <img src="https://img.shields.io/badge/Alembic-2B7BE4" />
    </td>
  </tr>
  <tr>
    <th colspan="2" align="center">DevOps & Tooling</th>
  </tr>
  <tr>
    <td><b>Infra</b></td>
    <td>
      <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker" />
      <img src="https://img.shields.io/badge/Docker_Compose-2496ED?logo=docker" />
      <img src="https://img.shields.io/badge/Nginx-009639?logo=nginx" />
      <img src="https://img.shields.io/badge/Gunicorn-499848?logo=gunicorn" />
      <img src="https://img.shields.io/badge/systemd-2B7BE4" />
      <img src="https://img.shields.io/badge/Makefile-2B7BE4" />
    </td>
  </tr>
  <tr>
    <td><b>CI/CD</b></td>
    <td>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions" />
      <img src="https://img.shields.io/badge/GitLab_CI-FC6D26?logo=gitlab" />
      <img src="https://img.shields.io/badge/Jenkins-D24939?logo=jenkins" />
    </td>
  </tr>
  <tr>
    <td><b>Quality</b></td>
    <td>
      <img src="https://img.shields.io/badge/Pytest-0A9EDC?logo=pytest" />
      <img src="https://img.shields.io/badge/mypy-2B7BE4" />
      <img src="https://img.shields.io/badge/ruff-2B7BE4" />
      <img src="https://img.shields.io/badge/Pre--commit-FAB040?logo=precommit" />
      <img src="https://img.shields.io/badge/Sentry-362D59?logo=sentry" />
    </td>
  </tr>
  <tr>
    <td><b>Auth</b></td>
    <td>
      <img src="https://img.shields.io/badge/OAuth2-2B7BE4" />
      <img src="https://img.shields.io/badge/JWT-2B7BE4" />
      <img src="https://img.shields.io/badge/OpenID-2B7BE4" />
    </td>
  </tr>
</table>

---

## 📦 Projects

<table>
  <tr>
    <th>Project</th>
    <th>Description</th>
    <th>Stack</th>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/fastapi-arq"><b>fastapi-arq</b></a> ⭐</td>
    <td>FastAPI + ARQ без boilerplate. Библиотека на PyPI</td>
    <td>FastAPI, arq, Redis, Pydantic</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/video_bot"><b>video_bot</b></a></td>
    <td>Telegram-бот: вопросы на NL → SQL-агрегации через OpenAI</td>
    <td>aiogram, SQLAlchemy, PostgreSQL, OpenAI</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/CRM"><b>CRM</b></a></td>
    <td>Полнофункциональная CRM: рассылки, задачи, роли</td>
    <td>Django, Celery, Redis, PostgreSQL</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/image-processing-api"><b>image-processing-api</b></a></td>
    <td>Обработка изображений: ресайз, поворот, фильтры</td>
    <td>FastAPI, MinIO (S3), PostgreSQL</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/Flaskter"><b>Flaskter</b></a></td>
    <td>Микроблоги на Flask с чистой архитектурой</td>
    <td>Flask, SQLAlchemy, Alembic, pytest</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/online_store_meg"><b>online_store</b></a></td>
    <td>Интернет-магазин: каталог, корзина, заказ, оплата</td>
    <td>DRF, JWT, Swagger</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/synchron"><b>synchron</b></a></td>
    <td>Синхронизация с Яндекс.Диск (хэши, автообновление)</td>
    <td>Python, requests, Yandex API</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/salary_aggregate_bot"><b>salary_aggregate_bot</b></a></td>
    <td>Агрегатор зарплат + Telegram-интерфейс</td>
    <td>FastAPI, MongoDB, aiogram</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/ServicesStatusFastapi"><b>ServicesStatusFastapi</b></a></td>
    <td>Мониторинг состояния внешних/внутренних API</td>
    <td>FastAPI, PostgreSQL, Alembic</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/memes_api"><b>memes_api</b></a></td>
    <td>API мемов: S3-загрузка, поиск, фильтрация</td>
    <td>FastAPI, MinIO (S3), pytest</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/Data_Uploader"><b>Data_Uploader</b></a></td>
    <td>Загрузка Excel/CSV, анализ пиков, визуализация</td>
    <td>Flask, PostgreSQL, SQLAlchemy</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/link-shortener"><b>link-shortener</b></a></td>
    <td>Telegram-бот для сокращения ссылок</td>
    <td>FastAPI, aiogram, MongoDB</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/notice_f"><b>notice_f</b></a></td>
    <td>Бот-уведомлятор: рассылка по дате, Celery-задачи</td>
    <td>Django, DRF, Celery, Redis</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/request_rate_limit"><b>request_rate_limit</b></a></td>
    <td>Лимитирование запросов через FastAPI + Redis</td>
    <td>Flask, Redis, Docker</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/todo_TG_bot"><b>todo_TG_bot</b></a></td>
    <td>Telegram-бот для управления задачами</td>
    <td>aiogram, Celery, Redis</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/collage_photo"><b>collage_photo</b></a></td>
    <td>Генерация фото-коллажей</td>
    <td>Pillow</td>
  </tr>
  <tr>
    <td><a href="https://github.com/artem-sitd/telebot_hotel"><b>telebot_hotel</b></a></td>
    <td>Поиск отелей через RapidAPI + Telegram</td>
    <td>pyTelegramBotAPI, Peewee</td>
  </tr>
</table>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=artem-sitd&theme=default" width="600" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=artem-sitd&theme=default" height="140" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=artem-sitd&theme=default" height="140" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=artem-sitd&theme=default" height="140" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=artem-sitd&theme=default&utcOffset=3" height="140" />
</p>

---

<p align="center">
  <b>📫 Connect / Связаться</b><br>
  <a href="mailto:betroxqq@gmail.com">artem.sitd@gmail.com</a>
</p>
