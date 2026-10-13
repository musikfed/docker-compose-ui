# Docker Compose UI

Docker Compose UI는 Docker Compose 위에 제공되는 가벼운 웹 인터페이스와 HTTP API입니다. Docker Compose CLI와 호환되며 별도 데이터베이스 없이 단일 컨테이너로 실행할 수 있습니다.

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
