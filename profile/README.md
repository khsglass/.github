# 👋 Welcome to KHS Glass

KHS Glass is an internal platform built to support 
the operations of a local glass business. 
It is a fully containerized, microservices-based 
system designed for reliability, modularity, and 
scalability.

🔒 Most repositories are private — ongoing commercial project.

---

## 🚀 What We're Building

A full-stack system for managing a glazier business:

- 🤖 AI-powered chatbot (GPT-4o-mini) in Hebrew, Arabic, English
- 🔐 Session management with secure cookies and CSRF protection
- 🖼️ Gallery management with photo upload and organization
- 🧮 Admin tools: price calculator, handwriting recognition
- 📊 Conversation analytics and lead tracking
- 🏗️ Microservice architecture (FastAPI, TypeScript, Docker)

---

## 🛠️ Technologies

- **Frontend:** React (TypeScript), Tailwind CSS, shadcn/ui
- **Backend:** FastAPI (Python), PostgreSQL, SQLAlchemy
- **AI:** OpenAI GPT-4o-mini
- **Gateway:** Nginx (api.khsglass.com)
- **Infrastructure:** Docker, Railway, GitHub Actions CI/CD
- **Auth:** Supabase Auth (coming soon)
- **Storage:** PostgreSQL on Railway (live)

---

## 📁 Repositories

| Repo | Description | Status |
|------|-------------|--------|
| `frontend` | React + TypeScript website | ✅ Live |
| `chatbot-service` | AI chat via GPT-4o-mini | ✅ Live |
| `control-plane-service` | Sessions, CSRF, auth, DB | ✅ Live |
| `api-gateway` | Nginx routing + CORS | ✅ Live |
| `image-compression-service` | Photo optimization | 🔄 In Progress |
| `admin-service` | Gallery + calculator | 📋 Planned |

---

## 🌐 Live

- Website: https://khsglass.com
- API: https://api.khsglass.com

---

## 📊 Status

- ✅ Website live at khsglass.com
- ✅ AI chatbot running (Hebrew/Arabic/English)
- ✅ CI/CD pipeline via GitHub Actions
- ✅ PostgreSQL database on Railway
- 🔄 Admin panel in development
- 📋 Authentication system planned

---

## 🔗 Maintained By

Managed and maintained by [Abdalla Mahamid](link).
