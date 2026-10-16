<div align="center">

# DEV-codeNexus

### We build at hackathon speed and ship real products.

*A team of developers turning 48-hour ideas into working platforms across healthcare, AI, security, and social impact.*

[![GitHub](https://img.shields.io/badge/GitHub-DEV--codeNexus-181717?style=for-the-badge&logo=github)](https://github.com/DEV-codeNexus)
![Projects](https://img.shields.io/badge/Projects-6-6f42c1?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-Hackathons%20%26%20Real%20Products-ff6f00?style=for-the-badge)

</div>

---

## Who We Are

**DEV-codeNexus** (also known as **CODE_NEXUS**) is a developer collective that competes in hackathons and keeps building after the judging ends. We like hard, real-world problems: maternal health in low-connectivity clinics, price fraud on online marketplaces, national risk monitoring, and making sure rescued animals find homes that last.

Every project here started as a challenge and was built to work end to end, with ML pipelines, role-based systems, offline support, and real integrations.

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌸 [BloomCare](https://github.com/DEV-codeNexus/BloomCare)
**AI-powered maternal healthcare platform**

Early risk screening and clinical triage for **preeclampsia, gestational diabetes, and preterm birth**, built for low-connectivity clinics.

- Offline-first Stage 1 screener (web + mobile) with sync on reconnect
- Server-side Stage 2 diagnostics with explainable AI (SHAP)
- Portals for frontline staff, doctors, patients, and admins
- Multilingual UI: English, Sinhala, Tamil

`Next.js` `FastAPI` `PostgreSQL` `React Native` `scikit-learn`

</td>
<td width="50%" valign="top">

### 🛡️ [VerifyShelf](https://github.com/DEV-codeNexus/verifishelf)
**Brand protection against MAP price violations** · *ProxyMaze Hackathon*

Monitors marketplace listings for **Minimum Advertised Price** violations, scores them with ML, and generates evidence-backed enforcement letters.

- Geo-targeted residential/ISP proxy crawling (live on Daraz)
- XGBoost violation scoring + semantic title matching
- Seller fingerprinting across renamed storefronts
- AI-drafted letters, Playwright screenshots, PDF reports

`Next.js` `FastAPI` `Celery` `Redis` `XGBoost` `Playwright`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗺️ [National Risk Intelligence Platform](https://github.com/DEV-codeNexus/National-Risk-Intelligence-Platform)
**Real-time risk intelligence for Sri Lanka (MODEL-X)**

Continuously collects news and social signals from 9+ sources, scores risk, and visualizes it on live dashboards.

- RSS, Reddit, GDELT, and World Bank data collection
- Deterministic 1–10 risk scoring (sentiment, crisis keywords, source reliability)
- Geospatial risk map, analytics, and a live risk feed
- Anomaly detection and 7-day forecasting

`Python` `Streamlit` `SQLite` `Pydeck` `VADER`

</td>
<td width="50%" valign="top">

### 🔌 [ProxyMaze](https://github.com/DEV-codeNexus/ProxyMaze26)
**Real-time proxy pool monitoring API** · *ProxyMaze '26*

An HTTP API that health-checks proxy pools continuously and raises alerts when the pool starts failing.

- Live up/down tracking with per-proxy history
- Alert state machine that fires at a 20% failure rate and resolves on recovery
- Webhook delivery with retries, backoff, and deduplication
- Slack and Discord integrations, metrics, and a dashboard

`Node.js` `Express` `Webhooks`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🐾 PawMatch: *Smarter Adoptions, Happier Endings*
**Lifestyle-based pet adoption platform** · [Backend](https://github.com/DEV-codeNexus/PawMatchbackend) · [Frontend](https://github.com/DEV-codeNexus/PawMatchFront)

PawMatch matches pets with adopters by **lifestyle compatibility**, not just listings, so fewer pets are returned and more adoptions last.

- **Pawsonality engine** scores activity, time, space, experience, existing pets, and neighborhood, with hard safety filters
- **Buddy-check** matches temperament against pets already in the home
- Sri Lankan NIC verification for adopters and document review for shelters
- Adoption workflow, foster-to-adopt, shelter visits, and in-app messaging
- 90-day post-adoption **welfare tracker**, community animal reports, and achievements

`Next.js` `TypeScript` `Tailwind CSS` `shadcn/ui` `Node.js` `Express` `MySQL` `Cloudinary` `Twilio`

</td>
</tr>
</table>

---

## 🛠️ Our Tech Stack

<div align="center">

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)

**Data & ML**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**DevOps & Integrations**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white)

</div>

---

## What Drives Us

| | |
|---|---|
| **Local impact** | Many of our projects target Sri Lanka and South Asia directly, with multilingual UIs, NIC verification, and local data sources. |
| **Applied AI** | We use ML where it actually helps: explainable clinical risk models, violation classifiers, sentiment-based risk scoring. |
| **Built for reality** | Offline-first apps, retry and backoff logic, and graceful fallbacks, because real conditions are messy. |
| **Hackathon speed, product quality** | We ship fast, then keep going with role-based access, security hardening, and testing. |

---

## Get Involved

- ⭐ **Star** any project you find useful
- 🐛 **Open an issue** if you spot a bug or have an idea
- 🔀 **Send a pull request** — contributions are welcome

---

<div align="center">

### 💡 *Code. Connect. Create.*

**Made with ❤️ by the DEV-codeNexus team**

</div>
