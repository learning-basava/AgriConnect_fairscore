# AgriConnect — FairScore™
### Google Solution Challenge 2026 · Problem Statement 04 · Unbiased AI Decision Making

---

## 🔴 The Problem

AgriConnect's own AgriScore™ algorithm was giving women farmers 23% lower scores than men with identical land, yield, and payment history.

Root cause: a Training Completion criterion (18% weight) that measured **travel access — not farming skill**. 94% of women farmers live 8km+ from training venues with no independent transport.

---

## ✅ The Solution — FairScore™

FairScore™ is a bias audit engine built into AgriConnect. It:

- Runs **Demographic Parity, Disparate Impact, and Equalised Odds** metrics across gender, irrigation type, caste, and district
- Uses **Gemini 1.5 Pro** to explain every bias finding in plain language — to admins AND to farmers in Kannada, Hindi, or English
- Lets admins **recalibrate AgriScore™ feature weights in real time**
- Provides a **Farmer View** — farmers can ask "Why is my score low?" in their own language

---

## 🚀 Live Demo

👉 **[Add your Netlify link here after deploying]**

---

## 💻 How to Run Locally

1. Download all files from this repository
2. Open `fairscore_index.html` in any browser — this is the PS04 submission
3. Open `index.html` for the full AgriConnect platform
4. No server required. No installation. Works 100% offline.

---

## 🔑 Demo Login Credentials

| Portal | Email | Password |
|--------|-------|----------|
| Farmer | farmer@agriconnect.in | Farmer@123 |
| Landlord | landlord@agriconnect.in | Land@123 |
| Marketplace | buyer@agriconnect.in | Market@123 |
| Admin | admin@agriconnect.in | Admin@2025 |

---

## 📁 File Guide

| File | What It Is |
|------|------------|
| index.html | Landing Hub — full platform entry point |
| farmer_index.html | Farmer Portal |
| landlord_index.html | Landlord Portal |
| marketplace_index.html | Marketplace |
| admin_index.html | Admin Panel |
| fairscore_index.html | **FairScore™ — PS04 Bias Audit (START HERE)** |

---

## 🔧 Google Technologies Used

| Technology | Purpose |
|------------|---------|
| Gemini 1.5 Pro | Bias explanations in Kannada, Hindi, Telugu, English |
| Vertex AI | Fairness metrics — demographic parity, equalised odds |
| BigQuery | 3,247 farmer records analysed at scale |
| Firebase | Real-time audit history, notifications, auth |
| Cloud Run | Python fairness microservice — Fairlearn + AIF360 |
| Flutter | Cross-platform farmer app — web, Android, iOS |

---

## 🌾 About AgriConnect

India's first farm-to-table ecosystem. Three pillars — Land Exchange, Direct Marketplace, Agri Partnership. Zero brokers. FairScore™ ensures our own AI never becomes a new source of injustice.

**Pilot:** Karnataka, India — Tumkur · Kolar · Ramanagara

*Built for Google Solution Challenge 2026*
