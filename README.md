# Groq Chatbot (React + FastAPI)

## 1. Backend (terminal 1)
    cd backend
    python -m venv venv
    source venv/bin/activate        # Windows: venv\Scripts\activate
    pip install -r requirements.txt
    uvicorn main:app --reload --port 8000

## 2. Frontend (terminal 2)
    cd frontend
    npm install
    npm run dev

Open http://localhost:5173
API key `backend/.env` mein hai (git mein commit mat karna).
