# Automated-Weather-Report-via-Gmail-using-n8n
"Send daily weather reports to Gmail using n8n + OpenWeatherMap API"
# 🌤️ Automated Weather Report to Gmail using n8n

This project uses [n8n](https://n8n.io/), an open-source workflow automation tool, to automatically send a daily weather report to your Gmail inbox using data from the OpenWeatherMap API.

---

## 🚀 Features

- Fetches real-time weather data using **OpenWeatherMap API**
- Sends a formatted daily email to Gmail using **n8n’s Gmail node**
- Fully automated with scheduling via **Cron node**
- Customizable city/location and email content
- Easy to extend with SMS, Slack, or home automation integrations

---

## 🧰 Tech Stack

- **n8n**
- **OpenWeatherMap API**
- **Gmail API**
- **JavaScript (Function Nodes)**

---

## 📸 Workflow Screenshot

![Workflow Screenshot](./screenshots/w<img width="1466" alt="Automated Daily Weather Notification System using n8n" src="https://github.com/user-attachments/assets/0b7963ab-38f6-4fbd-a82e-4ac77a928848" />
orkflow.png)

---

## 📁 Files Included

- `automated-weather-workflow.json`: n8n exported workflow
- `.env.example`: Environment variable template
- `README.md`: Project documentation

---

## 🔑 Prerequisites

- n8n installed locally or on cloud (e.g., n8n Cloud, Docker)
- Gmail account with OAuth2 credentials set up in n8n
- OpenWeatherMap API key (free account)

---

## ⚙️ Setup Instructions

1. **Clone this repo**
   ```bash
   git clone https://github.com/your-username/automated-weather-n8n.git
   cd automated-weather-n8n

🌤️ Weather Report for New York

Condition: Clear Sky
Temperature: 72°F
Humidity: 45%
Wind: 10 mph


