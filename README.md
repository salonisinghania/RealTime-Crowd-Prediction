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

 ## 📸 Sample Dashboard Preview

🖼️ **Smart City Crowd Monitoring Dashboard** – an AI-powered, real-time visualization of crowd density, air quality, and predictive alerts for urban safety and management.

> *(Below is a sample look of the live dashboard interface showcasing map markers, KPIs, and predictive analytics.)*

![Smart City Crowd Dashboard Sample](frontend/src/assets/sample_dashboard.png)


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

### 🧩 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Smart-City-Crowd-Dashboard.git
cd Smart-City-Crowd-Dashboard
````

---

### ⚙️ 2️⃣ Backend Setup (Django)

```bash
cd backend
python -m venv venv
venv\Scripts\activate   # (Windows)
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

🔹 **Runs on:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

### 💻 3️⃣ Frontend Setup (Angular 12)

```bash
cd ../frontend
npm install
npx ng serve --open
```

🔹 **Opens on:** [http://localhost:4200/](http://localhost:4200/)

---

### 🧾 Environment Configuration

Create a `.env` file inside `/backend` and update your credentials:

```bash
DJANGO_SECRET_KEY=your_secret_key_here
MONGODB_URI=mongodb+srv://<user>:<password>@cluster.mongodb.net/
MONGO_DB_NAME=crowd_db
ALERT_THRESHOLD=350
```

---

## 🧭 How It Works

1. **Django REST API** fetches and serves live or simulated crowd + AQI data.
2. **Angular frontend** polls every 30 seconds for real-time updates.
3. Data visualizations include:

   * 🟢 Normal zones (low density)
   * 🔴 Alert zones (high crowd or poor air quality)
4. **AI Prediction Engine** forecasts next-hour crowd and AQI trends.

---

## 🔮 Example Prediction Response

```json
{
  "predicted_count": 482,
  "predicted_aqi": 156,
  "alert_expected": true
}
```

---

## 🧠 Future Enhancements

* 📡 IoT sensor integration for live data streams
* 🗺️ Predictive heat-map visualization
* 📧 Smart alert notifications (SMS / Email)
* 🔐 Role-based admin analytics dashboard

---

## 👩‍💻 Contributor

**Saloni Singhania** — *Full-Stack Developer | AI & ML Integration*

---

## ⚖️ License

Licensed under the **MIT License** — free for personal and academic use.

---

## 🌟 Tags

`angular` • `django` • `mongodb` • `ai` • `iot` • `dashboard` • `smart-city` • `python` • `data-visualization`

```

---


