# DataPulse - AI Business Analytics Platform
Built for HackIndia Spark 7 North Region by **Prime Makers**.

## Overview
DataPulse is an AI-powered business analytics platform designed for small-to-medium businesses (SMBs). It provides real-time dashboard analytics, CSV data ingestion, and a conversational AI assistant that understands your actual sales data.

## Features
- **Real-time Analytics Dashboard:** Interactive KPI cards and Recharts-based visualisations.
- **AI Chatbot:** Ask questions about your revenue, sales, and products (powered by Mistral AI / Claude).
- **CSV Ingestion Engine:** Upload your raw `sales.csv` and get instant aggregated dashboards.
- **Anomaly Detection & Forecasting:** Advanced Python-backed machine learning.

## Tech Stack
- **Frontend:** React (Vite), Tailwind CSS, Zustand, Recharts
- **Backend API:** Node.js, Express
- **AI Service:** Python, FastAPI, Pandas, scikit-learn, Mistral AI / Anthropic
- **Database:** PostgreSQL (via Prisma)
- **Containerisation:** Docker & Docker Compose

## Quick Start (Docker)
```bash
cd datapulse
docker-compose up --build
```
- Frontend: `http://localhost:5173`
- Node API: `http://localhost:3001`
- Python AI Service: `http://localhost:8000`

## Quick Start (Manual)
1. Frontend:
   `cd datapulse/frontend && npm install && npm run dev`
2. AI Service:
   `cd datapulse/ai-service && python3 -m venv venv && source venv/bin/activate && pip install -r requirements.txt && python main.py`
