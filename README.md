1. `python -m venv .venv`
2. `source .venv/bin/activate`
3. `pip install -r requirements.txt`
4. `cp .env.example .env`
5. `uvicorn backend.main:app --reload --port 8000`
6. `cd frontend && npm install && npm run dev`
7. Open `http://localhost:5173`