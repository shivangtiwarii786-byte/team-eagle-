# 🌍 BreatheGrid

Hyperlocal air intelligence and heat-risk forecasting.

## 🚀 Quick Start

### Option 1 — Docker
```bash
docker compose up --build
```

Open:
- Frontend: http://localhost:3000
- API: http://localhost:8000/docs

### Option 2 — Run manually

Backend:
```bash
cd backend
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Frontend:
```bash
cd frontend
npm install
npm run dev
```

Then open http://localhost:3000.

## ✨ Starter Features

- Live-style sample AQI dashboard
- PM2.5, ozone and temperature indicators
- 72-hour forecast preview
- Compound risk score
- Health guidance
- FastAPI JSON endpoints
- Docker Compose setup

> This starter uses sample data. It does not claim to provide real-time public-health forecasts until real data sources and a validated ML model are connected.
