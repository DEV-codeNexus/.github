<div align="center">

# DEV-codeNexus

A developer team building software for hackathons and real-world problems,<br>
with a focus on healthcare, applied machine learning, and data platforms.

</div>

---

## About

DEV-codeNexus (CODE_NEXUS) is a team that competes in hackathons and develops the resulting projects into complete, working systems. Our work spans maternal healthcare, marketplace brand protection, national risk monitoring, infrastructure tooling, and animal welfare. Many of these projects are built for Sri Lanka and South Asia.

## Projects

| Project | Description | Stack |
| --- | --- | --- |
| [BloomCare](https://github.com/DEV-codeNexus/BloomCare) | AI-assisted maternal healthcare platform for risk screening and clinical triage | Next.js, FastAPI, PostgreSQL, React Native, scikit-learn |
| [VerifyShelf](https://github.com/DEV-codeNexus/verifishelf) | Brand protection platform that detects Minimum Advertised Price violations on online marketplaces | Next.js, FastAPI, Celery, Redis, XGBoost, Playwright |
| [National Risk Intelligence Platform](https://github.com/DEV-codeNexus/National-Risk-Intelligence-Platform) | Real-time risk monitoring for Sri Lanka built from news and social data | Python, Streamlit, SQLite, Pydeck |
| [ProxyMaze](https://github.com/DEV-codeNexus/ProxyMaze26) | HTTP API for real-time proxy pool health monitoring and alerting | Node.js, Express |
| 🐾 PawMatch ([Backend](https://github.com/DEV-codeNexus/PawMatchbackend), [Frontend](https://github.com/DEV-codeNexus/PawMatchFront)) | Pet adoption platform that matches pets with adopters based on lifestyle compatibility | Next.js, TypeScript, Node.js, Express, MySQL |

---

### 🌸 BloomCare

A maternal healthcare platform for low-connectivity clinical environments. An offline-first screener on web and mobile handles initial triage. Server-side models then assess preeclampsia, gestational diabetes, and preterm birth risk, with explanations for each result.

- Offline screening with a local queue that syncs on reconnect
- Separate portals for frontline staff, clinicians, patients, and administrators
- Appointments, prescriptions, and longitudinal tracking of vital signs
- Interface available in English, Sinhala, and Tamil

### 🛡️ VerifyShelf

*Built for the ProxyMaze hackathon.*

A monitoring platform that helps brands enforce Minimum Advertised Price (MAP) policies on third-party marketplaces. It crawls listings through geo-targeted residential proxies, flags violations with a trained classifier, and generates evidence for enforcement.

- Scheduled marketplace crawls with price history (live on Daraz)
- XGBoost violation scoring with semantic product matching
- Seller fingerprinting to link storefronts that have changed names
- Generated enforcement letters, listing screenshots, and weekly PDF reports

### 🗺️ National Risk Intelligence Platform

A risk intelligence dashboard for Sri Lanka. It continuously collects data from RSS feeds, Reddit, GDELT, and World Bank indicators, then scores each item for risk.

- Deterministic risk scoring based on sentiment, crisis terms, and source reliability
- Geospatial risk map, analytics, and a live feed of the highest-risk items
- Anomaly detection and seven-day forecasting
- Monitoring of source health and data collection

### 📡 ProxyMaze

An API service that continuously health-checks a pool of proxies and manages alerts based on the pool's failure rate.

- Per-proxy status tracking with check history
- Alerts that fire when 20% of proxies fail and resolve on recovery
- Webhook delivery with retries, backoff, and deduplication
- Slack and Discord integrations, metrics endpoint, and dashboard

### 🐾 PawMatch

*Smarter adoptions, happier endings.* 🐶🐱

An adoption platform that matches pets and adopters on lifestyle factors rather than browsing alone, with the aim of reducing returns.

- Compatibility scoring based on activity level, available time, living space, experience, and existing pets
- Verification for adopters and shelters, with review by administrators
- Adoption applications, foster-to-adopt, shelter visits, and messaging
- 90-day post-adoption welfare tracking and community animal reports

---

## Technologies

| Area | Tools |
| --- | --- |
| Frontend | Next.js, React, React Native, TypeScript, Tailwind CSS, Streamlit |
| Backend | Python, FastAPI, Node.js, Express, Celery |
| Data | PostgreSQL, MySQL, Redis, SQLite |
| Machine Learning | scikit-learn, XGBoost, PyTorch, sentence-transformers |
| Infrastructure | Docker, Playwright, Cloudinary, Twilio, SendGrid |

---

## Contributing

Issues and pull requests are welcome on any of our repositories. If you are organizing a hackathon or want to collaborate, open an issue or reach out through GitHub.
