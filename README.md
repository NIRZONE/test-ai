# AI Coding Chatbot

A full-stack AI chatbot web app for code generation and general chat, using OpenAI GPT-3.5 Turbo via FastAPI backend and a minimal HTML/JS frontend.

---

## Features

- Chat and code generation (like ChatGPT/Copilot)
- Works for coding and general Q&A
- Easily extendable

---

## Setup

### 1. Backend

```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows, use venv\Scripts\activate
pip install -r requirements.txt
# Place your OpenAI API key in a file named .env (see .env file for format)
uvicorn main:app --reload
```

### 2. Frontend

Open `frontend/index.html` in your browser.  
If your backend is on a remote server, update the `apiUrl` in the HTML accordingly.

---

## Data Collection

To collect data for fine-tuning:
- Log user queries and bot responses in your backend.
- Curate and format into Q&A/code pairs for future model customization.

---

## Deployment

- Backend: Deploy with Render, Heroku, AWS, etc.
- Frontend: Use Vercel, Netlify, or GitHub Pages.

---

**Enjoy building with your own AI Coding Chatbot!**