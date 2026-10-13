# Docker Compose UI

Docker Compose UI is a lightweight web interface and HTTP API on top of Docker Compose. It keeps compatibility with the Docker Compose CLI and can run as a single container without a separate database.

## Architecture / Архитектура

```text
Browser -> Docker Compose UI HTTP service -> docker-compose CLI -> Docker Engine -> application containers
```

## Project structure / Структура проекта

- `static/` — web assets
- `demo-projects/` — example Compose projects
- `screenshots/` — UI captures
- application code — HTTP API and Docker Compose integration

## Contact / Контакты

- Email: feudor.lab@yandex.ru
- Telegram: @Feudorlab1
