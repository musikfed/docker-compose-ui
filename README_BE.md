# Docker Compose UI

Docker Compose UI — лёгкі вэб-інтэрфейс і HTTP API над Docker Compose. Ён сумяшчальны з Docker Compose CLI і можа працаваць адным кантэйнерам без асобнай базы даных.

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
