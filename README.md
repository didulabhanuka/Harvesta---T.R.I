# 🌿 HARVESTA - T.R.I

**Smart Agriculture Assistant for Modern Farmers**  
Built with React Native & Flask.

---

## 📖 About The Project

HARVESTA - T.R.I is a smart agriculture assistant app focused on optimizing plant growth, ripeness prediction, and harvesting schedules.  
Using real-time data, environmental recommendations, and smart analysis, it helps farmers make better decisions easily.

---

## 🚀 Tech Stack

| Frontend | Backend | Database | Other |
|:---|:---|:---|:---|
| React Native (Expo) | Flask (Python) | Firebase Firestore | OpenWeather API |

---

## ✨ Core Features

✅ Lottie Splash Screen  
✅ Interactive Welcome Onboarding  
✅ Home Dashboard with Real-Time Weather  
✅ Harvest Prediction Dashboard (Charts, Data)  
✅ Image Upload for Plant Analysis (Gallery/Camera)  
✅ Historical Data Visualization  
✅ Dynamic API Integration (Upload/Fetch Predictions)

---

## 📂 Project Structure

```
/client     --> Mobile App (React Native + Expo)
/server     --> Backend API (Flask + Firebase)
```

---

## ⚡ API Endpoints Summary

| Method | Endpoint | Description |
|:------|:---------|:------------|
| POST | `/harvesta-api/harvestingpredict/predict` | Upload multiple images for ripeness prediction |
| GET | `/harvesta-api/harvestingpredict/historical-data` | Fetch last 7 days of historical ripeness |
| GET | `/harvesta-api/harvestingpredict/latest-data` | Fetch latest ripeness prediction |

---

## 🛠️ Getting Started

### 🚀 Running the Client (React Native)

```bash
cd client
npm install
npm start
```
Scan QR with Expo Go app to run!

---

### 🔥 Running the Server (Flask API)

```bash
cd server
pip install -r requirements.txt
python app.py
```
Server will run at: `http://localhost:5000/`

---

## 🛡️ Important Notes

- If testing on a real device, update API URL from `localhost` ➔ to your local network IP (e.g., `192.168.x.x`)
- Client and Server must be running at the same time for full functionality.

---

## ❤️ Built for T.R.I

Project proudly developed with care and quality.
