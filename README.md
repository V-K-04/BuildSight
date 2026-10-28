# 🏗️ BuildSight

**AI-Powered Construction Intelligence**

BuildSight is a web application that helps users analyze construction sites using AI. It provides site safety analysis, crack detection, construction cost estimation, weather information, and an AI construction assistant.

---

## 🚀 Features

- 🦺 AI Site Safety Analysis
- 🧱 Crack Detection & Analysis
- 📐 Construction Cost Estimation
- 🤖 AI Construction Assistant
- 🌦️ Weather Information
- 📄 Download Reports

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Axios
- CSS

### Backend
- Python
- FastAPI
- Uvicorn
- Pydantic

### AI & APIs
- Google Gemini API
- Open-Meteo API

---

## 📂 Project Structure

```
buildsight-multimodal-construction-intelligence/
│
├── backend/
│   ├── main.py
│   ├── config.py
│   ├── requirements.txt
│   └── .env.example
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── README.md
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/buildsight.git

cd buildsight
```

---

## 2. Backend Setup

Move to backend

```bash
cd backend
```

Create virtual environment

```bash
python -m venv venv
```

Activate it

### Windows

```powershell
venv\Scripts\activate
```

### macOS/Linux

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create `.env`

```text
GEMINI_API_KEY=YOUR_API_KEY
```

Run backend

```bash
uvicorn main:app --reload
```

Backend runs on

```
http://localhost:8000
```

API Docs

```
http://localhost:8000/docs
```

---

## 3. Frontend Setup

Open another terminal

```bash
cd frontend
```

Install packages

```bash
npm install
```

Create `.env`

```text
VITE_API_URL=http://localhost:8000
```

Run frontend

```bash
npm run dev
```

Frontend runs on

```
http://localhost:5173
```

---

## 📸 Screenshots

Add screenshots here.

```
frontend/public/screenshots/
```

---

## 📦 Build

Frontend

```bash
npm run build
```

Backend

```bash
python -m pytest
```

---

## ☁️ Deployment

### Frontend

Deploy on **Vercel**

### Backend

Deploy on **Render**

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## ⚠️ Disclaimer

BuildSight provides AI-assisted insights for educational and informational purposes. Construction decisions should always be verified by qualified professionals.

---