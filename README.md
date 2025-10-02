# 🛒 Smart Grocery Reminder
Smart Grocery Reminder is a full-stack application designed to simplify grocery management and reduce food waste. It allows users to track grocery items, detect expiry dates (via manual entry or OCR from receipts), and automatically receive reminders through email or SMS before items expire.

This project combines practicality with modern web development technologies, offering a seamless and intuitive way to manage groceries at home.


## 🚀 What It Does
- Tracks grocery items with expiry dates.
- Accepts input either manually or through receipt scanning (OCR).
- Stores all data in a PostgreSQL database.
- Sends automated reminders (via email/SMS) when groceries are about to expire.
- Provides a React-based dashboard for monitoring groceries with filters, search, and sorting.


## 💡 Why It’s Useful
Food waste is a growing global issue. Many people forget what groceries they bought or when items will expire. This app acts as a personal grocery assistant, helping users:
- Save money by reducing waste.
- Stay organized with a clear view of what’s in stock.
- Get timely notifications to use groceries before expiry.


## ✨ Features
- Add groceries manually or by scanning a receipt (OCR)
- Store items with expiry dates in PostgreSQL
- Automated reminders (email and SMS)
- React dashboard with filters (expired, expiring soon, fresh), search, sort
- Docker-ready for local development


## 🛠 Tech stack
- Frontend: React (Vite) + Tailwind CSS
- Backend: Node.js + Express
- Database: PostgreSQL with Prisma ORM
- OCR: Tesseract.js (client/server) — alternative: Google Cloud Vision
- Notifications: SendGrid (email), Twilio (SMS)
- Scheduler: `node-cron` or background worker (Bull + Redis)


## 📚 What I Learned
While building this project, I gained hands-on experience with:
- Full-stack development (React, Node.js, PostgreSQL).
- Database design with Prisma ORM.
- Using OCR tools like Tesseract.js for text extraction.
- Setting up background jobs for scheduling tasks.
- Sending automated notifications via third-party APIs (SendGrid, Twilio).
- Containerization using Docker for simplified deployment.


## 🔮 Possible Future Improvements
- 📱 Develop a mobile app version (React Native / Flutter).
- 🛒 Integration with popular e-commerce grocery APIs for auto-fetching receipts.
- 🌐 Multi-language support for international users.
- 🔔 Push notifications in addition to email/SMS.
- 🤖 AI-powered expiry prediction (based on item type and storage conditions).
- 👨‍👩‍👧 Shared family accounts with collaborative grocery tracking.


## ⚡ Quick start (development)
1. Clone repo
```bash
git clone https://github.com/<https://github.com/dikshantnanwate94-prog>/smart-grocery-reminder.git
cd smart-grocery-reminder
