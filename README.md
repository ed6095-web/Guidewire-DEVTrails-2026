<div align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=42&pause=1000&color=00FFCC&center=true&vCenter=true&width=800&lines=ShieldGig;AI-Powered+Income+Protection;Parametric+Insurance+System" />

Phase 1 Strategy & System Concept

A data-driven financial safety net for India’s gig economy

</div>
📌 Problem Statement

India's gig economy depends heavily on delivery partners who earn money only when deliveries are completed.

However, workers face income loss due to uncontrollable external disruptions, such as:

🌧 Heavy Rain

🌡 Extreme Heatwaves

🌫 Severe Air Pollution

🚧 Government Curfews

🌊 Flood Alerts

During these events, workers often lose 20–30% of their weekly income, and no system currently protects them from this type of disruption.

pie title Weekly Income Loss Due to Environmental Disruptions
    "Retained Earnings" : 70
    "Income Lost to Weather" : 30
💡 Proposed Solution: ShieldGig

ShieldGig is a parametric micro-insurance platform designed specifically for gig delivery workers.

Instead of traditional insurance claims, the system uses automated environmental triggers from trusted APIs.

When certain conditions occur, payouts are triggered automatically without requiring manual claims.

Core Idea

If weather or government restrictions stop gig workers from working, the system automatically compensates part of their lost income.

⚙️ Core System Pillars
1️⃣ Weekly Micro-Premiums

Small subscription payments aligned with the weekly payout cycle of gig workers.

2️⃣ Algorithmic Risk Scoring

Premiums dynamically adjust based on:

Local weather risk

Historical disaster data

Geographic vulnerability

3️⃣ Zero-Touch Claims

No forms, no claim process.

When an event occurs, the system detects it automatically.

4️⃣ Instant Wallet Payouts

Compensation is directly credited to the worker’s digital wallet.

👤 Target User Persona

For Phase 1, the system is designed for food delivery partners.

Category	Details
Platforms	Swiggy, Zomato
Age Group	18 – 35
Daily Earnings	₹600 – ₹900
Payment Cycle	Weekly
📖 Example Workflow
Scenario

Rahul is a delivery partner earning ₹5,000 per week.

A heavy monsoon flood stops deliveries in his zone for 2 days, causing a ₹1,500 income loss.

ShieldGig Response

1️⃣ Weather API detects extreme rainfall

2️⃣ Parametric trigger condition is validated

3️⃣ System automatically processes payout

4️⃣ Rahul receives ₹800 compensation instantly

No claims.
No paperwork.
No delays.

🏗️ System Architecture
<p align="center"> <img src="images/architecture.png" width="850"> </p>
Architecture Components

Client Interface

Worker dashboard

Policy registration

Coverage tracking

Backend Node

User policy management

API polling

Trigger evaluation

Risk Engine

Calculates geographic risk scores

Determines premium pricing

Data Oracles
External trusted data sources:

OpenWeather API

Government AQI API

Disaster alert APIs

Trigger Engine
Evaluates incoming environmental data against predefined thresholds.

Payment Gateway
Simulates automated payout via Razorpay sandbox.

🚨 Parametric Triggers & Payout Logic

These triggers ensure transparent and automated payouts.

xychart-beta
    title "Automated Payout Matrix (₹)"
    x-axis ["Rain >50mm","Heat >45°C","Flood Alert","AQI >400","Curfew"]
    y-axis "Payout" 0 --> 600
    bar [300,200,400,150,500]
Disruption Event	API Condition	Payout
🌧 Heavy Rain	Rainfall > 50mm	₹300
🌡 Extreme Heat	Temperature > 45°C	₹200
🌊 Flood Alert	Govt flood alert = TRUE	₹400
🌫 Severe Pollution	AQI > 400	₹150
🚧 Curfew	Geo-fenced restriction	₹500
💰 Weekly Premium Model

Premiums are calculated weekly to match the gig worker payment cycle.

Tier	Weekly Premium	Max Coverage
Basic	₹20	Up to ₹1000
Standard	₹35	Up to ₹2000
Pro	₹50	Up to ₹3500

Premiums dynamically adjust based on location risk score.

🤖 AI & Logic Integration
1️⃣ Risk Prediction Engine

Machine learning models analyze:

Historical weather patterns

Flood zones

Seasonal risk

Tools:

Python

Scikit-learn

2️⃣ Dynamic Premium Pricing

Premiums change based on:

Geographic risk

Weather forecasts

Disaster probability

Lower risk zones → cheaper premiums.

3️⃣ Fraud Detection System

To prevent misuse:

The system cross-checks:

📍 GPS location vs disruption zones

🌧 API weather vs user reports

🧾 Duplicate claim patterns

🧰 Technology Stack
Layer	Technology
Frontend	React.js / Next.js
Backend	Node.js + Express
Database	MongoDB
AI/ML	Python, Scikit-learn
APIs	OpenWeather API, AQI API
Payment Simulation	Razorpay Sandbox
🗺 Development Roadmap
Phase 1 (Current)

Concept design

Parametric trigger modeling

Architecture planning

Hackathon submission

Phase 2

API integration

Backend logic development

Risk engine implementation

Phase 3

Real-time event detection

Fraud detection models

Wallet payout simulation

Full system prototype

👨‍💻 Team
Member	Role
Eashan Darsh	System Architecture & Frontend
Ved Deshmukh	Research
Shashwat Chaturvedi	Backend Development
Sneha Basera	Data Collection
Asim Shankar	AI / ML
🎯 Vision

ShieldGig aims to create the first automated income protection system for gig workers.

As gig economies grow globally, millions of workers remain financially vulnerable to environmental disruptions.

ShieldGig transforms insurance into a real-time financial safety net powered by data and automation.
