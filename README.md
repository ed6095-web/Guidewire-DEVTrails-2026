<p align="center">
  <img src="images/banner.png" alt="ShieldGig Banner" width="900">
</p>

<h1 align="center">ShieldGig</h1>

<p align="center">
  <b>AI-Powered Income Protection for Gig Delivery Workers</b><br>
  <i>Parametric Insurance Platform for India's Gig Economy</i>
</p>

---

## 🚨 The Problem

India’s gig economy runs on delivery partners (Swiggy, Zomato, Zepto, Blinkit). These workers earn daily wages based strictly on completed deliveries. However, uncontrollable external disruptions such as:
* 🌧️ **Heavy Rain & Floods**
* 🌡️ **Extreme Heatwaves**
* 🌫️ **Severe Air Pollution**
* 🚧 **Curfews / Sudden Shutdowns**

...can completely halt deliveries. During these events, workers lose **20–30% of their weekly income**. Currently, there is **zero protection** against this environmental income loss.

---

## 💡 Our Solution

ShieldGig is an **AI-powered parametric insurance platform** engineered specifically for gig delivery workers. 

Instead of traditional, messy claim forms, ShieldGig relies on **Parametric Triggers**. Payouts are entirely data-driven and triggered automatically when predefined environmental APIs hit critical thresholds.

**Key Features:**
* **Weekly Micro-Premiums:** Subscription-based models matching the gig worker payout cycle.
* **AI Risk Prediction:** Dynamic pricing based on location and weather forecasting.
* **Zero-Touch Claims:** No manual filing. If it floods, the system knows, and the system pays.
* **Instant Payout Simulation:** Direct wallet transfers for immediate financial relief.

---

## 🎯 Target Persona: Food Delivery Partner

We are specifically targeting **Food Delivery Partners (e.g., Swiggy/Zomato)** for our initial launch.

| Attribute | Worker Profile |
| :--- | :--- |
| **Age** | 18–35 |
| **Daily Earnings** | ₹600 – ₹900 |
| **Weekly Earnings** | ₹4000 – ₹6000 |
| **Payment Cycle** | Weekly |

### 📖 Real-Life Scenario
Rahul is a delivery partner in Chennai earning ₹5,000/week. A sudden monsoon floods his delivery zone, halting work for two days. He loses ₹1,500. 
**With ShieldGig:** Our system detects the extreme rainfall via weather APIs. The parametric trigger activates, and Rahul automatically receives an ₹800 payout directly to his wallet—no questions asked, no forms filled.

---

## ⚙️ System Architecture

<p align="center">
  <img src="images/architecture.png" alt="System Architecture" width="850">
</p>

1. **Frontend UI:** Worker Dashboard for policy management.
2. **Backend Server:** Manages users, policies, and API polling.
3. **AI Risk Engine:** Calculates localized risk scores.
4. **Data Oracles:** Weather & Pollution APIs (OpenWeather, AQI).
5. **Trigger Engine:** Validates data against parametric rules.
6. **Payment Gateway:** Simulates automated payouts.

---

## 🔄 Automated Workflow

<p align="center">
  <img src="images/workflow.png" alt="System Workflow" width="850">
</p>

1. Worker registers and selects a weekly plan.
2. AI calculates a localized premium risk score.
3. Policy activates.
4. System continuously monitors environmental data via APIs.
5. **Event Detected** (e.g., Rainfall > 50mm).
6. Smart contract / Trigger engine generates an automatic claim.
7. Instant payout initiated to the worker.

---

## 📊 Parametric Triggers & Payouts

These triggers ensure transparent, unbiased, and instant payouts.

| Event | API Condition | Payout Amount |
| :--- | :--- | :--- |
| 🌧 **Heavy Rain** | Rainfall > 50mm | ₹300 |
| 🌡 **Extreme Heat** | Temperature > 45°C | ₹200 |
| 🌊 **Flood Alert** | Verified Govt Flood Alert | ₹400 |
| 🌫 **Severe Pollution**| AQI > 400 | ₹150 |
| 🚧 **Curfew** | Govt Restriction Notification| ₹500 |

---

## 💰 Weekly Premium Model

Because gig workers earn weekly, our premiums are strictly weekly. Our AI dynamically adjusts these premiums depending on the specific location's risk profile (e.g., a high-flood zone might see a slight premium increase).

| Plan | Weekly Premium | Income Coverage |
| :--- | :--- | :--- |
| **Basic** | ₹20/week | Up to ₹1000 |
| **Standard**| ₹35/week | Up to ₹2000 |
| **Pro** | ₹50/week | Up to ₹3500 |

---

## 🤖 AI Integration Strategy

**1. Risk Prediction Engine**
Machine learning models (built with Python & Scikit-learn) analyze historical weather data, flood zones, and traffic patterns to generate a dynamic risk score for specific delivery zones.

**2. Dynamic Pricing**
Premiums automatically adjust based on the AI's risk score, ensuring fair pricing (e.g., a dry week in a safe zone lowers the premium).

**3. Fraud Detection Engine**
AI-based anomaly detection prevents abuse by cross-referencing:
* Worker GPS spoofing checks.
* Discrepancies between claimed weather and actual API data.
* Delivery platform activity validation.

---

## 💻 Technology Stack

* **Frontend:** React.js / Next.js
* **Backend:** Node.js + Express
* **Database:** MongoDB
* **AI/ML:** Python, TensorFlow/Scikit-learn
* **APIs:** OpenWeather API, AQI API
* **Payments:** Razorpay Sandbox

---

## 📱 Platform Preview

<p align="center">
  <img src="images/dashboard.png" alt="Dashboard Preview" width="700">
</p>

---

## 🚀 Development Roadmap

* **Phase 1 (Current):** Strategy, Idea Validation, Architecture Design, and Parametric Modeling.
* **Phase 2:** Core system development (Auth, Policy Creation, API Polling, Trigger Engine).
* **Phase 3:** Scale platform (Advanced AI Fraud Detection, Real-time Payout Simulation, Analytics Dashboard).

---

## 👥 Team

* **Eashan Darsh** - AI/ML & Full Stack Development
* *(Add Teammate 2 Name)* - *(Add Role)*
* *(Add Teammate 3 Name)* - *(Add Role)*
