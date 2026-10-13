# Docker Compose UI

Docker Compose UI нь Docker Compose дээр ажиллах хөнгөн веб интерфейс болон HTTP API юм. Docker Compose CLI-тэй нийцтэй бөгөөд тусдаа өгөгдлийн сангүй нэг контейнерээр ажиллаж чадна.

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
