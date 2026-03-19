# GigShield AI  
AI-Powered Parametric Insurance for Food Delivery Partners  

---

## Team Details  
- Team Name: Apex Innovators 
- Hackathon: Guidewire DEVTrails 2026  
- Phase: Ideation & Foundation  

---

## Persona  

We are building for **Food Delivery Partners (Swiggy/Zomato) operating in urban Indian cities such as Chennai and Bangalore**.  

These workers rely on daily deliveries for income and are highly affected by environmental disruptions like rain, heat, and pollution, which directly reduce their working hours and earnings.

---

## Problem Statement  

Food delivery partners in India frequently lose income due to external disruptions such as heavy rainfall, extreme heat, and severe air pollution. These conditions can reduce or completely stop their working hours, leading to **20–30% weekly income loss**. Currently, there is no insurance solution focused on protecting their income, leaving them financially vulnerable.

---

## 💡 Our Solution: GigShield AI  

GigShield AI is an **AI-powered parametric insurance platform** that provides income protection to delivery workers by automatically detecting disruptions and triggering payouts.  

- No manual claims  
- No paperwork  
- Fully automated payouts  
- Weekly subscription model  

---

## Parametric Trigger Scenarios  

Payouts are triggered automatically when conditions are met:

| Trigger | Condition | Payout |
|--------|----------|--------|
| Heavy Rain | Rainfall > 50 mm/day | ₹400 |
| Extreme Heat | Temperature > 42°C | ₹300 |
| Severe Pollution | AQI > 300 | ₹250 |

These conditions directly impact delivery operations and cause income loss.

---

## 💸 Weekly Pricing Model  

The platform uses a **weekly premium model** aligned with gig worker earnings.

| Risk Level | Weekly Premium |
|-----------|---------------|
| Low Risk | ₹20/week |
| Medium Risk | ₹35/week |
| High Risk | ₹50/week |

### Risk Factors:
- Location-based weather history  
- Frequency of disruptions  
- Area-specific risk patterns  

---

## AI/ML Strategy  

### 1. Dynamic Premium Calculation  
AI models analyze location and historical disruption data to assign a personalized weekly premium.

### 2. Income Loss Prediction  
The system estimates potential income loss based on working hours affected by disruptions.

### 3. Fraud Detection  
Machine learning models detect anomalies and suspicious claim behavior using multi-signal validation.

---

## 🔐 Adversarial Defense & Anti-Spoofing Strategy  

### 1. Differentiation  

The system uses a **Multi-Signal Trust Score** instead of relying only on GPS.

| Signal | Real Worker | Spoofer |
|------|------------|--------|
| Movement | Active | Static |
| GPS Pattern | Continuous | Sudden jumps |
| App Activity | Accepts deliveries | No activity |
| Network Type | Mobile data | WiFi |
| Weather Match | Matches location | Mismatch |

---

### 2. Data Used  

The system analyzes multiple data points:

- Device sensors (accelerometer, gyroscope)  
- GPS movement patterns  
- Network type and IP validation  
- Delivery activity (simulated)  
- Weather API comparison  
- Nearby user behavior (cluster validation)  

---

### 3. UX Balance  

To ensure fairness:

- **Low Risk:** Instant payout  
- **Medium Risk:** Quick verification  
- **High Risk:** Delayed review  

Users are informed transparently without blocking genuine claims.

---

### Anti-Collusion Detection  

The system detects coordinated fraud using:
- Same IP clusters  
- Simultaneous claims  
- Repeated patterns  

---

## 🔄 System Workflow  

1. User registers and enters location and income  
2. AI calculates risk score  
3. Weekly premium is assigned  
4. System monitors real-time environmental data  
5. Trigger condition is detected  
6. Claim is automatically initiated  
7. Fraud detection is performed  
8. Payout is processed instantly  

---

## Integration Plan  

- Weather APIs (or mock data)  
- AQI APIs (or mock data)  
- Delivery activity simulation  
- Payment gateway (Razorpay test mode / mock UPI)  

---

## 📊 Dashboard Features  

### Worker Dashboard  
- Active policy status  
- Risk level  
- Earnings protected  
- Claim history  

### Admin Dashboard  
- Total users  
- Claims triggered  
- Fraud alerts  
- Risk analytics  

---

## 🛠️ Tech Stack  

- Frontend: HTML, CSS, JavaScript  
- Backend: Python (Flask / FastAPI)  
- AI/ML: scikit-learn  
- Database: Firebase / MongoDB  
- APIs: Weather + AQI  

---

## Development Plan  

### Phase 1  
- Idea and architecture  

### Phase 2  
- Registration  
- Premium calculation  
- Trigger system  
- Auto payout  

### Phase 3  
- Fraud detection  
- Dashboard  
- Optimization  

---

## Demo Video  

Paste your video link here:  
VIDEO_LINK  

---

## Conclusion  

GigShield AI provides a **fully automated, AI-powered insurance solution** tailored for India’s gig economy. By focusing on income protection, weekly pricing, and fraud-resistant architecture, the platform ensures financial stability for delivery partners during external disruptions.
