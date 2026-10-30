[English](README.md) | **Русский**

# Данил Мифтахов

**Python Backend Developer | PostgreSQL и обработка данных**

Я Python-разработчик с более чем четырьмя годами коммерческого опыта в обработке данных, автоматизации и интеграции API. Мои основные направления — Python, PostgreSQL/PostGIS, SQL и асинхронная обработка данных.

Разрабатываю backend-приложения на FastAPI, SQLAlchemy и PostgreSQL, а также инфраструктуру для своих проектов: подготовку Ubuntu-серверов, упаковку в Docker, CI/CD и HTTPS-маршрутизацию.

**[Моё портфолио → danil-miftakhov.dev](https://danil-miftakhov.dev/ru/)**

Проекты, инженерные решения, резюме на русском и английском языках и контакты.

📍 Ереван, Армения · 🟢 Рассматриваю удалённую работу Python Backend Developer

## Обо мне

- **Коммерческий опыт:** разрабатываю и поддерживаю Python-инструменты для обработки геоданных, интеграции внешних API и автоматизации внутренних процессов.
- **Обработка больших объёмов данных:** разработал Python-инструмент, который обработал **46 миллионов адресных записей за один запуск** примерно за **6–8 часов**, используя пакетные и параллельные операции с PostgreSQL.
- **Работа с базами данных:** использую PostgreSQL/PostGIS, оптимизацию SQL, asyncio, psycopg и SQLAlchemy. Разрабатывал переиспользуемые инструменты для работы с БД и настраиваемые процессы обработки данных.
- **Backend-разработка:** создаю REST API на FastAPI, SQLAlchemy, Alembic и Pydantic. В проектах портфолио отрабатываю архитектуру backend-приложений, бизнес-логику, транзакции и автоматизированное тестирование.
- **Инфраструктура и доставка приложений:** разрабатываю подготовку Ubuntu VPS на Ansible и платформу деплоя на Python с неизменяемыми Docker-образами, проверкой подписанных релизов, проверками готовности, HTTPS-маршрутизацией через Caddy и контролируемым восстановлением.
- **Качество:** проверяю API и бизнес-логику, пользовательские сценарии и обработку инфраструктурных сбоев с помощью модульных, интеграционных, браузерных тестов и тестов в изолированных виртуальных машинах.

Бакалавр по направлению «Прикладная математика и информатика», Казанский федеральный университет.

## Избранные проекты

| Проект | Описание | Стек |
| --- | --- | --- |
| [**Portfolio Deployment**](https://github.com/DanilFaritovich/portfolio-deployment) | Платформа деплоя Docker-приложений на одном VPS: планирование без обращения к серверу, проверка подписанных релизов, неизменяемые образы, проверки готовности перед активацией, общая HTTPS-маршрутизация и восстановление с журналом операций. | Python, Docker Compose, Caddy, SQLite, GitHub Actions, GHCR |
| [**ProjectRouter — сайт-портфолио**](https://github.com/DanilFaritovich/project-router) | [Мой сайт](https://danil-miftakhov.dev/ru/) со страницами на русском и английском языках, каталогом проектов, встроенным просмотром PDF-резюме, предварительной генерацией HTML, браузерными тестами и проверками доступности интерфейса. | Vue 3, TypeScript, Vite SSG, Tailwind CSS, PDF.js, Playwright |
| [**Portfolio Server Infrastructure**](https://github.com/DanilFaritovich/portfolio-server-infrastructure) | Пошаговая подготовка Ubuntu VPS с независимыми проверками доступа, настройкой безопасности SSH/UFW, Docker, управлением пользователями, политиками обслуживания системы и E2E-сценариями в изолированных виртуальных машинах. | Python, Ansible, Ubuntu, Docker, SSH/UFW, GitHub Actions |
| [**Moon Courier Crisis**](https://github.com/DanilFaritovich/Moon-courier-crisis-game) | Логистическая симуляция с REST API на FastAPI, доменными сервисами, расчётом маршрутов, репозиториями SQLAlchemy, автоматизированными тестами и веб-интерфейсом. | Python, FastAPI, SQLAlchemy, Vue 3, Docker |
| [**Yandex Geocoder Region Parser**](https://github.com/DanilFaritovich/yandex-geocoder-region-parser) | ETL-пайплайн для геоданных с оркестрацией обработки через Airflow, интеграцией внешнего API, PostgreSQL, S3-совместимым хранилищем и автоматизированными тестами. | Python, Airflow, PostgreSQL, MinIO/S3, Docker |
| [**MaximML**](https://github.com/DanilFaritovich/maxim-ml) | Full-stack приложение для прогнозирования цен на жильё, обучения моделей и получения предсказаний с использованием сохранённых пайплайнов scikit-learn. | Python, FastAPI, scikit-learn, React, Docker |
| [**Task Service API**](https://github.com/DanilFaritovich/task-service-api) | REST API с хранением данных в БД, миграциями, сервисным слоем и автоматизированными тестами. | Python, FastAPI, PostgreSQL, SQLAlchemy, Alembic |

За сайт и его инфраструктуру отвечают три отдельных репозитория: **ProjectRouter** — за приложение сайта, **Portfolio Server Infrastructure** — за подготовку сервера, **Portfolio Deployment** — за доставку приложений и маршрутизацию.

## Инструменты для разработки

- [**Codex Development Standards**](https://github.com/DanilFaritovich/codex-development-standards) — переиспользуемые рабочие процессы и соглашения для разработки, тестирования, архитектуры и CI/CD с учётом технологического стека.
- [**Codex Free Worker**](https://github.com/DanilFaritovich/codex-free-worker-mcp) — локальный MCP-мост для передачи OpenCode ограниченных задач по анализу и выполнению команд с возвратом кратких результатов.

## Технологический стек

| Направление | Технологии |
| --- | --- |
| Backend | Python, FastAPI, SQLAlchemy, Pydantic, asyncio, aiohttp |
| Базы данных и обработка данных | PostgreSQL, PostGIS, SQL, psycopg, Apache Airflow, MinIO/S3, pandas |
| Frontend | Vue 3, TypeScript, Vite, Tailwind CSS |
| Тестирование и качество | Pytest, Ruff, Mypy, Vitest, Playwright, GitHub Actions |
| Инфраструктура и доставка приложений | Ansible, Docker, Docker Compose, Linux, Bash, SSH/UFW, Caddy, Nginx, GHCR |
| Интеграция ML | scikit-learn, обучение моделей, пайплайны предобработки, API для получения предсказаний |

## Контакты

[Портфолио](https://danil-miftakhov.dev/ru/) · [LinkedIn](https://www.linkedin.com/in/danil-miftakhov-55468b399/) · [Telegram](https://t.me/Daniel_De_Casto) · [Email](mailto:danilfaritovichwork@gmail.com)
