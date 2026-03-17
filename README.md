<p align="center">
<img src="images/banner.png" width="900">
</p>

<h1 align="center">ShieldGig</h1>

<p align="center">
AI-Powered Income Protection for Gig Delivery Workers
</p>

<p align="center">
Parametric Insurance Platform for India's Gig Economy
</p>

---

# Problem Statement

India’s gig economy depends heavily on delivery workers from platforms such as:

- Swiggy
- Zomato
- Amazon
- Zepto
- Blinkit

These workers earn based on completed deliveries. However, external disruptions such as:

• Heavy rain  
• Floods  
• Extreme heat  
• Severe pollution  
• Curfews or sudden area shutdowns  

can completely stop deliveries.

When these disruptions occur, workers lose **20–30% of their weekly income** and currently there is **no protection against income loss**.

---

# Our Solution

ShieldGig is an **AI-powered parametric insurance platform** designed to protect gig delivery workers from income loss caused by environmental or social disruptions.

Key Features

- Weekly subscription-based insurance
- AI-based risk prediction
- Automatic disruption detection
- Zero-touch claim processing
- Instant payout simulation

Unlike traditional insurance, payouts are **automatically triggered when predefined disruption conditions occur**.

---

# Target Persona

Food Delivery Partners (Swiggy / Zomato)

Typical Worker Profile

| Attribute | Value |
|------|------|
Age | 18–35 |
Daily Earnings | ₹600–₹900 |
Weekly Earnings | ₹4000–₹6000 |
Work Hours | 8–10 hours |
Payment Cycle | Weekly |

---

# Real Life Scenario

Rahul is a Swiggy delivery partner working in Chennai.

Average earnings

₹750 per day  
₹5000 per week

During heavy rainfall, deliveries stop for two days.

Income loss:

₹1500

With ShieldGig:

• System detects rainfall automatically  
• Insurance trigger activates  
• Rahul receives ₹800 payout automatically  

No claim filing required.

---

# System Architecture

<p align="center">
<img src="images/architecture.png" width="850">
</p>

Architecture Components

1 Worker Web App  
2 Backend Server  
3 AI Risk Engine  
4 Weather & Pollution APIs  
5 Trigger Engine  
6 Claim Processor  
7 Payment System

---

# Workflow

<p align="center">
<img src="images/workflow.png" width="850">
</p>

Process

1 Worker registers on platform  
2 Worker selects weekly insurance plan  
3 AI calculates premium based on risk  
4 Worker activates policy  
5 System monitors disruption triggers  
6 Event detected via API  
7 Automatic claim generated  
8 Instant payout initiated  

---

# Parametric Triggers

| Event | Condition | Payout |
|------|------|------|
Heavy Rain | Rainfall > 50mm | ₹300 |
Extreme Heat | Temperature > 45°C | ₹200 |
Flood Alert | Government flood alert | ₹400 |
Severe Pollution | AQI > 400 | ₹150 |
Curfew | Government restriction | ₹500 |

These triggers ensure **transparent and automated payouts without manual claims**.

---

# Weekly Premium Model

Gig workers operate on a weekly earning cycle, therefore ShieldGig uses a **weekly subscription model**.

| Plan | Weekly Premium | Coverage |
|------|------|------|
Basic | ₹20/week | Up to ₹1000 |
Standard | ₹35/week | Up to ₹2000 |
Pro | ₹50/week | Up to ₹3500 |

AI dynamically adjusts premiums depending on location risk.

Example

Low flood zone → ₹20/week  
High flood zone → ₹28/week

---

# AI Integration

## Risk Prediction

Machine learning models analyze:

• Weather history  
• Flood data  
• Pollution data  
• Traffic disruption patterns  

This generates a **risk score for each delivery zone**.

---

## Dynamic Premium Adjustment

Premiums automatically adjust based on calculated risk score.

Higher risk zone → slightly higher premium  
Lower risk zone → cheaper insurance

---

## Fraud Detection

AI-based anomaly detection prevents fraudulent claims.

Fraud checks include:

• Location validation  
• Weather verification  
• Duplicate claim detection  
• Delivery activity validation

---

# Technology Stack

Frontend  
React.js

Backend  
Node.js + Express

Database  
MongoDB

AI / ML  
Python  
Scikit-learn

APIs  
OpenWeather API  
AQI API

Payment Simulation  
Razorpay Sandbox

---

# Platform Choice

The platform is initially developed as a **web application** because:

• Faster development  
• Easy API integration  
• Accessible on low-end smartphones  
• Simple onboarding

Future versions will include a **mobile application**.

---

# Development Roadmap

Phase 1  
Research, architecture design, and idea validation

Phase 2  
Core system development

- Worker registration
- Policy creation
- Premium calculation
- Automated claim triggering

Phase 3  
System scaling

- Fraud detection
- Instant payout simulation
- Analytics dashboard

---

# Expected Impact

ShieldGig helps gig workers:

• Protect weekly earnings  
• Reduce financial uncertainty  
• Receive instant payouts during disruptions  

This creates a **financial safety net for India’s growing gig economy**.

---

# Repository Structure
