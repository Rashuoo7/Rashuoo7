<h1 align="center">Hey, I'm Rashtradeep Tripathi 👋</h1>

<p align="center">
  <b>Senior Software Engineer · Full Stack & AI-Integrated Backend</b><br/>
  Laravel · Angular · Vue · React · Node.js · Python · LangChain · AWS · GCP
</p>

<p align="center">
  <a href="https://linkedin.com/in/rashtradeep-tripathi">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:rashtradeeptripathi@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Status-Open%20To%20Work-brightgreen" />
  <img src="https://img.shields.io/badge/Experience-7%2B%20Years-orange" />
</p>

---

### 👨‍💻 About Me

- 🏗️ **7+ years** shipping production Full Stack & Backend systems across **8 industry domains**
- ✈️ Recently shipped **iPronto**'s shuttle operations console (Angular 22) and complex booking APIs, plus a **website + admissions CRM** for Air World Academy
- 🤖 Built two AI products: an **AI video generation platform** (NGFlix) and a **RAG insurance chatbot**
- 💼 Senior Software Engineer at **Arihant Web Consultancy** since June 2024
- 🏠 Based in **India** · Open to remote roles and product companies

---

### 🛠️ Tech Stack

**Backend**

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP%208-777BB4?logo=php&logoColor=white)
![Filament](https://img.shields.io/badge/Filament-FDAE4B?logoColor=black)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![REST API](https://img.shields.io/badge/REST-APIs-orange)

**Frontend**

![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)

**AI & Python**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logoColor=white)
![RAG](https://img.shields.io/badge/RAG-Architecture-blueviolet)
![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?logo=ffmpeg&logoColor=white)

**Cloud, Data & DevOps**

![AWS](https://img.shields.io/badge/AWS-EC2%20·%20S3%20·%20RDS%20·%20CloudFront-232F3E?logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-Cloud%20Run-4285F4?logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=github-actions&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)

---

### 🚀 Recent Work

#### 🚌 iPronto: Event Travel & Shuttle Platform *(Laravel API · Angular 22 · AWS)*
[ipronto.com](https://ipronto.com) · game-day shuttles and group outings in the US
- Built **admin.ipronto.com**, the operations console: **Angular 22** with standalone components, signals, strict TypeScript and Vitest, served from S3 + CloudFront. It covers bookings, fleet, drivers, manifests and live dashboards.
- Added a phone-first **driver boarding app** with QR ticket scanning (native `BarcodeDetector` with a `jsqr` fallback). Drivers never see passenger contact details.
- Designed the **role-gated admin API** in Laravel, with a vehicle-based capacity model and a test that fails the build if any admin route is left ungated.
- Built the full **QR ticket → check-in** flow and redesigned 26 transactional emails.
- Performance work on a shared RDS instance: one targeted index took dashboard queries on a 500K-row table from **88 ms to 20 ms**. Also moved legacy SQL to bound parameters.
- Shipped features and fixes in the customer Angular app (SSR, NgRx, PWA).

#### ✈️ Air World Academy: Website + Admissions CRM
- **[airworldacademy.in](https://airworldacademy.in)**: marketing site built with **Vue 3 · Vite · Tailwind**. It replaced the old WordPress site and sends every enquiry straight to the CRM.
- **[crm.airworldacademy.in](https://crm.airworldacademy.in)**: admissions CRM built from scratch on **Laravel 13 · Filament 5 · PHP 8.4 · MySQL**
  - Lead intake from Meta, Google, Justdial, WhatsApp, the website and walk-ins, through webhooks
  - Duplicate detection on normalised phone numbers: an indexed exact match that warns without blocking the save
  - Installable on phones, with web-push notifications · **223 automated tests**

#### 🎬 NGFlix: AI Video Generation *(Node.js · React · FFmpeg · GCP Cloud Run)*
Generates multi-scene videos from text prompts. Scenes are stitched and audio merged on the server with FFmpeg, and long renders run through a job queue on Cloud Run.

#### 🤖 Insurance AI Chatbot *(Python · LangChain · RAG · Docker · AWS EC2)*
Turns plain-English questions into SQL over a **100,000+ record** database, with ~90% accuracy on domain questions. Guardrails block destructive queries.

---

### 🏭 Industries I've Built For

| Industry | Projects |
|----------|----------|
| 🚌 Travel & Events | iPronto: shuttle ops console, booking API |
| ✈️ Aviation Education | Air World Academy: website + admissions CRM |
| 🎬 AI / Media | NGFlix: AI video generation |
| 🛡️ Insurance | TCCI Portal · AI Insurance Chatbot |
| 🏥 Healthcare | Nemicare: electronic medical records (EMR) |
| 🎓 Ed-Tech | PCS Simplified (20,000+ students) · Simplified Academy |
| 💰 Fintech / SaaS | Invoices SaaS · Credzee |
| ⚡ Energy | APG Energy: utility data & reporting |
| 🛒 E-Commerce | Genius.TV: German headless commerce (Commercetools + Contentful) |
| 🏠 Real Estate | HomesInfra · Dreamdraft |

---

### 📂 A Note on My Repositories

Most of my work lives in **private client and company repositories**: production Laravel APIs,
Angular and Vue frontends, AWS/GCP infrastructure and CI/CD pipelines. The contribution graph
reflects **real, daily production commits.** 🟩

---

### 📫 Let's Connect

<p>
  <a href="https://linkedin.com/in/rashtradeep-tripathi">
    <img src="https://img.shields.io/badge/LinkedIn-rashtradeep--tripathi-blue?logo=linkedin" />
  </a>
  &nbsp;
  <a href="mailto:rashtradeeptripathi@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-rashtradeeptripathi-red?logo=gmail" />
  </a>
</p>

- 🎯 Looking for **Senior Full Stack / Backend / AI Engineer** roles
- 💬 Happy to talk Laravel architecture, modern Angular, AI integrations or AWS/GCP deployments
