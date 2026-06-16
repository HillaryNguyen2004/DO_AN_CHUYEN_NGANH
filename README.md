# Trimibel — AI-Powered Workspace Platform
> An integrated Workspace platform for modern organizations, combining real-time operations, AI-powered productivity forecasting, and intelligent document Q&A.

---

## 🎬 Demo

<!-- Paste your video demo link or GIF here -->
> [![Watch Demo](https://img.youtube.com/vi/wmGUKQNcznc/maxresdefault.jpg)](https://youtu.be/wmGUKQNcznc)
---

## ✨ Features

- **Project & Task Management** — Full lifecycle tracking with phases, priorities, quality scoring, and burndown charts
- **Attendance & Leave** — Check-in/check-out, late tracking, day-off approval workflows
- **LSTM Productivity Forecasting** — Predicts each employee's next-day productivity (Low/Medium/High) using 14 days of behavioral data
- **RAG AI Chatbot** — Ask questions about HR documents and employee productivity in natural language
- **Real-Time Collaboration** — Group chat, notifications, whiteboard, document management
- **Face Detection Check-In** — Facial recognition for attendance verification
- **Data Warehouse & Analytics** — ETL pipeline, dimensional model, exportable reports

---

## 🏗️ Tech Stack

| Layer | Technologies |
|---|---|
| Backend | Laravel 9, PHP 8.2, MySQL, PostgreSQL |
| Frontend | Vite, TailwindCSS, Chart.js |
| ML / AI | Python, TensorFlow/Keras (LSTM), Flask, FastAPI |
| LLM / RAG | Deepseek-r1, ChromaDB |
| Real-Time | Pusher, Laravel Echo |
| Storage | AWS S3 |

---

## 🚀 Quick Start

````bash
# Clone and install
git clone https://github.com/HillaryNguyen2004/DO_AN_CHUYEN_NGANH.git
cd DO_AN_CHUYEN_NGANH
composer install && npm install

# Configure environment
cp .env.example .env
php artisan key:generate && php artisan jwt:secret

# Run migrations and seeds
php artisan migrate && php artisan db:seed

# Start services
php artisan serve          # Laravel (port 8000)
python ml/api.py           # LSTM Flask API (port 5001)
python chatbot_service/api/app.py  # RAG FastAPI (port 8000)
npm run dev                # Frontend
````

---

## 👥 Team

| Member | Responsibilities |
|---|---|
| **Tran Tuan Minh Khoa** | AI Chatbot Service, Workspace & Project Management, Task Management, User & Role Management, CI/CD & AWS Deployment |
| **Nguyen Thi Quoc Nguyen** | LSTM Productivity Forecasting, Attendance & Reports, Department Permissions, Meeting Management, Email Campaigns, Whiteboard |
| **Tu Khanh Minh** | Advanced Search System, Department Management, Real-Time Chat, Notifications, Document Management, AI Summarization |
| **Nguyen Huu Tri** | Speech-to-Text, Calendar Management, UI/UX Design, Day-off Requests, Holiday Management |
---

## 📁 Project Structure

````
DO_AN_CHUYEN_NGANH/
├── app/              # Laravel controllers, models, services
├── ml/               # LSTM training & Flask inference API
├── chatbot_service/  # FastAPI RAG chatbot
├── etl/              # ETL pipeline (MySQL → PostgreSQL DW)
├── face_detection/   # Face recognition module
└── resources/views/  # Blade templates & frontend
````

---

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.2-blue?logo=php" />
  <img src="https://img.shields.io/badge/Laravel-9-red?logo=laravel" />
  <img src="https://img.shields.io/badge/Python-3.9+-yellow?logo=python" />
  <img src="https://img.shields.io/badge/TensorFlow-LSTM-orange?logo=tensorflow" />
  <img src="https://img.shields.io/badge/status-active-brightgreen" />
</p>
