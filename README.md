# CropTrack-Live

An IoT-based agriculture monitoring platform using **Spring Boot (Java)** for the backend and MQTT for sensor communication.  
Provides real-time environmental data, analytics, and automated irrigation recommendations.

## 🚀 Features
- Live temperature, humidity, and soil moisture monitoring
- MQTT-based IoT device data ingestion
- AI-powered irrigation scheduling (placeholder)
- REST API for sensor data

## 🛠 Tech Stack
- Backend: Java 17, Spring Boot, MQTT, REST API
- Frontend: React (optional dashboard UI)
- Database: H2 (dev mode) / TimescaleDB (prod-ready)
- Version Control: Git + GitHub

## 📂 Structure
- `/backend` – Spring Boot application
- `/frontend` – React dashboard (if added)
- `/docs` – diagrams, screenshots, and setup guides

## 🧑‍💻 Setup
```bash
# Backend
mvn spring-boot:run
# Default API: http://localhost:8081/api/sensors
