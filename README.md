# Entropy Compressor

Веб-сервис сжатия данных с математической оценкой эффективности
(энтропия Шеннона, избыточность, средняя длина кода).

## Стек
- **Backend:** FastAPI, SQLAlchemy, PostgreSQL, MinIO
- **Frontend:** HTML/CSS/JS, Chart.js
- **Infra:** Docker, docker-compose, Kubernetes, GitLab CI/CD
- **Monitoring:** Prometheus, Grafana

## Быстрый старт
```bash
cp backend/.env.example backend/.env
docker compose up --build