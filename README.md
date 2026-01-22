# 📊 Lead Conversion Process Optimization (Quarterly Analysis)

## 📌 Project Overview
This project analyzes lead generation and conversion data from the past quarter to identify performance trends, operational bottlenecks, and optimization opportunities across the lead conversion funnel.

Using structured funnel analysis and validated findings from the accompanying analytical report, the project provides data-driven recommendations to improve conversion efficiency, reduce operational waste, and guide experimentation strategies.

The analysis follows the **PPDAC framework**:
**Problem → Plan → Data → Analysis → Conclusion**

---

## 1️⃣ Problem

Despite high lead volume, overall conversion performance remains low and uneven across lead sources. Key business challenges include:

- Identifying **high-quality lead sources**
- Understanding which **engagement activities drive conversions**
- Detecting **funnel drop-off points** where leads disengage
- Improving conversion rates without increasing agent workload

---

## 2️⃣ Plan

To address these challenges, the analysis focused on:

1. Evaluating lead performance across funnel stages:
   - Lead Posted → Workable → Converted
2. Comparing lead sources by:
   - Conversion rate
   - Workable rate
   - Average dials per lead
   - Agent hours per conversion
3. Assessing engagement effort vs. conversion outcomes
4. Identifying operational and quality bottlenecks
5. Proposing actionable optimizations and controlled A/B tests

---

## 3️⃣ Data

### Data Sources
- **Primary Dataset:**  
  `Data set_ Assignment Pro. Ops Analyst.xlsx`
- **Supporting Analysis:**  
  `Adejoro Raymond Olaotan Lead Conversion Process Assignment.pdf`

### Key Fields Used
- Lead source
- Leads posted
- Workable leads
- Converted leads
- Average dials per lead
- Stop action / disqualification indicators

### Derived Metrics
- Conversion rate
- Workable %
- Engagement efficiency
- Agent hours per conversion

### Dataset Summary
- **Total leads analyzed:** 45,887  
- **Overall conversion rate:** ~1.5–4% (varies by source)  
- **Average workable rate:** ~50%

---

## 4️⃣ Analysis

### 4.1 Lead Source Performance

| Lead Source | Volume | Conversion Rate | Agent Hrs / Conversion | Performance |
|------------|--------|-----------------|------------------------|-------------|
| sf7if44 | 3,530 | 2.27% | 2.19 | ⭐ Star Performer |
| fx6exmg | 535 | 2.06% | 1.56 | 💎 Hidden Gem |
| ie14stia | 7,973 | 1.81% | 2.99 | Solid |
| wt11ifia | 9,865 | 1.64% | 4.95 | ⚠ High Cost |
| ld8drar | 3,859 | 0.88% | 3.28 | Underperformer |
| lt16roia | 933 | 0.54% | 3.00 | ❌ Critical Concern |

**Key Insight**
High-performing sources convert earlier in the funnel with fewer engagement attempts, while low-quality sources require excessive agent effort with minimal returns.

---

### 4.2 Engagement Effectiveness

- Increased dialing improves conversion **only for high-intent sources**
- Over-dialing low-quality leads leads to diminishing returns
- wt11ifia consumes nearly **5 agent hours per conversion**, double that of top performers

---

### 4.3 Funnel Drop-Off Points

#### 🔻 Primary Drop-Off: Contact Rate
- fx6exmg has strong intent and a **48% closing rate**
- Contact rate is low (28%), indicating reachability issues

#### 🔻 Secondary Drop-Off: Closing Rate
- ii9icnt has high contact (42%) but poor close (7.7%)
- Indicates qualification or messaging mismatch

#### 🔻 Structural Disqualification
- Leads with “Other” carriers show:
  - Lower contact rates
  - Significantly weaker conversion performance

---

## 5️⃣ Conclusions

- Lead quality and early engagement are stronger drivers of conversion than outreach volume
- The largest funnel loss occurs **before leads become workable**
- Excessive dialing on low-quality leads increases cost without improving outcomes
- A small subset of lead sources delivers the majority of efficient conversions

---

## 6️⃣ Recommendations

### Strategic Actions
- Reallocate budget from **lt16roia** and **ld8drar** to **sf7if44** and **ie14stia**
- Scale **fx6exmg** despite lower volume due to superior efficiency
- Prioritize mobile carriers with higher contact probability

### Operational Improvements
- Audit wt11ifia calls and tighten early qualification
- Align ii9icnt marketing copy with actual product offering
- Implement smarter engagement limits by lead quality

---

## 7️⃣ Proposed A/B Tests

| Experiment | Objective | Target Source | Test Design |
|-----------|---------|--------------|-------------|
| SMS Warm-Up | Increase contact rate | fx6exmg | SMS before first call vs none |
| Aggressive Dialing | Salvage low conversion | lt16roia | 12 vs 20 dials over 3 days |
| Script Variation | Improve closing rate | ii9icnt | Standard vs early qualification script |

---

## 📌 Final Takeaway

Improving lead conversion performance requires **smarter source prioritization, earlier intent validation, and disciplined engagement strategies**—not more dialing. By focusing on efficiency-driven decisions and validating changes through experimentation, organizations can significantly improve conversion outcomes while reducing operational waste.

---

📁 **Repository Contents**
- `/data` – Raw dataset
- `/analysis` – Supporting calculations and metrics
- `/README.md` – Project documentation
