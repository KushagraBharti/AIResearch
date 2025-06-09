# AIResearch Platform

A collaborative, LLM-powered academic research platform with a visual node-based editor — designed for automating, exploring, and publishing full research projects from a single prompt.

---

## Project Stack

| Layer       | Tech                                     |
|-------------|------------------------------------------|
| Frontend    | React, TypeScript, Vite, Yarn            |
| Backend     | Python, FastAPI, WebSockets              |
| Realtime DB | Supabase (coming soon)                   |
| LLMs        | OpenAI + AWS Bedrock (coming soon        |

---

## Setup & Configuration

### Frontend

```bash
cd frontend
yarn
yarn dev
```

Local Frontend Server will run at http://localhost:5173

### Backend

```bash
cd backend
python -m venv .venv
.venv\Scripts\Activate.ps1
python.exe -m pip install --upgrade pip
pip install "fastapi[standard]"
pip install -r requirements.txt
```

Local Backend Server will run at http://127.0.0.1:8000