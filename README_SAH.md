# Docker Compose UI

Docker Compose UI — Docker Compose үрдүгэр үлэлиир судургутук веб-интерфейс уонна HTTP API. Docker Compose CLI-ны кытта сөп түбэһэр уонна туспа база суох биир контейнерга үлэлиэн сөп.

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
