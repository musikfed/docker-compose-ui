# Docker Compose UI

Docker Compose UI, Docker Compose के ऊपर एक हल्का वेब इंटरफ़ेस और HTTP API है। यह Docker Compose CLI के साथ संगत रहता है और अलग डेटाबेस के बिना एक कंटेनर में चल सकता है।

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
