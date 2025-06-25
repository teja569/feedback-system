# Feedback System 📝

A web-based feedback management platform allowing managers and employees to exchange feedback, request reviews, and track sentiments. Built with a modern tech stack for flexibility and easy deployment.

---

## 🌐 Live Demo

**Frontend:** [Visit frontend](https://feedback-system-frontend-2nsa.onrender.com/)  
**Backend API:** [Visit backend](https://feedback-system-backend-9djn.onrender.com/)

---

## 🛠️ Tech Stack

| Layer           | Tech                             |
|-----------------|----------------------------------|
| Frontend        | React, Axios, Chart.js           |
| Backend         | FastAPI, SQLAlchemy, Pydantic    |
| Database        | SQLite (local)                   |
| Deployment      | Render (both frontend & backend) |
| Version Control | Git & GitHub                     |

---

## 🔧 Project Structure

```
feedback-system/
├── frontend/          # React client app
├── backend/           # FastAPI server
│   ├── main.py
│   ├── models.py
│   ├── schemas.py
│   ├── database.py
│   └── Dockerfile
└── README.md
```

---

## 🚀 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/teja569/feedback-system.git
cd feedback-system

2. Backend Setup (FastAPI)
▶️ Local Setup
cd backend
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn main:app --reload

▶️ Docker Setup
cd backend
docker build -t feedback-backend .
docker run -p 8000:8000 feedback-backend


3. Frontend Setup (React)
cd frontend
npm install
npm start

🌟 Features
🔐 Login & Signup (Employee / Manager roles)

✅ Manager submits feedback to employees

📩 Employees request feedback from managers

🔁 Peer-to-peer feedback (anonymous option)

📊 Sentiment tracking & charts

🖨️ Export feedback as PDF

🏷️ Feedback tags (e.g. communication, leadership)

🗨️ Feedback comments with markdown

🛡️ Role-based access

🌐 CORS-enabled API for frontend integration

📦 Environment Variables
.env example for backend:

DATABASE_URL=postgresql://<user>:<password>@<host>:<port>/<dbname>
SECRET_KEY=your-secret-key

✨ Design Decisions
FastAPI for clean API design and async support

SQLite for local development, PostgreSQL for production

React with hooks for component state and reusable UI

Axios to handle API requests

Render used for zero-config full stack deployment

Docker for consistent backend containerization

📄 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

---

Let me know if you'd like to include [screenshots](f), [deployment commands](f), or [API documentation](f).

