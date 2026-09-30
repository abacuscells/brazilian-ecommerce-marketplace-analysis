# Brazilian E-Commerce Marketplace Turnaround Strategy
*Operational Diagnostic & Strategic Growth Framework*

---

## 📌 Executive Summary
Between 2016 and 2018, top-line order volume on a major Brazilian e-commerce marketplace plateaued at roughly 6,500 orders per month, accompanied by high volatility in customer review scores[cite: 7]. This project evaluates the underlying transaction data to diagnose the drivers of customer churn, assess the impact on repeat purchasing behavior, and define a prioritized turnaround framework[cite: 7, 8].

---

## 🔍 Key Diagnostic Findings

1. **Abysmal Customer Retention (3.12% Repeat Rate)**
   - Out of 96,096 unique customers, 96.88% (93,099) are single-purchase buyers[cite: 14].
   - Only 2,997 customers completed two or more orders, indicating that acquisition spend does not translate into recurring customer lifetime value[cite: 14].

2. **Delivery Delays Strongly Depress Review Ratings**
   - **On-Time / Early Deliveries:** Maintain an average review score of 4.28 / 5.0, with only 9.5% negative feedback (1–2 stars)[cite: 14].
   - **Severe Delays (>7 Days Late):** Average review scores drop to 1.73 / 5.0, with negative feedback surging to 78.5%[cite: 14].

3. **Regional Transit Bottlenecks & Handover Friction**
   - Core southeastern hubs (São Paulo, Minas Gerais) maintain late delivery rates around 5.4%–5.6% with 8.7–12.0 average delivery days[cite: 15].
   - High-volume interstate corridors (Rio de Janeiro, Bahia) experience late delivery rates of 12.6%–13.3%, transit durations reaching 15.2–19.3 days, and freight costs exceeding R$ 33.60[cite: 15].
   - Sellers average 3.23 days to complete packaging and carrier handover before transit begins[cite: 16].

---

## 🚀 Prioritized 4-Pillar Action Plan

| Priority Rank | Strategic Initiative | Impact vs. Effort Call (Reasoning) | Key Tracking KPIs |
| :--- | :--- | :--- | :--- |
| **Rank 1: Seller SLA** | Enforce strict 48-hour order dispatch SLA with automated tier penalties and reduced search visibility for chronic delays[cite: 16]. | **High Impact / Low Effort:** Enforces seller accountability via algorithm rules without capital expense[cite: 16]. | • Dispatch Time: < 1.5 days[cite: 16]<br>• On-Time Handover: ≥ 92%[cite: 16] |
| **Rank 2: 3PL Logistics** | Partner with regional 3PL carriers in high-delay corridors (e.g., RJ, BA) to consolidate freight and reduce transit handoffs[cite: 16]. | **High Impact / High Effort:** Requires regional contract negotiations & API sync, but directly solves transit bottlenecks[cite: 16]. | • On-Time Rate: ≥ 97.0%[cite: 16]<br>• Inter-State Days: < 9.0d[cite: 16] |
| **Rank 3: CRM Retention** | Launch post-purchase automated CRM lifecycle workflows (bounce-back incentives & re-order reminders within 30 days)[cite: 16]. | **High Impact / Medium Effort:** Leverages transaction data to drive repeat GMV with minimal recurring overhead[cite: 16]. | • 60-Day Repeat Rate: ≥ 8.5%[cite: 16]<br>• CRM Offer Conv.: ≥ 10%[cite: 16] |
| **Rank 4: Dynamic EDD** | Deploy ML-based dynamic Estimated Delivery Date engine factoring real-time seller location and carrier historical speed[cite: 16]. | **Medium Impact / Medium Effort:** Shields review scores from unrealistic delivery promises while logistics scales[cite: 16]. | • EDD Variance: ≤ ±1 day[cite: 16]<br>• Net Review Score: ≥ 4.4/5[cite: 16] |

---

## 🏛️ Departmental KRA & 90-Day Implementation Framework

* **Logistics & Supply Chain:** Increase on-time delivery rate from 92.1% to ≥ 97% and compress interstate transit from 15.1 days to < 9 days by auditing high-delay routes and integrating regional 3PL partners[cite: 16].
* **Seller Operations:** Enforce 48-hour handover compliance (≥ 92%) and penalize/offboard sellers exceeding 15% late dispatch or receiving < 3.0 review scores[cite: 16].
* **Product & Tech:** Implement dynamic delivery date algorithms (variance target ≤ ±1 day) and standardize dimension checks to resolve freight misclassification[cite: 16].
* **Marketing & Retention:** Lift repeat purchase rate from 3.12% to ≥ 8.5% via replenishment triggers and automated post-purchase outreach[cite: 16].

### Implementation Timeline
* **Month 1:** Launch 48-hr Seller SLA & 3PL RFP[cite: 16].
* **Month 2:** Sync 3PL APIs & Roll out CRM Automation[cite: 16].
* **Month 3:** Deploy Dynamic EDD & Audit CSAT[cite: 16].

---

## 📁 Repository Deliverables
* `Brazilian_Marketplace_Analysis.xlsx`: Multi-tab analytical workbook containing data cleaning logs, order volume trends, and chart-backed diagnostic findings[cite: 17].
* `Strategic_Action_Plan.pdf`: 1-page executive action memo featuring prioritized recommendations, impact-vs-effort evaluations, and the cross-functional KRA matrix[cite: 16, 17].

---

## 🛠️ Tools Used
* **Spreadsheet Modeling:** Microsoft Excel (PivotTables, Multi-Condition Aggregations, Data Cleaning Log)
* **Strategy Frameworks:** Impact vs. Effort Matrix, Departmental KRA Framework, 90-Day Operational Roadmap[cite: 16]
