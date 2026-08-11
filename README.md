<div align="center">

# Full-Stack Developer

`Python` · `Django` · `DRF` · `JavaScript` · `PostgreSQL` · `Docker`

Building production web applications, REST APIs and background systems.<br>
Backend architecture, database design, third-party integrations, deployment.

</div>

---

```text
$ whoami

Full-Stack Developer — backend-oriented

$ stack --core

  backend      Python · Django · Django REST Framework
  frontend     JavaScript ES6+ · HTML5 · CSS3 · Tailwind · Webpack
  data         PostgreSQL · Redis
  async        Celery
  infra        Docker · Nginx · Linux · Git

$ focus

  Designing and shipping real-world web systems:
  REST APIs, relational data models, background processing,
  external API synchronization and production deployment.

$ status

  BUILDING
```

---

## Tech Stack

**Backend**

![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3776AB)
![Django](https://img.shields.io/badge/Django-0D1117?style=flat-square&logo=django&logoColor=44B78B)
![DRF](https://img.shields.io/badge/Django%20REST%20Framework-0D1117?style=flat-square&logo=django&logoColor=A30000)
![Celery](https://img.shields.io/badge/Celery-0D1117?style=flat-square&logo=celery&logoColor=37814A)

**Frontend**

![JavaScript](https://img.shields.io/badge/JavaScript-0D1117?style=flat-square&logo=javascript&logoColor=F7DF1E)
![HTML5](https://img.shields.io/badge/HTML5-0D1117?style=flat-square&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-0D1117?style=flat-square&logo=css3&logoColor=1572B6)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-0D1117?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![Webpack](https://img.shields.io/badge/Webpack-0D1117?style=flat-square&logo=webpack&logoColor=8DD6F9)

**Data & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1)
![Redis](https://img.shields.io/badge/Redis-0D1117?style=flat-square&logo=redis&logoColor=FF4438)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED)
![Nginx](https://img.shields.io/badge/Nginx-0D1117?style=flat-square&logo=nginx&logoColor=009639)
![Linux](https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=FCC624)
![Git](https://img.shields.io/badge/Git-0D1117?style=flat-square&logo=git&logoColor=F05032)

**APIs & Integrations**

![REST API](https://img.shields.io/badge/REST%20API-0D1117?style=flat-square&logo=fastapi&logoColor=A0A0A0)
![Telegram](https://img.shields.io/badge/Telegram%20Mini%20Apps-0D1117?style=flat-square&logo=telegram&logoColor=26A5E4)
![MoySklad](https://img.shields.io/badge/MoySklad%20API-0D1117?style=flat-square&logo=json&logoColor=A0A0A0)

---

## Featured Project — MARVA

**Telegram Mini App / e-commerce platform for dental supplies.**

Full-cycle system: Django backend with a REST API, custom JavaScript frontend
bundled with Webpack, PostgreSQL data layer, Redis-backed Celery workers for
background jobs, and a synchronization pipeline against an external ERP
(MoySklad) — running in Docker behind Nginx.

```text
architecture
├── backend      Django · DRF · PostgreSQL
├── async        Celery · Redis
├── frontend     JavaScript ES6+ · Tailwind CSS · Webpack
├── auth         Telegram Login / Mini App initData
├── integration  MoySklad API (products · stock · images)
└── runtime      Docker · Nginx · Linux
```

**Core functionality**

| Domain | Implementation |
| :-- | :-- |
| Catalog | Product listing, search, filtering, product detail pages |
| Commerce | Cart, checkout flow, order handling |
| Accounts | Telegram authentication, user profile, favorites |
| Sync | Product, stock and image synchronization with MoySklad |
| Async | Scheduled and queued background tasks via Celery |
| API | REST endpoints consumed by the Mini App frontend |

**Engineering notes** — API-first design with a clear backend/frontend boundary;
external ERP data normalized into the local schema instead of proxied at request
time; long-running sync moved off the request cycle into workers; the whole stack
reproducible via a single Docker composition.

---

## Engineering

```text
API-first development          Contracts defined before UI; frontend consumes REST only.
Clean separation               Backend, frontend and async workers as independent layers.
Relational data modeling       Normalized schemas, migrations, indexed queries.
Background processing          Queues and periodic tasks for anything slow or external.
Third-party integrations       External APIs treated as unreliable: retries, idempotency, logging.
Production debugging           Logs, container inspection, reproducing issues on real data.
Deployment                     Docker images, Nginx reverse proxy, Linux servers.
Git workflow                   Branch-based development, reviewable commits.
```

---

## Currently Building

- **LOYSBOY98** — CRM Telegram Mini App e-commerce platform (Django · DRF · PostgreSQL · Celery · MoySklad)
- Deepening Django internals, query optimization and async task architecture

---

## GitHub

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=loysboy98&show_icons=true&hide_border=true&bg_color=0D1117&title_color=FFFFFF&text_color=A0A0A0&icon_color=44B78B)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=loysboy98&layout=compact&hide_border=true&bg_color=0D1117&title_color=FFFFFF&text_color=A0A0A0&langs_count=8)

</div>

---

```text
┌──────────────────────────────────────────────┐
│ developer@localhost:~/loysboy98              │
│                                              │
│  $ git status                                │
│  $ python manage.py test                     │
│  $ npm run build                             │
│  $ docker compose up -d                      │
│  $ git push origin main                      │
│                                              │
│  STATUS: BUILDING                            │
└──────────────────────────────────────────────┘
```

---

## Contact

[![Telegram](https://img.shields.io/badge/Telegram-0D1117?style=flat-square&logo=telegram&logoColor=26A5E4)](https://t.me/YOUR_TELEGRAM)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://linkedin.com/in/YOUR_PROFILE)
[![Email](https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:YOUR_EMAIL)
