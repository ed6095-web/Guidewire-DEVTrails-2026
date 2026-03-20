<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=42&pause=1000&color=00FFCC&center=true&vCenter=true&width=800&lines=ShieldGig;AI-Powered+Income+Protection;Parametric+Insurance+System" alt="Animated Header" />
</div>

<p align="center">
  <b>Phase 1 Strategy & System Concept</b><br>
  <i>A data-driven safety net for India's gig economy</i>
</p>

---

# 📌 Problem Statement

India’s gig economy relies on delivery partners who earn daily wages based on completed deliveries.

Income is vulnerable to **external disruptions** such as:

- Heavy Rain  
- Extreme Heatwaves  
- Severe Air Pollution  
- Mobility Restrictions  
- Platform Activity Anomalies  

These events can reduce weekly income by **20–30%**, with no existing real-time protection system.

---

# Proposed Concept

ShieldGig is a **parametric micro-insurance system** that automates income protection using real-time external signals.

Unlike traditional insurance, ShieldGig eliminates claim delays by using **predefined parametric triggers**, enabling **instant and unbiased payouts**.

---

# Core Mechanism

The system converts real-world disruptions into **quantified income risk**, then triggers payouts automatically.

---

# Decision Engine (Core Innovation)

ShieldGig uses a **multi-factor weighted decision model**, not simple rule-based triggers.

```text
Risk Score =
(Environment × 0.4) +
(Platform × 0.4) +
(Mobility × 0.2)
```

Weights are dynamically adjusted using historical correlation between disruptions and income loss.

### Payout Logic

```text
Risk > 70 → High Payout  
40–70 → Partial Payout  
< 40 → No Payout  
```

---

# Decision Tree Model

```mermaid
flowchart TD

A[Start Monitoring] --> B{Disruption Detected?}

B -- No --> A

B -- Yes --> C{Disruption Type}

C -->|0.4| D[Environmental]
C -->|0.4| E[Platform Activity]
C -->|0.2| F[Mobility Restriction]

D --> G[Evaluate Severity]
E --> G
F --> G

G --> H{Impact on Earnings}

H -- Low --> I[No Payout]

H -- Medium --> J[Partial Risk]

H -- High --> K[High Risk]

J --> L[Compute Risk Score]
K --> L

L --> M{Risk > Threshold?}

M -- No --> I
M -- Yes --> N[Trigger Payout]

N --> O[Wallet Credit]
I --> P[Continue Monitoring]
O --> P
P --> A
```

---

# Parametric Triggers

| Category | Trigger | Condition | Payout |
|----------|--------|----------|--------|
| Environmental | Rain | Rainfall > 60mm | ₹250 |
| Environmental | Heat | Temperature > 45°C | ₹200 |
| Environmental | Pollution | AQI > 400 | ₹150 |
| Platform | Activity Anomaly | Proxy-based demand drop / downtime | ₹350 |
| Mobility | Restriction | Route blockage / restricted zone | ₹300 |

---

# Data & Feasibility

- Weather → Public APIs  
- Mobility → Traffic APIs  
- Platform signals → **Proxy indicators (order density, time-based demand simulation)**  

This ensures feasibility without relying on proprietary platform data.

---

# Risk & Pricing Logic

Premiums are calibrated to maintain a **balanced loss ratio**, ensuring system sustainability.

| Tier | Weekly Premium | Coverage |
|------|--------------|----------|
| Basic | ₹25 | ₹500 |
| Standard | ₹40 | ₹1000 |
| Pro | ₹60 | ₹1800 |

---

# Fraud Prevention

- GPS-based location validation  
- Cross-verification with API data  
- Duplicate claim prevention  

Example: Claims from unaffected zones are automatically rejected.

---

# System Architecture

- Frontend: React / Next.js  
- Backend: Node.js  
- Database: MongoDB  
- AI: Python (Scikit-learn)  
- APIs: Weather, Traffic  
- Payments: Razorpay Sandbox  

---

# Key Insight

ShieldGig does not insure events.

It insures **income impact caused by those events**.

---

# Vision

From claim-based insurance to **trigger-based protection**.
