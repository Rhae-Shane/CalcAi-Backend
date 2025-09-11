# CalcAI Backend 🔧⚡

Backend API for **CalcAI** — the intelligent calculator. This service powers the frontend hosted at: [https://calcai-rhae.vercel.app/](https://calcai-rhae.vercel.app/)

> Minimal, focused README for the backend service. Includes quick start, core endpoints, environment variables, and links.

---

## Overview

A lightweight Express.js service that evaluates expressions, handles AI-enhanced problem solving, stores calculation history, and exposes a small set of REST endpoints for the CalcAI frontend.

---

## Quick Start

```bash
git clone https://github.com/Rhae-Shane/CalcAi-Backend.git
cd CalcAi-Backend
npm install
cp .env.example .env   # edit .env
npm run dev
```

API default: `http://localhost:3001`

---



---

## Important Endpoints (summary)

* `POST /api/calculate` — Evaluate a math expression (basic/scientific)
* `POST /api/calculate/advanced` — Advanced/special functions
* `POST /api/ai/solve` — AI-powered problem solving (returns solution + steps)
* `POST /api/ai/parse` — Parse natural-language math queries
* `GET /api/history` — List calculation history (auth required)
* `POST /api/history` — Save a calculation record (auth required)

Detailed OpenAPI/Swagger is available in `/docs` when running locally at `/api-docs`.

---

## Notes

* The backend is designed to be containerized (Dockerfile included).
* Use the provided `.env.example` to wire AI keys and DB connection.
* CORS is preconfigured for the frontend hosted at `https://calcai-rhae.vercel.app`.

---

## Links

* Frontend (GitHub): [https://github.com/Rhae-Shane/CalcAi](https://github.com/Rhae-Shane/CalcAi)
* Live frontend: [https://calcai-rhae.vercel.app/](https://calcai-rhae.vercel.app/)
* Backend (this repo): [https://github.com/Rhae-Shane/CalcAi-Backend](https://github.com/Rhae-Shane/CalcAi-Backend)

---

## Author

**Rhae Shane** — GitHub: [https://github.com/Rhae-Shane](https://github.com/Rhae-Shane)

---

⭐ Star the repos if you find them useful.
