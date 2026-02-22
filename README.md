# HMS — AI-Driven Real-Time Patient Queue & Appointment Optimization 🏥

![Team](https://img.shields.io/badge/Team-A4-7c3aed)
![Edition](https://img.shields.io/badge/Software-Edition-blue)
![Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20JS-yellow)
![Status](https://img.shields.io/badge/Status-Live-green)

An advanced **AI-powered patient flow optimization platform** designed to eliminate the inefficiency of static hospital scheduling. This system moves beyond traditional "first-come, first-served" models to a dynamic, multi-objective optimization approach.

## 🚀 The Problem
Traditional hospital queues fail because they are static. They cannot handle:
* **Emergency walk-ins** that disrupt the schedule.
* **Consultation overruns** (service time uncertainty).
* **Real-time volatility** in patient arrivals.

## 🧠 Our Solution: AI-Driven Dynamic Scheduling
Our platform uses a weighted **Optimization Engine** that continuously re-calculates patient priority based on three key vectors:

$$Score = (Severity \times 15) + (WaitTime \times 0.5) + (EmergencyBonus)$$

### Key Optimization Features:
* **AI Predicted Wait Times:** Unlike static estimates, our system uses patient severity levels (1-5) to predict consultation duration and potential delays.
* **Dynamic Re-Optimization:** The "Priority Queue" auto-sorts in real-time. If an emergency (Severity 5) arrives, the AI re-calculates the entire flow without manual intervention.
* **Explainable AI (XAI):** The system provides "Stability vs. Emergency" badges, explaining to staff and patients why specific tokens are prioritized.
* **Multi-Channel Communication:** Integrated with **EmailJS** to send real-time prescriptions and reports directly to patients' Gmail.



---

## ✨ Core Features

### 👨‍⚕️ Staff Control Center
* **Quick Registration:** Rapid intake form with auto-severity detection based on symptoms.
* **Live Analytics:** Dashboard tracking "Treatment Rate," "Avg Severity," and "Disease Breakdown."
* **Medical Records:** Full treatment history with persistent local storage.
* **Doctor Email Setup:** Secure configuration for EmailJS to automate patient communication.

### 🧑 Patient Portal
* **Real-time Position Tracking:** Patients can view their exact place in the queue.
* **AI Wait Prediction:** Visual feedback on estimated minutes until treatment.
* **Queue Transparency:** A "Now Serving" dashboard to reduce perceived wait time and anxiety.

---

## 🛠️ Technical Stack
* **Frontend:** Vanilla JavaScript, HTML5, CSS3 (Custom Glassmorphism UI).
* **Animations:** SVG ECG path animations and CSS-driven vital pulse orbs.
* **Communication:** EmailJS API integration.
* **Optimization Logic:** Weighted scoring algorithm for queue management.
* **Storage:** Browser `localStorage` for persistent state management across sessions.
