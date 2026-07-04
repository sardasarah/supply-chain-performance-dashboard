# 📊 Supply Chain Performance Dashboard

## 🚚 Project Overview

This project features an executive-level Supply Chain and Logistics dashboard developed to analyze shipping efficiency and identify the root causes behind delivery bottlenecks. By transforming data from over $384B in revenue, this dashboard exposes critical service level agreement (SLA) failures and provides data-driven recommendations to optimize transport operations.

The analysis deep dives into key operational metrics, cross-referencing carrier performance, regional constraints, and seasonal trends to uncover supply chain vulnerabilities.





https://github.com/user-attachments/assets/41eab1b1-39b3-49dc-8e1c-431d6a99da19




---

## 🛠️ Key Steps & Methodology

1. **Data Engineering & Modeling:** Integrated and cleaned complex relational database tables into an efficient data model using Excel and Power Pivot.
2. **Dynamic KPI Architecture:** Created real-time metric cards for *Total Revenue*, *Avg Lead Time*, and *Late Delivered Rate* that dynamically recalculate via native DAX measures.
3. **Advanced Interactivity:** Implemented interconnected slicers (**Year** and **Customer Country**) with complete report connections to enable seamless root-cause investigation.

---

## 📈 Executive Insights & Deep Dives

Through interactive data exploration using the dashboard filters, several critical operational anomalies were uncovered:

### 🇺🇸 United States Market (High-Volume Constraints)

* **SLA Breakdown:** While driving the highest revenue, the US operation faces a chronic **57.30% late delivery rate** and an average lead time of **3.49 days**.
* **Product Bottleneck:** The primary logistical drag is heavily concentrated in the **Golf Bags & Carts** category.
* **Sessional Stress Point:** Delays are not uniform; they surge drastically into **August** spikes. This indicates that standard US carriers lack the capacity to scale and move bulk/heavy freight during peak summer vacation volumes.

### 🇵🇷 Puerto Rico Market (Geographical & Sessional Inversion)

* **Infrastructure Barrier:** Despite generating lower revenue, it shares an almost identical lead time of **3.50 days**. This proves that maritime/aerial transport schedules impose a fixed geographical constraint regardless of order volume.
* **Sazonal Shift:** In stark contrast to the US, Puerto Rico's logistical collapse occurs exclusively in **January**.
* **Target Vulnerability:** The leading category for delays shifts to **Fitness Accessories (66.67% delay rate)**. This reflects a "holiday hangover" port congestion in December/January combined with high post-New Year demand for fitness goods that local last-mile delivery chains fail to absorb.

---

## 🚀 How to Use

1. **Download:** Download the `.xlsx` dashboard file from this repository.
2. **Explore:** Open the file in Microsoft Excel and navigate to the main visual interface.
3. **Filter:** Use the **Year** and **Customer Country** slicers to dynamically watch the charts, KPIs, and Pareto distributions adapt, replicating the analytical investigation detailed above.
