# In-Season-Order-Tracking-BI-Dashboard
<table>
  <tr>
    <td>
      <img src="Screenshot 2026-02-25 112952.png" alt="Summary" width="500"/>
    </td>
    <td>
      <img src="Screenshot 2026-02-25 113020.png" alt="OS Analysis" width="500"/>
    </td>
  </tr>
</table>

[![View Dashboard](https://img.shields.io/badge/PowerBI-Dashboard-blue?logo=powerbi)](https://app.powerbi.com/view?r=eyJrIjoiNDIwY2Q5N2UtYWM3MS00ZDYzLWJiZmItODUwYmU3MjIxMGNjIiwidCI6Ijg2NDU3OWM1LWVjMjctNDAzYi1hMjAwLWFhNjViYmEwMTIyMyIsImMiOjEwfQ%3D%3D)

## 🔎 Project Overview
A compact yet powerful production visibility system for manufacturing companies.

For confidentiality, the data shown here is **dummy / anonymized** while maintaining the **same structure, rules, and logics** as the actual project.  
👉 This ensures the business problem is clearly demonstrated while respecting organizational data privacy.  
  
---

## 🎯 Problem Statement
In many manufacturing organizations, production teams struggle with one key question:<br>
**“Which order is currently in which stage?”**

When managing multiple factories, customers, styles, and hundreds of active orders, tracking progress manually becomes:

- **❌ Time-consuming**
- **❌ Error-prone**
- **❌ Non-transparent**
- **❌ Difficult to escalate delays**
<br>
Without real-time stage visibility, delays are discovered too late — affecting shipment timelines, customer satisfaction, and revenue.

---

## 🚀 Solution Overview
The **In-Season Order Tracking Dashboard** provides end-to-end visibility of production stages across factories and customers.
<br>
It enables:<br>
- **📊 Real-time stage tracking**
- **⚠️ Early delay identification**
- **🏢 Factory-wise delay analysis**
- **📈 Order quantity insights**
- **🔎 Drill-through order-level monitoring**

### 2. **Core Concept**
1. CBD Publish  
2. Fabric MR  
3. HK Trims MR 
4. Fabric/Trims MR
5. Local Trims PO
6. ASL Trims PI
7. ASL Trims/Fabric PI
8. Direct Supplier PI Info
9. ASL Trims PI Info
10. ASL Trims/Fabric PI Info
11. Local Trims/Fabric SC/LC
12. LC/SC
13. GRN
<br>
The dashboard dynamically categorizes:<br>

- **✅ On Track**
- **🔴 Delayed**
- **📦 In Progress**
- **✔️ Completed**


## 💡 Dashboard Features
**1️⃣ Executive Summary View**
- **Total Orders**
- **Order Quantity**
- **Factory FOB**
- **In-Progress Count**
- **On-Track vs Delay Risk**
- **Stage-wise Completion Metrics**<br>
Includes alert system:<br>

**⚠️ “38% of active orders show delay risk. Close monitoring required.”**

**2️⃣ In-Progress Status Analysis**
<br>
Visual breakdown:
- **On Track vs Delayed per milestone**
- **Quick bottleneck identification**
- **Stage-wise performance comparison**

**3️⃣ Factory Delay View**
<br>
Helps answer:
- **Which factory has highest delay?**
- **Which stage is causing bottleneck?**
- **Where escalation is needed?**

**4️⃣ Order-Level Drill Tracker**
<br>
Searchable grid by:
- **File Number**
- **Style**
- **Customer**
- **Factory**

Visual indicators:
<br>
- **✔️ Completed**
- **⭕ Pending**
---

## 🏗️ Technical Architecture<br>
**Data Layer**
- Power Query (M Language)
- Data transformation & milestone extraction
- Factory indexing logic
- Status flag calculation

**Model Layer**
- Power BI dashboard
- Interactive slicers
- On-time vs Risk classification

**Visualization Layer**
- Stage-based status measures
- Delay logic
- Cross-filtering enabled
- Drill-through enabled

---

## 💡 Why This Project Is Powerful
Even though it’s a small model, it delivers:
- 🔍 Production transparency
- 📉 Risk prediction
- 🏭 Factory performance benchmarking
- 📦 Order lifecycle visibility
- ⚡ Faster management decisions

It converts raw operational data into actionable insights.
---

## 📂 Repository Structure
- `README.md` – Project documentation  
- `preview.png` – Dashboard screenshot  
- `.pbix` – Portfolio Power BI file (dummy data)  

---

## 🎯 Ideal Use Cases
- Garment manufacturing
- Footwear production
- FMCG batch tracking
- Multi-stage production environments
- Supply chain monitoring
- Vendor performance tracking

## 🏁 Conclusion

Manufacturing visibility should not depend on Excel follow-ups and WhatsApp updates.

This dashboard demonstrates how structured milestone tracking + simple logic + strong visualization can transform production monitoring.

- Small in size.
- Powerful in insight.
- Built for operational clarity.

---

👤 **Author:** Didarul Islam  
📌 *This project is part of my portfolio. All datasets are **dummy representations** — I strictly respect and protect the confidentiality of any organization I work with.*  
