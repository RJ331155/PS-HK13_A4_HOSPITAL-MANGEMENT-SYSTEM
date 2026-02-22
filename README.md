# HMS — AI-Driven Real-Time Patient Queue & Appointment Optimization
**Developed by Team A4**

## 🚀 Overview
A web-based Hospital Management System that replaces traditional "first-come, first-served" queues with an **AI-driven priority engine**. It auto-sorts patients based on medical severity, emergency status, and wait time.

## 🧠 AI Priority Logic
The system uses a predictive scoring algorithm to ensure critical patients are treated first:
- **Severity (Lvl 1-5):** Multiplied by a high-weight factor.
- **Emergency Status:** Adds a "Critical" bonus to the score.
- **Wait Time:** Gradually increases priority to prevent low-severity patients from being ignored.

## 🛠️ Tech Stack
- **Frontend:** HTML5, CSS3 (Custom Animations), JavaScript (ES6+)
- **AI Engine:** Custom JS-based scoring algorithm
- **Communication:** EmailJS API for real-time prescriptions
- **Database:** LocalStorage for persistent session data
