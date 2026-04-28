# 👋 Welcome to KHS Glass

KHS Glass is an internal platform built to support the operations of a local glass business. It is a fully containerized, microservices-based system designed for reliability, modularity, and scalability.

🔒 Most repositories are private — ongoing commercial project.

---

## 🚀 What We've Built

A full-stack system for managing a glazier business:

- 🤖 AI-powered chatbot (GPT-4o-mini) in Hebrew, Arabic, and English
- 🔐 Authentication via Supabase Auth with secure session cookies
- 🖼️ Gallery management — photo upload, compression, and organization by category
- 🛠️ Admin panel — photo manager, cover selection, currency & discount calculator
- 📷 Image compression pipeline (Sharp/libvips → WebP)
- 🌐 Multilingual UI — Hebrew (RTL), Arabic (RTL), English (LTR)
- ♿ Accessibility compliant (Israeli Standard IS 5568)
- 🛡️ Security — rate limiting, gateway secret, DDoS protection at Nginx layer

---

## 🔧 Technologies

- **Frontend:** React (TypeScript), Tailwind CSS, shadcn/ui
- **Backend:** FastAPI (Python), SQLAlchemy, PostgreSQL
- **AI:** OpenAI GPT-4o-mini
- **Auth:** Supabase Auth (JWT)
- **Storage:** Supabase Storage (gallery photos) + PostgreSQL (sessions, metadata)
- **Gateway:** Nginx (api.khsglass.com)
- **Image processing:** Node.js, Sharp
- **Infrastructure:** Docker, Railway, GitHub Actions CI/CD

---

## 🗂️ Repositories

| Repo | Description | Status |
|---|---|---|
| `frontend` | React + TypeScript website | ✅ Live |
| `chatbot-service` | AI chat via GPT-4o-mini | ✅ Live |
| `control-plane-service` | Sessions, auth, gallery API, rates | ✅ Live |
| `api-gateway` | Nginx routing, CORS, rate limiting | ✅ Live |
| `image-compression-service` | Photo compression to WebP | ✅ Live |

---

## 🌐 Live

- **Website:** https://khsglass.com
- **API:** https://api.khsglass.com

---

## 📊 Status

- ✅ Website live at khsglass.com
- ✅ AI chatbot running (Hebrew / Arabic / English)
- ✅ Admin panel live (photo management, calculator)
- ✅ Authentication live (Supabase)
- ✅ Image compression pipeline live
- ✅ CI/CD pipeline via GitHub Actions
- ✅ PostgreSQL database on Railway
- ✅ Rate limiting and gateway security hardened

---

## 🔗 Maintained By

Managed and maintained by [Abdalla Mahamid](https://github.com/abedkhma).
