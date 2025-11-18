# banking-user-analysis
Data science project simulating user behaviour, spending patterns, and feature adoption in a digital banking app.

# Banking User Analysis
### A Data Science Project on Customer Behaviour, Spending Patterns, and Product Engagement

---

## 📋 Overview
This project simulates a **digital banking environment** with 50,000 synthetic UK users and millions of transactions.  
It aims to replicate the kind of **customer behaviour and product analytics** work performed by data scientists in modern fintech companies.

The goal is to understand:
- How users interact with app features
- How spending behaviour varies by device and demographics
- How user activity and retention evolve over time

---

## 🎯 Objectives
- Analyse **feature adoption** and identify what drives engagement.  
- Measure **spending behaviour** across devices (iOS, Android, Web).  
- Track **user retention and monthly active users (MAU)** over 2024.  
- Deliver actionable **product recommendations** based on insights.

---

## 🧱 Dataset Summary
| Dataset | Rows | Description |
|----------|------|-------------|
| `users.csv` | 50,000 | User profiles (ID, name, device, signup date, demographics) |
| `transactions.csv` | ~3–4 million | Individual purchase transactions by user |
| `feature_usage.csv` | ~5–8 million | Events of feature adoption and use across app features |

All data are **synthetically generated** for realism and reproducibility, using Python.

---

## 🧩 Tech Stack
**Languages:** Python (pandas, NumPy, matplotlib, seaborn), SQL  
**Tools:** Google Colab, Google Drive, GitHub  
**Visualization:** Matplotlib / Seaborn  
**Version Control:** Git + GitHub

---

## 🧮 Analyses Performed

### 1️⃣ Feature Adoption
| Feature | Adoption Rate |
|----------|----------------|
| Pots | 44.9 % |
| Budgeting | 40.3 % |
| Get Paid Early | 34.8 % |
| Round-Ups | 30.2 % |
| Investments | 22.6 % |
| Pensions | 18.0 % |

**Insight:**  
Everyday money-management features (Pots, Budgeting, Get-Paid-Early) drive the highest engagement.  
Wealth-building tools (Investments, Pensions) have lower adoption, suggesting room for in-app education or feature redesign.

![Feature Adoption](images/feature_adoption.png)

---

### 2️⃣ Spending Behaviour by Device
| Device | Transactions | Avg Txn (£) | Total Spend (£) |
|---------|---------------|--------------|----------------|
| iOS | 1,066,814 | 35.99 | 38,403,977 |
| Android | 527,894 | 35.97 | 18,988,148 |
| Web | 177,850 | 35.96 | 6,396,632 |

**Insight:**  
iOS users generate over **50% of total spend**, suggesting they are the most active and valuable segment.  
Targeted campaigns for Android users could help close the engagement gap.

![Spend by Device](images/spend_by_device.png)

---

### 3️⃣ User Retention and Monthly Activity
**Monthly Active Users (MAU)** increased steadily through 2024.  
Cohort analysis shows strong retention — the January 2024 cohort retained over 120 % of its initial active users by May.

![Monthly Active Users](images/mau_trend.png)
![Cohort Retention](images/cohort_retention.png)

**Insight:**  
Sustained activity across cohorts suggests effective onboarding and engagement design, particularly through budgeting and early-salary features.

---

## 💡 Business Recommendations
1. **Enhance high-engagement features** (Pots, Budgeting) with smart notifications.  
2. **Target Android engagement** through personalised rewards or UI parity.  
3. **Promote Investments and Pensions** via in-app education for younger users.  
4. **Monitor retention cohorts** to assess long-term impact of feature rollouts.

---

## 🧠 Skills Demonstrated
- Data cleaning and aggregation with pandas & NumPy  
- SQL-style joins and analysis in Python  
- Feature adoption and retention modelling  
- Data storytelling and visual communication  
- Business insight formulation for product strategy  

---
