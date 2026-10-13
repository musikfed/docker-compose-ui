# Docker Compose UI

Docker Compose UI 是构建在 Docker Compose 之上的轻量 Web 界面和 HTTP API，保持与 Docker Compose CLI 的兼容，并可作为单个容器运行，无需独立数据库。

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
