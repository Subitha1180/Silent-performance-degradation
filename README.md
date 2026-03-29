# 🧠 AI-Based Silent Performance Degradation Detection System

## 📌 Overview

This project presents an AI-based system for detecting silent performance degradation in computer systems using **unsupervised machine learning** and **multivariate time-series analysis**.

Traditional monitoring systems rely on thresholds and reactive alerts, which often fail to detect gradual or hidden performance issues. This system provides a proactive solution by identifying early degradation and offering actionable insights.

---

## 🎯 Problem Statement

Modern monitoring systems:

* Use threshold-based alerts
* Depend on predefined rules
* React only after failures

### ❌ Limitations:

* Cannot detect gradual degradation
* Produce delayed or false alerts

### ✅ Solution:

This project uses **AI-driven anomaly detection** to identify hidden performance issues early.

---

## 🎯 Objectives

* Detect early performance degradation
* Analyze CPU, memory, disk, and network metrics
* Identify hidden system performance drift
* Reduce false alerts
* Enable proactive maintenance

---

## 🚀 Key Features

* 🔐 User Authentication & Role Management
* 📊 Real-Time Monitoring Dashboard
* 🤖 AI-Based Anomaly Detection
* 🧠 Root Cause Analysis using SHAP
* 📈 Time-Series Data Analysis
* 📧 Email Alerts & Notifications
* 🖥️ System & Server Management
* 💡 Recommendation Engine

---

## 🧩 System Modules

* System Degradation Analyzer
* User Management System
* Server Management
* Monitoring Agent
* Anomaly Detection Engine
* Recommendation System
* Alerts & Notification System

---

## 🏗️ System Architecture

### 🔹 Existing System

* Threshold-based monitoring
* Reactive alerts
* No predictive capability

### 🔹 Proposed System

* AI-based anomaly detection
* Continuous monitoring
* Explainable machine learning
* Proactive alert system

---

## ⚙️ Tech Stack

### 🖥️ Backend

* Python (Flask)
* Pandas, NumPy
* Scikit-learn
* TensorFlow / PyTorch

### 🌐 Frontend

* HTML, CSS, Bootstrap
* JavaScript

### 🗄️ Database

* MySQL

### 📦 Tools

* SHAP (Explainable AI)
* Flask-Mail

---

## 🤖 Machine Learning Approach

* Unsupervised Learning
* Multivariate Time-Series Analysis
* GRU-VAE / OmniAnomaly models
* Anomaly detection using reconstruction error
* Explainability using SHAP values

---

## 🔄 Workflow

1. Monitoring agent collects system metrics
2. Data is preprocessed
3. ML model analyzes patterns
4. Anomalies are detected
5. Root cause is identified
6. Alerts and recommendations are generated

---

## 📂 Project Structure

```
project/
│── app.py
│── agent.py
│── model/
│── database/
│── templates/
│── static/
│── utils/
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/Subitha1180/Silent-performance-degradation.git
cd Silent-performance-degradation
```

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Setup Database

```
CREATE DATABASE system_monitor;
```

Import the SQL file provided.

### 4️⃣ Configure Email

Update in `app.py`:

```
MAIL_USERNAME = 'your-email@gmail.com'
MAIL_PASSWORD = 'your-app-password'
```

### 5️⃣ Run Application

```
python app.py
```

👉 Open:

```
http://127.0.0.1:5000/
```

---

## 🧪 Testing

* Tested with real-time data
* Validated system metrics monitoring
* Checked anomaly detection accuracy
* Reduced false positives

---

## 📊 Results

* ✅ Early degradation detection
* ✅ Accurate anomaly detection
* ✅ Reduced false alerts
* ✅ Better system reliability

---

## 🔮 Future Enhancements

* ☁️ Cloud integration (AWS, Azure)
* ⚡ Real-time streaming analytics
* 🔄 Self-healing systems
* 📊 Advanced dashboards

---

## 🔒 Security Notes

* Use environment variables
* Avoid exposing credentials
* Implement role-based access

---

## 👩‍💻 Authors

* **Subitha G**
* Swethalashmi G
* Varshaa S R

---

## 🎓 Academic Context

Developed as part of a Computer Science Engineering project.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgement

If you like this project, give it a ⭐ on GitHub!
