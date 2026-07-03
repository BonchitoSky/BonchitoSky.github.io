---
title: "Experience"
draft: false
---

## Engineering Experience

I'm Rupankar Dutta, a B.Tech student and builder with hands-on experience across embedded systems, Edge AI, backend development, and full-stack web applications. My work is centered on practical systems that combine hardware, software, and real-time decision-making.

## Focus Areas

### Embedded Systems, IoT, and Edge AI
- Built decentralized real-time systems on ESP32 for local communication, sensing, and automation
- Developed firmware for sensor-integrated devices using MPU-6050, DHT11, MQ-135, PIR, and sound sensors
- Worked with ESP32-WROOM-32, ESP32-CAM, and ESP-NOW for low-latency wireless communication
- Trained and deployed on-device ML models using TinyML, LSTM autoencoders, int8 quantization, TFLite Micro, Edge Impulse, and MobileNetV2

### Backend, Full-Stack, and AI Application Development
- Built application backends using FastAPI, Flask, Node.js, and Express
- Engineered microservices infrastructure including API gateway patterns with JWT authentication and Redis rate limiting
- Developed interactive web experiences using React, Socket.IO, MySQL, and PostgreSQL
- Integrated AI services (OpenAI API, Google Vision) into full-stack products with personalization and chat memory
- Containerized applications with Docker and set up CI workflows with GitHub Actions

### Programming and Tooling
- Languages: Python, C, C++, JavaScript, SQL
- Tools: Arduino IDE, PlatformIO, EasyEDA, Git, Docker, VS Code
- Libraries and utilities: BeautifulSoup, PyPDF2

## Project Experience

### Edge AI Anomaly Detection System ([GitHub](https://github.com/BonchitoSky/edge-ai-anomaly-detection))
- Built a real-time vibration anomaly detection system running entirely on an ESP32 with an MPU-6050 sensor — no cloud required
- Trained an LSTM autoencoder in TensorFlow on normal-only data and quantized it to int8 for TFLite Micro on-device inference
- Added a fault-type classifier that identifies the kind of anomaly (drop, shake, imbalance) alongside severity
- Developed a Flask + JavaScript dashboard with live reconstruction-error charts, adaptive EWMA thresholding, and CSV-exportable anomaly event logs

### CookMind AI – AI-Powered Cooking Assistant ([GitHub](https://github.com/BonchitoSky/CookMind-AI))
- Developed a full-stack AI application using React, Vite, FastAPI, PostgreSQL, and the OpenAI API
- Built recipe recommendations from ingredient lists, conversational cooking assistance with chat memory, and image-based ingredient recognition via Google Vision
- Implemented JWT signup/login, pantry persistence, cuisine and dietary preferences, and favorite recipe saving
- Containerized the stack with Docker (dev and production compose files with an Nginx reverse proxy) and added a CI workflow for backend tests and frontend builds

### TheRUPOgate – Microservices API Gateway ([GitHub](https://github.com/BonchitoSky/TheRUPOgate))
- Engineered a production-style Node.js API gateway serving as a single entry point in front of microservices
- Implemented JWT authentication with role-based header injection for downstream services
- Built Redis sliding-window rate limiting that fails open if Redis is unavailable
- Added structured JSON logging and a live monitoring dashboard streaming request metrics over Server-Sent Events

### Intelligent Decentralized Home Automation System
- Developed a decentralized smart home system using ESP32 nodes communicating through ESP-NOW
- Implemented local sensing, threshold-based alerts, timing control, and offline automation logic
- Integrated DHT11, MQ-135, PIR, and sound sensors into the firmware pipeline
- Contributed to a MobileNetV2-based facial recognition workflow for secure access control on ESP32-CAM

### Real-Time Multiplayer Quiz Platform
- Built a multiplayer quiz application using React, Node.js, and Socket.IO
- Implemented private rooms, timed rounds, live score tracking, leaderboard generation, and synchronized gameplay state

### Natural Language to SQL Query Generator
- Built a Flask and MySQL based application that converts natural language questions into SQL queries
- Developed the backend query flow, execution pipeline, and result presentation interface

### Dynamic Programming Text Auto-Correction
- Developed a C-based text correction system using edit-distance dynamic programming
- Focused on optimized string matching, fast suggestion generation, and correction accuracy

### Automated Plant Watering System
- Built an ESP32-based irrigation system that automates watering decisions from environmental input
- Added real-time monitoring and control behavior to improve reliability and efficiency

### WiFi Network Scanner
- Developed an ESP32 utility to detect nearby WiFi networks and display SSID and RSSI values
- Used the system for quick signal analysis and basic wireless environment diagnostics

For more details about my technical background and projects, please refer to my [resume](/my-resume).
