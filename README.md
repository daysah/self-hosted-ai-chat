# 🤖 Self-Hosted AI Chat Platform

![Docker](https://img.shields.io/badge/Docker-Ready-blue)
![Linux](https://img.shields.io/badge/Linux-Supported-success)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Stable-brightgreen)

A *privacy-focused ChatGPT alternative* using *Ollama* and *Open WebUI*.
Fully local. No cloud APIs. Your data stays yours.

---

## ✨ Features

- 🧠 Local LLMs (LLaMA 3, Mistral)
- 👥 Multi-user authentication
- 🐳 Docker & Docker Compose
- 🔒 Privacy-first (offline capable)
- ⚡ Simple 5-minute setup

---

## 📸 Screenshots

### Dashboard
![Dashboard](docs/screenshots/dashboard.png)

### Chat Interface
![Chat](docs/screenshots/chat.png)

---

## 🚀 Quick Start

```bash
git clone https://github.com/daysah/self-hosted-ai-chat.git
cd self-hosted-ai-chat
docker compose up -d
—-


##🧠 Download Models

```bash
docker exec -it ollama ollama pull llama3
docker exec -it ollama ollama pull mistral
—-


##🔐 Security Notes
	•	Authentication enabled by default
	•	All data stored locally
	•	No external API calls
	•	Works fully offline after model download

⸻

##🧪 Tested On
	•	Fedora Linux
	•	Ubuntu 22.04
	•	Docker Compose v2
