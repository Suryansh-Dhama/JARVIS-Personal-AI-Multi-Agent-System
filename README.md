# 🤖 JARVIS – Personal AI Multi-Agent System

## 🚀 Project Title

**JARVIS – AI-Powered Personal Multi-Agent Assistant using n8n**

---

## 📌 Brief One Line Summary

An intelligent personal AI assistant built with n8n that automates tasks like email, scheduling, content creation, and contact management using multiple specialized agents.

---

## 📖 Overview

JARVIS is a powerful multi-agent AI system designed to act as a personal assistant. It integrates multiple task-specific agents such as Email, Calendar, Content Creator, and Contact Manager into a unified system. The assistant can understand user queries, route them to the appropriate agent, and provide accurate responses or perform real-world actions.

---

## ❗ Problem Statement

Managing daily tasks like sending emails, scheduling meetings, creating content, and organizing contacts manually can be time-consuming and inefficient. There is a need for a centralized intelligent system that can automate these processes and respond to user queries in real time.

---

## 📊 Dataset

This project does not rely on a static dataset. Instead, it uses:

* User inputs (queries and commands)
* Contacts database (stored in Airtable or similar)
* External APIs (for email, calendar, and web data)

---

## 🛠️ Tools and Technologies

* n8n (Workflow Automation)
* OpenAI / LLM APIs (AI reasoning)
* Webhooks (API communication)
* Airtable (Contacts database)
* Gmail API / SMTP (Email automation)
* Google Calendar API (Scheduling)
* ElevenLabs (Voice interaction - optional)
* ngrok (Webhook exposure)

---

## ⚙️ Methods

* Multi-agent architecture design
* Intent detection and routing
* Workflow automation using n8n
* API integration for real-world actions
* Dynamic variable handling
* Memory and context management

---

## 🔍 Key Insights

* Multi-agent systems improve modularity and scalability
* Workflow automation reduces manual effort significantly
* AI-powered routing enhances task accuracy
* Integration of APIs enables real-world task execution

---

## 📊 Dashboard / Model / Output

* Chat-based interface (text/voice)
* Automated email sending and drafting
* Calendar event creation and management
* Contact search and storage system
* AI-generated content (captions, posts, etc.)

---

## ▶️ How to Run this Project?

1. Install n8n locally or use cloud version
2. Import all JSON workflow files:

   * JARVIS.json
   * Email Agent
   * Calendar Agent
   * Content Creator Agent
   * Contact Agent
3. Set up credentials:

   * OpenAI API Key
   * Airtable API Key
   * Gmail / SMTP
   * Google Calendar API
4. Start ngrok to expose webhook
5. Activate workflows in n8n
6. Send requests via webhook or UI

---

## 📈 Results & Conclusion

The system successfully automates multiple personal and professional tasks using AI. It reduces manual effort, increases productivity, and provides a seamless user experience through intelligent task handling and automation.

---

## 🔮 Future Work

* Add voice assistant with real-time streaming
* Implement long-term memory (database/Redis)
* Improve UI with React frontend
* Add more agents (Finance, News, Tasks)
* Integrate real-time internet search (RAG)

---

## 👨‍💻 Author & Contact

**Suryansh Dhama**
B.Tech CSE (AI & ML)

📧 Email: [ydvryo@gmail.com](mailto:ydvryo@gmail.com)

🔗 LinkedIn: https://www.linkedin.com/in/suryansh-dhama-7217a428b

💻 GitHub: https://github.com/Suryansh-Dhama

---
