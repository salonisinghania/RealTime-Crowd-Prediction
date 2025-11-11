# RealTime-Crowd-Prediction
# 🏙️ Smart City Crowd Monitoring Dashboard

![Angular](https://img.shields.io/badge/Frontend-Angular_12-DD0031?logo=angular&logoColor=white)
![Django](https://img.shields.io/badge/Backend-Django_5-092E20?logo=django&logoColor=white)
![MongoDB](https://img.shields.io/badge/Database-MongoDB_Atlas-4EA94B?logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/Language-Python_3.13-3776AB?logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

---

> 🧠 **An AI-driven smart city dashboard** for monitoring real-time crowd density, air quality, and predictive alerts using Django, Angular, and MongoDB Atlas.

---

## 📸 Sample Dashboard Preview

 

---

## 🧩 Overview

The **Smart City Crowd Monitoring Dashboard** empowers urban planners and emergency managers to visualize, analyze, and predict crowd patterns using live IoT and AI-driven data.

### 💡 Highlights
- Real-time **crowd & AQI** monitoring
- **Predictive alerts** for high-density or pollution spikes
- **Dynamic map visualization** (Leaflet JS)
- **Interactive charts & KPIs**
- **Searchable live data table**

---

## ⚙️ Tech Stack

- **Frontend:** Angular 12 (TypeScript, Leaflet, HTML, CSS)
- **Backend:** Django REST Framework (Python 3.13)
- **Database:** MongoDB Atlas (Cloud)
- **AI Module:** Predictive model for crowd + AQI forecasting
- **Visualization:** Map + KPI Cards + ChartJS (simplified)

---

## 🚀 Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Smart-City-Crowd-Dashboard.git

2️⃣ Backend Setup (Django)
cd backend
python -m venv venv
venv\Scripts\activate  # for Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver


🔹 Runs on → http://127.0.0.1:8000/

3️⃣ Frontend Setup (Angular)
cd ../frontend
npm install
npx ng serve --open


🔹 Opens on → http://localhost:4200/

🔧 Environment Configuration

Create a .env file inside /backend:

DJANGO_SECRET_KEY=your_secret_key_here
MONGODB_URI=mongodb+srv://<user>:<password>@cluster.mongodb.net/
MONGO_DB_NAME=crowd_db
ALERT_THRESHOLD=350

🧭 How It Works

Backend API (Django) fetches live or simulated data from MongoDB.

Frontend (Angular) polls every 30 seconds for new updates.

Data points are visualized as:

🟢 Normal zones (low density)

🔴 Alert zones (high density or poor AQI)

AI predictions show expected next-hour trends.

🔮 Example Prediction Response
{
  "predicted_count": 482,
  "predicted_aqi": 156,
  "alert_expected": true
}

🧠 Future Improvements

IoT sensor integration for live feeds

Predictive heat-map visualization

Alert notifications via SMS / Email

Role-based admin analytics panel

🧑‍💻 Contributors

Saloni Singhania — Full-Stack Developer | Machine Learning Integration


⚖️ License

This project is licensed under the MIT License – free to use and modify with attribution.

🌟 GitHub Tags

angular • django • mongodb • ai • iot • dashboard • smart-city • python • data-visualization
