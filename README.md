<div align="center">
  <h1>⎋ AI Decision Systems Portfolio</h1>
  <p><b>Production AI systems executing real-time decisions under latency, capital, and risk constraints</b></p>

  <img src="https://img.shields.io/badge/Execution-%3C100ms-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Production_Code-73k%2B-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Architecture-Multi--system-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/API_Cost_Reduction-98%25-success?style=for-the-badge" />
</div>

<br/>

## 🧠 Overview

This repository showcases **production-grade AI decision systems** that convert real-time data into **actionable execution**. The focus is on **systems that make decisions and act on them**, not models in isolation.

> ⚠️ **These are not experiments.**  
> They are **live system architectures** designed to operate under strict **latency, capital, and risk constraints**.

```mermaid
graph LR
    D[(Data)] --> F(Features)
    F --> C{Decision}
    C --> R[Risk]
    R --> E((Execution))
    E --> M[Monitoring]
    
    style D fill:#f9f,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:4px
    style E fill:#bfb,stroke:#333,stroke-width:2px
```

---

## 🎯 Portfolio Structure

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>☑︎ Capital Decision Systems</h3>
      <p>Systems that <b>directly generate capital growth.</b></p>
    </td>
    <td width="50%" valign="top">
      <h3>⚛︎ Supporting Infrastructure</h3>
      <p>Systems that enable <b>data, execution, and system reliability.</b></p>
    </td>
  </tr>
</table>

---

# ☑︎ Capital Decision Systems

## 1. Easy ORB 0DTE — High-Frequency Capital Allocation System
*Primary production system for capital growth*

A cloud-deployed execution system that:
- 📊 Captures opening range breakout (ORB) structures  
- ⏱️ Evaluates tradeability in real-time  
- ⚡ Executes ETF + 0DTE options trades  

**Key Capabilities:**
- **Scale:** 36,786 lines of production code
- **Logic:** Dual-strategy system (ETF + options overlay) with 14+ automated exit conditions
- **Pricing:** Real-time options pricing (30s updates)
- **Risk:** ADV-based position sizing + risk gating

<details open>
<summary><b>📈 Performance (Validated Backtesting)</b></summary>
<br/>

| Metric | Result |
| :--- | :--- |
| **Weekly Return** | +73.69% |
| **Winning Day Consistency** | 91% |
| **Drawdown Reduction** | 96% |

</details>

<details open>
<summary><b>🛠️ Product Decisions & Insights</b></summary>
<br/>

- 🛡️ Prioritized **capital preservation** over max gain.
- 🚧 Enforced **strict execution gating** over signal chasing.
- ⚖️ Balanced **latency vs. decision quality** under volatility.

> **Insight:** A real system for **decision-making under extreme constraints** (minutes-level timing, capital exposure, volatility uncertainty).
</details>

---

## 2. Easy Kalshibot — Prediction Market Decision System
*A probabilistic decision system for event-driven markets.*

**Core Concepts:**
- 🎲 **Edge Detection:** Probability vs. market pricing 
- 🔄 **Updates:** Bayesian updates from new information  
- 💰 **Allocation:** Kelly-based capital placement  

**Demonstrates:** Decision-making under uncertainty, probability-driven execution, and risk-adjusted capital deployment.

> **Insight:** Markets are treated as **probability surfaces**, not price charts.

---

## 3. Ultima Bot — AI Decision Platform
*A full-stack AI system orchestrating discovery, scoring, forecasting, risk management, and execution.*

**Core Pipeline:**
```mermaid
flowchart LR
    A[Discovery] --> B[Features]
    B --> C[Model]
    C --> D[Forecast]
    D --> E[Risk]
    E --> F[Execution]
    F --> G[Auto-Close]
```

**Key Capabilities:**
- 🏦 Multi-broker + DeFi wallet execution
- 🧠 ML model orchestration (7+ production models)
- ⚡ Real-time WebSocket system (<100ms latency)
- 📈 Confidence-based capital scaling

> **Role:** The **unified decision platform** that integrates data pipelines, models, and execution systems into a single operating system for capital allocation.

---

# ⚛︎ Supporting Infrastructure

## 4. Easy TradingView Agent — Execution Layer
*A production-grade system converting signals → broker execution.*

- **Webhook Pipeline:** Automated end-to-end execution
- **Multi-broker Routing:** With virtual partition system
- **Reliability:** Idempotent execution + reconciliation

> **Role:** Ensures **decision → execution reliability**. *(Not a strategy system)*

---

## 5. Easy Collector — Data & Feature Pipeline
*A cloud-native pipeline for ML training and feature generation.*

- **Ingestion:** Real-time data via Polygon, Coinbase
- **Labeling:** Edge-based labeling formula:  
  `edge = MFE - (k * MAE) - cost_penalty`
- **Efficiency:** 98% API cost reduction through idempotent storage caching

> **Role:** Provides **ML-ready datasets**. *(Not a trading system)*

---

# 🏗️ Architecture Philosophy

```mermaid
flowchart TD
    A[(Data Sources)] -->|Ingestion| B(Feature Engineering)
    B -->|Features| C{Decision Layer}
    C -->|Calculated Edge| D[Risk Constraints]
    D -->|Approved Sizing| E((Execution Layer))
    E -.->|Market Impact| A
    E --> F[Monitoring & Feedback]
    
    style A fill:#f9d0c4,stroke:#333
    style C fill:#bbf,stroke:#333
    style D fill:#ffb3ba,stroke:#333
    style E fill:#bfb,stroke:#333
```

### Core Principles
- 🎯 **Decisions > predictions:** Models must trigger action.
- 🚧 **Constraints define reality:** Latency, capital, and risk bound the solution space.
- ⚙️ **Deterministic execution:** Verifiable and strictly monotonic state transitions.
- 🧩 **Separation of concerns:** Data, strategy, risk, and execution are decoupled.
- 🛡️ **Fail-safe systems:** Graceful degradation is a primary requirement.

---

# 📊 Portfolio Scale

<div align="center">
  <img src="https://img.shields.io/badge/Lines_of_Production_Code-73%2C000%2B-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Classes-379-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Functions-2%2C484-orange?style=for-the-badge" />
</div>

<br/>

**Multi-system architecture seamlessly spans across:**
- ⚡ Execution Systems
- 🧠 ML Pipelines
- 💻 Full-Stack Applications

---

# 🎯 Target Roles

This portfolio powerfully advocates for capability in:
- 🥇 **Senior Technical Product Manager (AI/ML)**
- 🥈 **AI Platform Product Manager**
- 🥉 **Decision Systems / Infrastructure PM**

---

# 🧠 Core Thesis

<div align="center">
  <h3><em>"AI systems that matter are not models."</em></h3>
  <p>They are <b>decision systems operating under constraints</b>.</p>
</div>

---

<div align="center">
  
## 🚀 Contact
  
  <a href="#"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a> 
  <a href="#"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a> 
  <a href="#"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  
</div>
