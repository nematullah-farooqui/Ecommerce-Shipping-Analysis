# 🚨 E-commerce Shipping Crisis Analysis

## 📋 Project Overview
An e-commerce company is facing severe **delivery performance issues** that threaten both customer retention and business survival.  
- **40% of shipments arrive late**  
- **Customer satisfaction critically low (2.99 / 5)**  

This analysis uncovers the **root causes** and provides a roadmap for **operational transformation**.

---

## 🔑 Core Crisis
The **priority shipping system** is failing:  
- Only a **6% improvement** for high-importance shipments  
- All service levels perform **~30% below industry standards**  
- Even critical deliveries face a **35% late rate** → unacceptable risk for key customers  

---

## 🎯 Business Questions
1. Why do 40% of shipments arrive late?  
2. Is the "high importance" classification effectively protecting critical deliveries?  
3. Which shipping modes and warehouses perform best/worst?  
4. How are customers impacted (calls, satisfaction, churn risk)?  
5. Does the company need optimization or **complete transformation**?  

---

## 🛠️ Analysis Framework
- **Performance Baseline:** Current on-time delivery across all segments  
- **Priority System Effectiveness:** True impact of product importance  
- **Operational Analysis:** Shipping modes & warehouse efficiency  
- **Customer Impact:** Correlation with care calls & ratings  
- **Strategic Assessment:** Optimization vs. transformation  

---

## 📊 Dataset & Methodology
- **Records:** 10,999 shipments  
- **Source:** Internal logistics system  
- **Time Period:** Not specified (full dataset sample)  
- **Tools:** Microsoft Excel (end-to-end analysis)  

---

## 📖 Data Dictionary
| Column               | Description              | Type         | Business Significance             |
|----------------------|--------------------------|-------------|-----------------------------------|
| Reached.on.Time_Y.N  | 0 = On-time, 1 = Late   | Target      | Primary performance metric        |
| Mode_of_Shipment     | Flight / Ship / Road    | Categorical | Transportation efficiency         |
| Warehouse_block      | A / B / C / D / F       | Categorical | Storage & processing capability   |
| Customer_care_calls  | 2–7 calls               | Numerical   | Customer distress indicator       |
| Customer_rating      | 1–5 scale               | Numerical   | Satisfaction measurement          |
| Product_importance   | Low / Medium / High     | Categorical | Priority system effectiveness     |
| Discount_offered     | 1–70%                   | Numerical   | Customer value segmentation       |
| Weight_in_gms        | Product weight          | Numerical   | Logistics complexity              |

---

## 📈 Key Findings

### 1. Overall Performance
| Metric                 | Value                     |
|-------------------------|---------------------------|
| On-time Delivery Rate   | 59.66% (6,563 / 10,999)  |
| Late Delivery Rate      | 40.34% (4,436 shipments) |
| Customer Satisfaction   | 2.99 / 5 (Critical level)|

➡️ **Industry Benchmark:** 90%+ on-time is expected; <80% threatens survival.

---

### 2. The Priority System Illusion
| Product Importance | On-time Rate | Late Rate | "Improvement" |
|--------------------|--------------|-----------|---------------|
| High Importance    | 65%          | 35%       | +6%           |
| Medium Importance  | 59%          | 41%       | Baseline      |
| Low Importance     | 59%          | 41%       | Baseline      |

⚠️ **Insight:** The system creates a *false sense of security*. High-value shipments still fail **35% of the time**.

---

### 3. Operational Performance

#### Shipping Mode Efficiency
| Mode   | Late Delivery Rate | Performance | Insight              |
|--------|---------------------|-------------|----------------------|
| Road   | 58.8%              | Best        | Most reliable option |
| Ship   | 59.8%              | Average     | Moderate reliability |
| Flight | 60.2%              | Worst       | Surprisingly poor    |

#### Warehouse Ranking
| Warehouse | Late Delivery Rate | Rank | Action Required         |
|-----------|---------------------|------|-------------------------|
| B         | 60.2%              | 1st  | Model processes         |
| F         | 59.9%              | 2nd  | Good performance        |
| D         | 59.7%              | 3rd  | Acceptable              |
| C         | 59.7%              | 4th  | Needs review            |
| A         | 58.7%              | 5th  | Immediate investigation |

---

### 4. Customer Experience
| Care Calls | On-time Rate | Performance Drop | Interpretation         |
|------------|--------------|------------------|------------------------|
| 2 calls    | 65%          | Baseline         | Normal service         |
| 3 calls    | 63%          | -2%              | Early concerns         |
| 4 calls    | 60%          | -5%              | Growing issues         |
| 5 calls    | 58%          | -7%              | Significant problems   |
| 6–7 calls  | 48%          | -17%             | System failure         |

➡️ Customers making **6+ calls** face “coin-flip” delivery odds → complete service breakdown.

---

### 5. Discount Strategy Impact
- **Low discount orders (1–10%)**: Only **47% on-time**  
- **High discount orders:** Too few records for analysis  
- **Concern:** Regular, loyal customers receive **the worst service levels**  

---

## 🚨 Strategic Assessment

### Crisis Diagnosis
- **Foundation Failure:** All service levels lag **30%+ below industry benchmarks**  
- **Priority Weakness:** Only **6% improvement** → ineffective protection for critical shipments  
- **Customer Impact:** Low satisfaction (**2.99/5**) & high distress calls  
- **Systemic Issues:** Failures across warehouses and shipping modes  

### Business Impact
| Dimension              | Risk Level | Description                                           |
|------------------------|------------|-------------------------------------------------------|
| Customer Retention     | High       | Dissatisfied customers will churn                     |
| Brand Reputation       | Severe     | Unreliable delivery destroys trust                    |
| Revenue                | Significant| Failed priority shipments threaten key accounts       |
| Operational Costs      | High       | Excessive customer service calls escalate expenses    |

---

## 💡 Transformation Roadmap

**Phase 1: Emergency Stabilization (0–30 Days)**  
- CEO-led crisis response team  
- Immediate Warehouse A investigation & fixes  
- Flight contract review with stricter SLAs  
- Protect critical shipments via **Warehouse B + Road**  

**Phase 2: Foundation Repair (1–3 Months)**  
- Carrier performance audit & renegotiation  
- Real-time tracking system rollout  
- Customer communication overhaul for delays  
- Standardized service recovery protocols  

**Phase 3: Strategic Transformation (3–12 Months)**  
- Complete logistics redesign  
- Restructure carrier partnerships with incentives  
- Predictive analytics for delivery management  

---

## 📈 Success Metrics
- **On-time Delivery:** 85% in 6 months → 90% in 12 months  
- **Customer Rating:** ≥ 4.0 within 9 months  
- **Priority Gap:** ≥ 15% improvement for critical shipments  
- **Care Calls:** 50% reduction in 4+ call cases  

---

## 🛠 Technical Appendix
- **Data Cleaning:** Validation with Excel functions  
- **Analysis:** Comparative metrics across shipment segments  
- **Visualization:** Pivot tables & charts for insights  
- **Benchmarking:** Industry standard comparisons  
- **Files Included:**  
  - `E commerce Shipping Analysis.xlsx` → complete analytical workbook  

---

## 🎯 Conclusion
This is **not an optimization problem** — it is a **transformation mandate**.  
Incremental improvements will fail. The company must **choose between managing decline or rebuilding its logistics foundation**.  
