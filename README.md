# 🚀 AI Decision Systems Portfolio

---

## 🧠 Overview

This repository showcases **production-grade AI systems** that convert real-time data into **automated decisions and execution** under real-world constraints.

These are not experiments or notebooks.

They are **end-to-end decision systems** designed to operate continuously in live environments:
Data → Features → Model → Decision → Risk → Execution → Monitoring


The focus is on **systems that act**, not just models that predict.

---

## 🎯 What This Portfolio Demonstrates

- Designing **AI systems that operate under constraints** (latency, capital, risk)
- Translating ML outputs into **real-world decisions**
- Building **end-to-end production pipelines**
- Operating **continuous, event-driven systems**
- Delivering **product-grade infrastructure**, not isolated models

---

## 🧩 Core Systems

---

### 1. Ultima Bot — AI Trading Decision System

A full-stack **AI decision infrastructure for capital allocation** across crypto, equities, and DeFi wallets.

**Core pipeline:**
Discovery → Features → Model → Forecast → Risk → Execution → Auto-Close


**Key capabilities:**

- Multi-broker + wallet execution (CEX + DeFi)
- Real-time WebSocket telemetry and dashboard
- Risk-governed capital allocation and position sizing
- Forecast-driven trade structuring (TP/SL, trailing logic)
- Continuous async trading loop (runs headless after activation)

**Key principle:**

Ultima Bot is not a single model.

It is a **capital allocation system**, where:

- Model → filters opportunities  
- Forecast → defines trade structure  
- Risk → enforces constraints  
- Execution → performs actions  

The system’s edge comes from the **interaction of these layers**, not the model alone.

---

### 2. Easy TradingView Agent — Execution Infrastructure

A **production-grade execution system** that converts TradingView signals into deterministic broker actions.

**What it solves:**

Trading signals often fail in real-world execution due to:

- latency  
- missed or duplicated alerts  
- manual intervention  
- unreliable exits  

**Key capabilities:**

- Webhook → execution pipeline
- Margin-aware position sizing
- Idempotent order handling
- Redundant exit monitoring (agent + webhook)
- Real-time alerts and monitoring

**System role:**

This is the **execution layer**, ensuring strategies actually translate into **reliable outcomes**.

---

### 3. Easy Collector — Data & Feature Pipeline

A **production-grade data pipeline** that generates ML-ready datasets for decision systems.

**Core functions:**

- Real-time market data ingestion (Polygon, Coinbase)
- Feature engineering (technical + session-based signals)
- Edge-based labeling:
edge = MFE - k * MAE - cost_penalty


- Idempotent snapshot storage (Firestore)
- Cloud-native orchestration (Cloud Run + Scheduler)

**Key achievements:**

- ~98% reduction in API calls through caching architecture  
- Designed for **ML trainability and decision alignment**

---

## 🏗️ Architecture Philosophy

All systems follow a shared decision-system architecture:
Data Sources
↓
Feature Engineering
↓
Model / Scoring
↓
Decision Layer
↓
Risk & Constraints
↓
Execution Layer
↓
Monitoring & Feedback


### Core Principles

- **Systems > Models**  
  Value comes from full pipelines, not isolated ML

- **Constraints define behavior**  
  Latency, capital, and risk shape decisions

- **Deterministic execution**  
  Idempotency and contract-driven systems

- **Separation of concerns**  
  Discovery, modeling, risk, and execution are independent layers

- **Fail-safe design**  
  Systems prioritize controlled outcomes over theoretical performance

---

## ⚙️ Technology Stack

**Backend**
- FastAPI, async Python
- WebSockets for real-time systems
- Event-driven architecture

**Frontend**
- React, Vite, Tailwind
- Real-time dashboards and control planes

**Infrastructure**
- Docker, GCP Cloud Run
- Firestore / PostgreSQL
- Cloud Scheduler

**ML / Data**
- scikit-learn (production models)
- Feature pipelines + labeling systems
- Model registry + runtime contracts

---

## 📊 What Makes This Portfolio Different

Most AI portfolios show:

- notebooks  
- experiments  
- model accuracy  

This portfolio shows:

- systems that **make decisions**
- systems that **execute those decisions**
- systems that **run continuously in production**

---

## 🧪 Validation & Reality

- Backtests and simulations provide **directional insight**
- Production systems require:
  - replay testing  
  - forward testing  
  - contract validation  

**Live performance is governed by system behavior, not model accuracy alone.**

---

## 📁 Repository Structure
ai-decision-systems-portfolio/
├── ultima-bot/
├── tradingview-agent/
├── easy-collector/
├── docs/
│ ├── prd/
│ ├── architecture/
│ ├── roadmap/
│ └── frameworks/
└── README.md


---

## 🎯 Target Roles

This portfolio is designed to demonstrate capability for:

- Senior Technical Product Manager (AI/ML)
- AI Platform Product Manager
- Decision Systems / Infrastructure PM

---

## 🧠 Core Thesis

AI systems that matter are not models.

They are **decision systems operating under constraints**.

This portfolio demonstrates how to:

- design them  
- build them  
- operate them  
- and improve them  

---

## 🚀 Contact

- LinkedIn: *(add link)*
- GitHub: *(add link)*
- Portfolio: *(add site link)*
