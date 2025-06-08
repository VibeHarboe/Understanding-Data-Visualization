# 🧭 Audience Mapping Guide

**Repository:** [Understanding Data Visualization](https://github.com/VibeHarboe/Understanding-Data-Visualization)  
**Category:** Data Communication Concepts  
**File:** `audience-mapping-guide.md`

---

This guide helps you tailor your analysis, communication, and visualization to different stakeholder types. It ensures that insights are relevant, digestible, and actionable for both technical and non-technical audiences.

---

## 👥 Common Stakeholder Types

| Stakeholder Type      | Focus                              | Data Literacy | Expectations                       |
|-----------------------|-------------------------------------|---------------|------------------------------------|
| C-Level Executives    | Strategy, ROI, market impact        | Low–Med       | Executive summary, visual KPIs     |
| Department Heads      | Goals, team performance, efficiency | Med–High      | Trends, alerts, key recommendations |
| Data Teams            | Technical validity, methodology     | High          | Full transparency, SQL/logic       |
| Product Managers      | User behavior, growth metrics       | Med           | Dashboards, cohort retention       |
| Sales / Ops           | Targets, pipeline, daily metrics    | Low–Med       | Quick visuals, goal progress       |

---

## 🎯 Mapping Framework

Use the framework below to adapt your data story to its intended audience.

### 🧱 1. Understand Their Goals

Ask:
- What business question are they trying to answer?
- What decisions are dependent on this insight?

🎓 _Example_:  
If the CFO is reviewing churn, they care more about **financial impact** than technical churn rate definitions.

---

### 🧱 2. Choose the Right Visualization

| Use Case                | Recommended Chart Type             |
|-------------------------|------------------------------------|
| Executive Summary       | KPI cards, bullet charts           |
| Trends Over Time        | Line charts, area plots            |
| Categorical Comparison  | Bar charts, dot plots              |
| Diagnostic Deep Dives   | Scatter plots, heatmaps            |

Visual design should support cognitive ease, not overwhelm.

---

### 🧱 3. Adjust Detail & Terminology

| Audience            | Use This Style                        |
|---------------------|----------------------------------------|
| Non-Technical       | Plain language, no SQL, no jargon      |
| Mid-Level Managers  | Some detail, light methods             |
| Technical Analysts  | Include assumptions, methods, queries  |

---

## 🔁 Example Mappings

| Insight                           | Stakeholder       | Tailored Output                               |
|----------------------------------|--------------------|------------------------------------------------|
| Weekly active users (WAU) drop   | Product Manager    | Line plot + segmented funnel table            |
| Revenue vs. CAC imbalance        | CFO                | Executive summary + bar chart                 |
| Data anomaly in churn rate       | Data Team          | SQL logic, timestamp, changelog reference     |

---

## ✅ Best Practices

- Ask for stakeholder feedback and iterate.
- Keep versions: one-pager (exec), slide deck (managers), SQL notebook (analysts).
- Visuals > Tables. Always include a 1-line takeaway per chart.

---

## 💡 Why This Matters

Misaligned communication leads to lost insight. Tailoring content ensures your hard work results in business value, stakeholder trust, and better decisions.

