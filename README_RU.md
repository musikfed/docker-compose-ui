# Docker Compose UI

Docker Compose UI — лёгкий веб-интерфейс и HTTP API поверх Docker Compose. Он сохраняет совместимость с CLI Docker Compose и может работать одним контейнером без отдельной базы данных.

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
