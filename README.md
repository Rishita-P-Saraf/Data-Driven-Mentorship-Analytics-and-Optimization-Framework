# 📘 Scaler Program Management Intern Assignment – Mentor Session Structure  
---

## 🧩 Overview  

This project analyzes mentoring session data from Scaler programs to identify structural gaps in mentor preparation, learner engagement, and post-session follow-ups.  
The solution proposes a **data-driven framework** for improving mentoring session quality using **structured workflows, AI automation, and performance monitoring dashboards**.

---

## 📊 Section 1: Diagnostic Analysis  

### **1.5 Action Items & Follow-Up Gaps**

| Metric | Value / Observation | Insight |
|:--|:--|:--|
| Sessions with Documented Action Items | 36.67% | Lack of structured post-session actions. |
| Sessions with Scheduled Follow-Ups | 41.67% | Impacts learner accountability and continuity. |

---

### **1.6 Sentiment Insights from Feedback**

| Metric | Observation | Insight |
|:--|:--|:--|
| Negative Feedback Instances | 7 recurring comments | Common issue: *"Mentor was late, shortened our discussion time."* |
| Average Sentiment Score | –0.3 | Indicates dissatisfaction due to time management. |
| Impacted Mentors | Neha Verma, Divya Krishnan, Vikram Singh, Priya Patel, Kavya Nair, Rahul Sharma | Require time-discipline feedback. |

---

### **1.7 Age Cohort Analysis**

| Cohort | Attendance (%) | Insight |
|:--|:--|:--|
| a_1M | 75 | High engagement cohort |
| d_7–9M | 69.2 | Above average attendance |
| b_2–3M | 61.1 | Needs more engagement |
| c_4–6M | 61.1 | Needs more engagement |

---

### **1.8 Program-Wise Analysis**

| Program | Attendance Rate (%) | Insight |
|:--|:--|:--|
| DSML | 80.8 | Best performing |
| Academy | 68 | Average engagement |
| AIML | 62.5 | Needs structure |
| DevOps | 62.1 | Lowest, timing/structure issue |

---

### **1.9 Batch Insights**

| Batch | Attendance Rate (%) | Insight |
|:--|:--|:--|
| DSML Aug25 Advanced | 88.9 | High motivation, effective structure |
| DSML Jul25 Intermediate | 85.7 | Strong engagement |
| DevOps Sept25 | 42.8 | Critical attention needed |
| Academy Sept25 Advanced | 55.6 | Weak mentoring agenda |

---

### **1.10 Mentor Time Management Gaps**

| Mentor | Avg. Duration Gap (mins) | Insight |
|:--|:--|:--|
| Sneha Reddy | –45 | Ends sessions early, pacing issue |
| Pooja Gupta | –40 | Consistently short sessions |
| Arjun Desai | –36 | Under-time frequency high |

---

## ⚙️ Section 2: Solution Design  

### **2.1 Pre-Session Framework**

| Component | Description |
|:--|:--|
| **Mentor Preparation Checklist** | Structured checklist including learner goals, background, prior feedback. Mentors who prepare score higher (3.71 vs. 3.57). |
| **Learner Pre-Read or Task** | Assign pre-session tasks to ensure both parties are prepared. |
| **Automated Scheduling Confirmation** | Automated reminders via email/calendar to avoid missed sessions. |
| **Attendance Prediction System** | Predict high-risk no-shows using past trends and batch data. |

**Expected Impact:**  
✔ Higher participation  ✔ Consistent session quality  ✔ Early no-show identification  

---

### **2.2 During-Session Framework**

| Component | Description |
|:--|:--|
| **Standardized Session Flow** | 1️⃣ Introduction (5–10m) → 2️⃣ Core Discussion (15–40m) → 3️⃣ Action Items (5m) → 4️⃣ Feedback (2–5m) |
| **Action Item Documentation** | Ensure 100% sessions record clear next steps. Current: only 36.67%. |
| **Real-Time Feedback Collection** | Capture live feedback to detect dissatisfaction early. |
| **Duration Monitoring** | Flag under-time sessions (<80% scheduled duration). |
| **Interactive Elements** | Add polls, Q&A, or exercises for higher engagement. |

---

### **2.3 Post-Session Framework**

| Component | Description |
|:--|:--|
| **Follow-Up Scheduling** | Auto-schedule within 3–5 days; current completion = 41.67%. |
| **Action Item Tracker** | Track learner deliverables via dashboard. |
| **Feedback Sentiment Analysis** | Use NLP (TextBlob/VADER) for sentiment scoring. |
| **Continuous Improvement Loop** | Monthly performance report + mentor coaching. |
| **Early-Warning Dashboard** | Power BI dashboard flagging critical sessions. |

---

## 🤝 Section 3: Stakeholder Management  

| Stakeholder | Role | Action Plan | Expected Impact |
|:--|:--|:--|:--|
| **Mentors** | Deliver structured sessions | Training, dashboards, reminders | Higher consistency |
| **Learners** | Attend, provide feedback | Pre-session materials, follow-up reminders | Higher attendance |
| **Program Managers** | Oversee batch ops | Dashboards, early-warning trackers | Early issue resolution |
| **Product Owners** | Strategy & policy | Monthly reports, AI insights | Data-backed improvement |
| **Feedback Loop** | 2-way transparency | Continuous feedback & alerts | Accountability & alignment |

---

## 🗓️ Section 4: Implementation Roadmap  

| Phase | Weeks | Objective | Key Activities | KPIs |
|:--|:--|:--|:--|:--|
| **Phase 1: Pilot** | 1–4 | Test structured flow | Checklist, reminders, feedback | 80% adherence, +10% attendance |
| **Phase 2: Scale-Up** | 5–8 | Deploy across programs | Dashboards, sentiment analysis | 90% adoption, +0.2 rating |
| **Phase 3: Full Rollout** | 9–12 | Standardize & monitor | AI alerts, performance tracking | 95% structure adherence |
| **Phase 4: Continuous Improvement** | Post–12 | Sustain quality | Quarterly reviews, AI refinement | 15–20% fewer cancellations |

---

## 🤖 Section 5: AI & Automation Integration  

### **5.1 Automated Attendance & Engagement Tracker**

- **Goal:** Automate learner tracking and real-time attendance analytics.  
- **Layers:**  
  - Data Source: Zoom / Meet APIs  
  - ETL: Cloud Functions / Lambda  
  - Storage: NoSQL + Relational DB  
  - Dashboard: Power BI / Excel  
- **Benefits:** Real-time alerts, reduced manual tracking, predictive drop-off detection.

---

### **5.2 AI-Driven Feedback & Sentiment Analysis System**

- **Goal:** Extract insights from feedback to improve session quality.  
- **NLP:** TextBlob / VADER for sentiment & keyword extraction.  
- **Pipeline:** Feedback → NLP Microservice → Sentiment Score → Dashboard & Alerts.  
- **Benefits:** Early dissatisfaction detection, mentor-wise trends, automated alerts.

---

### **5.3 AI-Based Session Scheduling & Reminders System**

- **Goal:** Predict no-shows and automate reminders.  
- **Layers:**  
  - Input: Session data  
  - ML Predictor: Learner no-show probability  
  - Campaign Manager: Personalized nudges  
  - Channels: Email, SMS, In-App Notifications  
- **Outcome:** Reduced no-shows, improved attendance consistency.

---

## 📈 Section 6: Success Metrics  

| Metric Type | Key Measures | Target |
|:--|:--|:--|
| **Attendance** | Overall & batch-wise attendance | ≥ 80% |
| **Session Quality** | Avg rating, mentor prep compliance | ≥ 4.0 rating, ≥ 90% compliance |
| **Action Items & Follow-Up** | Documented & scheduled follow-ups | ≥ 85% completion |
| **Feedback Sentiment** | Average polarity score | > 0 (positive sentiment) |

---

## 🚨 Early-Warning Tracker Design  

| Section | Description |
|:--|:--|
| **Input Data** | Attendance %, Duration Gap, Ratings, Action Items, Sentiment |
| **Flagging Criteria** | Attendance <70%, Rating <3.5, Duration <80%, Negative Sentiment <0 |
| **Dashboard Features** | Traffic-light visualization, mentor/batch views, trend KPIs, auto-alerts |

---

## 📊 Tools & Technologies  

- **Data Engineering:** Python, Pandas, Cloud Functions, SQL  
- **NLP & ML:** TextBlob, VADER, Scikit-learn  
- **Visualization:** Power BI, Excel Dashboards  
- **Automation:** Email APIs, WhatsApp Gateway, In-App Notifications  

---

## 🏁 Expected Outcomes  

✅ 15–20% improvement in attendance  
✅ 0.2+ increase in feedback ratings  
✅ Reduction in early session endings  
✅ Automated dashboards for proactive mentoring management  
✅ Data-driven decision-making and transparent stakeholder alignment  

---

**© 2025 – Rishita Priyadarshini Saraf**  
*Scaler Program Management Intern Assignment – Mentor Session Structure*  
