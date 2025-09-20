# 📘 Data Storytelling Framework

**Document:** `07_data-storytelling-framework.md`
**Location:** `/docs/` folder in [Understanding Data Visualization](https://github.com/VibeHarboe/Understanding-Data-Visualization)

---

## 🎯 Purpose
This storytelling framework is designed to help data analysts, BI professionals, and strategy advisors present findings in a way that drives action. It provides a reusable structure to shape analysis into compelling business narratives that are easy to digest for both technical and non-technical stakeholders.

---

## 🧱 Framework Structure (SCQA + Pyramid Principle)

### 1. **S – Situation**
Set the business context. What's currently happening?
- Example: "Customer churn has risen steadily over the last two quarters."
- Real use: Describe the setting with KPIs or dashboard observations.

### 2. **C – Complication**
Introduce the business challenge or shift.
- Example: "Despite increased marketing efforts, user retention has not improved."
- Real use: Highlight a change, friction, or anomaly in the data.

### 3. **Q – Question**
Frame the decision or question your audience must consider.
- Example: "Why are premium users churning at a higher rate despite product upgrades?"
- Real use: This guides the interpretation of insights.

### 4. **A – Answer**
Deliver your data-backed recommendation or insight.
- Example: "Churn is driven by a disconnect between product adoption and value realization during onboarding."
- Real use: Lead with insight, follow with evidence.

---

## 🧠 Applying the Pyramid Principle
The SCQA structure feeds into the **Pyramid Principle** by placing the core insight (Answer) at the top, followed by layers of supporting data and logic:


## 📐 Pyramid Principle Example

Recommendation: Improve user onboarding flow
│
├── Insight A: Trend in user behavior  
│   └── Evidence: SQL analysis showed feature drop-off after Day 3  
│
├── Insight B: Feedback analysis  
│   └── Evidence: Topic modeling of user surveys revealed confusion around setup  
│
└── Insight C: Segment-level performance  
    └── Evidence: KPI dashboard shows higher churn among users aged 35–44


---

## 🗂️ Use Cases
| Scenario                                 | Example                                                                 |
|------------------------------------------|-------------------------------------------------------------------------|
| Executive summary                        | Present churn mitigation strategy to C-suite                           |
| Stakeholder onboarding                   | Frame data project kick-off with shared understanding                  |
| Product analytics report                 | Present findings from A/B testing and feature usage                    |
| Strategic OKR or KPI update              | Structure OKR dashboards into situation → insight → action             |
| BI sprint review                         | Wrap up BI backlog work with strategic framing                         |

---

## ✅ Best Practices
- Start with business language, not technical jargon
- Rehearse the narrative to ensure clarity and cohesion
- Anchor insights in business value (e.g., cost saved, conversion uplift)
- Always tailor structure based on audience

---

## 📌 Template Summary
```markdown
# 🎯 Executive Summary

**Situation:** What’s the business context?  
**Complication:** What new problem or opportunity emerged?  
**Question:** What is the key question or decision at hand?  
**Answer:** What is your recommendation?

---

# 🔍 Supporting Insights

## Insight 1: …
Evidence:

## Insight 2: …
Evidence:

## Insight 3: …
Evidence:

---

# 📈 Strategic Impact
- Outcome if applied (forecast or result)
- Related metric movements
