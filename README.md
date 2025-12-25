# AirSafePlus — Multi-Location IoT Air Quality Monitoring (Node-RED)

**AirSafePlus** is a production-style IoT monitoring system that simulates and visualizes air quality across multiple urban locations (e.g., park, construction area, residential zone).

The system is built using **Node-RED** and follows a realistic IoT pipeline:
**sensors → MQTT messaging → analytics → dashboard → alerts & recommendations**.

---

## 🎯 Project Motivation

Air quality is a critical smart-city challenge:
- citizens need **simple and actionable insights**, not raw sensor values
- operators need **real-time monitoring and early warnings**
- systems must be **explainable and easy to extend**

This project demonstrates how to design an **end-to-end IoT analytics solution** that can later be connected to real sensors and cloud services.

---

## 🚀 Key Features

- Multi-location air quality monitoring
- Scenario-based sensor simulation (normal, dusty wind, gathering, construction)
- Risk-level calculation and health-oriented index
- Real-time dashboard (charts, gauges, indicators)
- Alert logic and user recommendations
- MQTT-based architecture ready for cloud integration

---

## 🧠 System Architecture (High-Level)

**Data Flow**
1. Location & scenario selection
2. Sensor data generation (PM2.5, CO₂, temperature, etc.)
3. MQTT message publishing
4. Analytics & risk calculation layer
5. Live dashboard visualization
6. Alerts and recommendations

**Designed to be easily extended with real IoT devices**

---

## 🛠 Tech Stack & Integrations

- **Node-RED** — orchestration and business logic
- **MQTT / HiveMQ** — message broker for sensor data
- **Node-RED Dashboard** — real-time visualization
- **JavaScript functions** — analytics & risk scoring
- **ThingSpeak-ready architecture** — optional cloud analytics integration

---

## 🖥️ Dashboard Demo

The dashboard visualizes:
- current air quality indicators
- risk level per location
- historical trends
- health recommendations for users

Screenshots are available below.

---

## 📂 Repository Structure

```text
AirSafePlus-IoT-NodeRED/
├── flows/        # Exported Node-RED flows (.json)
├── assets/       # Dashboard & flow screenshots
├── docs/         # Project documentation / report
├── README.md
└── LICENSE

▶️ How to Run (Node-RED)

Import the flow
	1.	Open Node-RED
	2.	Menu → Import
	3.	Upload flow from:

  flows/AirSafe+-Final-Flow.json

  	4.	Deploy the flow
	5.	Open the dashboard:
  http://localhost:1880/ui

  📸 Example Screenshots
  Normal air quality scenario
  High-risk air quality scenario
📈 Practical Value
	•	Demonstrates a realistic smart-city IoT use case
	•	Shows how to structure IoT analytics pipelines
	•	Easily adaptable to real sensors and cloud platforms
	•	Focus on clarity, explainability, and usability

⸻

🔮 Future Improvements
	•	Connection to physical sensors (ESP32, Arduino, Raspberry Pi)
	•	Cloud deployment (AWS IoT / Azure IoT Hub)
	•	Advanced anomaly detection
	•	Mobile-friendly dashboards
	•	Integration with public health systems

⸻

⚖️ License

MIT

  
