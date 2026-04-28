# Astra System 🤖

> **Multi-agent AI platform** connecting business needs with automated, real-time solutions.

[![Status](https://img.shields.io/badge/status-production-brightgreen)](https://github.com/artemiomora/astra-system)
[![Stack](https://img.shields.io/badge/stack-PWA%20%7C%20Apps%20Script%20%7C%20Claude%20%7C%20GPT-blue)](https://github.com/artemiomora/astra-system)
[![Efficiency](https://img.shields.io/badge/ops%20efficiency-%2B70%25-orange)](https://github.com/artemiomora/astra-system)

---

## 🚀 What is Astra System?

Astra System is a **production-ready, multi-agent AI platform** built as a single-file Progressive Web App (PWA). It connects any business model to a suite of AI-powered agents that handle operations, customer management, sales, logistics, and financing — all from one unified interface.

Currently live with two active business modules:
- **Astra Moda** — AI-powered fashion retail management
- **Astra Pay** — Consumer financing and payment facilitation

---

## ⚙️ Architecture

```
Client (PWA) → Google Sheets API → Backend (Apps Script) → Claude API + OpenAI API
     ↑                                      ↓
index.html + Service Worker         Multi-agent orchestrator
12+ modules (offline-first)         Tool calling + Context injection
                                    Business memory + RAG-lite
```

---

## 🤖 AI Agent Capabilities

The Astra AI agent operates with RAG-lite architecture — injecting real-time business context into every LLM call:

| Capability | Description |
|---|---|
| 📊 Query business metrics | Sales today, weekly trends, open orders |
| 👥 Customer lookup | Search by name, tier, purchase history |
| ✅ Task management | Create, edit, prioritize activities |
| 🔔 Proactive alerts | Inventory low, payment due, follow-ups |
| 🎙️ Voice interface | Web Speech API — speak commands, hear responses |
| 💬 Contextual memory | Conversation history + business state per session |

**Models used:** Claude (Anthropic) · GPT-4 (OpenAI)

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript, PWA |
| Offline | Service Worker, Cache API, Sync Queue |
| Backend | Google Apps Script |
| Database | Google Sheets API |
| AI/LLM | Claude API, OpenAI API |
| Charts | Chart.js |
| PDF | jsPDF |
| QR | html5-qrcode, QRCode.js |
| Voice | Web Speech API |

---

## 📊 Production Metrics (April 2026)

| Metric | Value |
|---|---|
| Active users | 47 |
| Frequent customers in system | 200+ |
| Weekly transactions processed | 30+ |
| Operational time savings | 70% |
| Business domain experience | 6 years |
| Collaborators | 3 |

---

## 🧩 Modules

- **Dashboard** — Real-time KPIs, revenue graphs, activity feed
- **Pending Tasks** — Smart task queue with AI prioritization
- **Finances** — Cash register, cuts, income/expense tracking
- **Store (Astra Moda)** — Inventory, product catalog, order management
- **Customers** — CRM with tier system (Bronze/Silver/Gold/VIP)
- **Astra Pay** — Financing plans, payment schedules, loan tracking
- **Logistics** — Shipping, delivery status, vendor management
- **Astra Team** — Staff management, schedules, performance
- **Astra IA** — AI assistant with full business context
- **Config** — RBAC (CEO-only settings), system configuration

---

## 👤 About the Author

**Artemio Mora Ortiz** — AI Systems & Agents Engineer
📍 Brownsville, TX · Open to Remote US
🔗 [LinkedIn](https://www.linkedin.com/in/artemiomora)

> Self-taught builder with 6 years of domain expertise, 2 years I&C tech background, and a production AI system with measurable results.

---

*Built with Claude + GPT · In production since January 2025*
