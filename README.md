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

Aqui está a tradução dos seus insights para um inglês corporativo impecável, ideal para documentações formais, apresentações executivas ou para estruturar o seu portfólio no GitHub.

Mantive os termos técnicos do universo de *Supply Chain & Analytics* (como *SLA*, *Lead Time*, *Picking/Packing* e *Spot Fleet*) que os recrutadores adoram ler.

---

# 📊 Supply Chain Executive Insights & Deep Dive Report

## Part 1: Macro Overview and Regional Trends

### 1. Macro Overview and Service Level Agreement (SLA) Alert

* **The Data:** Accumulated revenue is highly expressive ($384.6 Billion), yet the overall average late delivery rate (*Late Delivered Rate*) stands at 57.3%.
* **The Insight:** More than half of all goods sold arrive outside the timeframe promised to the customer. This indicates a chronic breakdown in the Service Level Agreement (SLA). While the commercial department is generating a billion-dollar sales volume, operational inefficiency is putting customer retention and loyalty at extreme risk.

### 2. Critical Bottlenecks by Product Category (Pareto Analysis)

* **The Data:** The "Top 10 Categories with Highest Delay Rates" chart shows that the *Golf Bags & Carts* category leads the inefficiency ranking, with a staggering 68.85% of its deliveries delayed. It is followed closely by *Lacrosse* (62.61%) and *Pet Supplies* (61.44%).
* **The Insight:** The delay issue is not uniform; it is severely aggravated by specific product categories. Bulky items or those with more complex supply chains (such as oversized sports equipment) are bottlenecking the fulfillment or transportation process.
* **Recommended Action:** Conduct a targeted process mapping for *Golf Bags & Carts* to evaluate whether the bottleneck occurs during internal preparation (picking/packing) or due to a lack of certified carriers equipped for oversized freight.

### 3. Logistics Performance and Shipping Mode Contradictions (Carrier Performance)

* **The Data:** Cross-referencing the average shipping time (*Avg Lead Time*) with the delay rate per shipping mode reveals that *Same Day* shipping achieves the lowest average transit time (0.5 days) but still suffers a late delivery rate close to 60% on the secondary axis. *Second Class* and *Standard Class* modes operate at their maximum time limits (nearly 4 days) and consistently breach delivery targets.
* **The Insight:** There is a severe failure in either the delivery promise or route optimization. If a service purchased as *Same Day* fails 60% of the time, the company is charging a premium for a service it cannot fulfill, leading to immediate customer frustration and shattered expectations.
* **Recommended Action:** Urgently review contracts and the delivery windows promised at checkout on the e-commerce platform for express shipping. If the current logistics network cannot support immediate dispatch, the customer-facing timeline must be recalibrated.

### 4. Critical Time-Series Seasonality (Monthly Late Delivery Trend)

* **The Data:** The monthly trend displays a healthy decline in delays from January through May (reaching a minimum of ~32%), followed by a drastic explosion in August, where the late delivery rate peaks at over 70%. In September, the index retreats back to the 35% range.
* **The Insight:** The logistics operation suffers from a severe inability to absorb seasonal peaks. August represents the system's maximum stress point. This typically occurs due to a sudden surge in demand (such as Q3 inventory building or specific campaigns) where partner carriers cannot handle the dispatched volume.
* **Recommended Action:** Implement advanced Logistics Capacity Planning. For upcoming cycles, the company must secure contract space guarantees and extra on-demand third-party fleets starting in June/July, preempting the inevitable August bottleneck.

---

## Part 2: Interactive Filter Deep Dive (US vs. Puerto Rico)

### 1. United States Scenario: Mass Operation and Heavy Freight Bottlenecks

The United States accounts for the company's largest revenue share, dictating the overall pace of the dashboard's macro averages. However, the operation suffers from a severe lack of responsiveness during specific periods.

* **Operational Metrics:** Features an average transit time (*Avg Lead Time*) of 3.49 days and a late delivery rate of 57.30%.
* **The Core Bottleneck Category:** The primary logistical bottleneck on US soil is concentrated in the Golf category (*Golf Bags & Carts*).
* **Critical Seasonality:** Delays are not steady; they explode into massive spikes specifically during the month of August.
* **Analyst's Diagnosis:** The August spike coincides with the US summer vacation and peak travel season. The fact that the *Golf* category leads delays indicates that standard US carrier networks lack the capacity to move heavy/bulky freight during peak seasonal demand, triggering a local distribution collapse.

### 2. Puerto Rico Scenario: Geographical Limitations and Seasonal Inversion

Puerto Rico is the market with the lowest revenue contribution, yet it reveals some of the most intriguing and hazardous behaviors regarding supply chain efficiency.

* **Operational Metrics:** Registers an *Avg Lead Time* of 3.50 days (slightly higher than the US) and a subtly lower late delivery rate of 57.27%.
* **The Core Bottleneck Category:** Unlike the American market, the *Golf* category shows a significant improvement (dropping to a 62.50% delay rate), yielding the worst-performing spot to *Fitness Products*, which surge to an alarming **66.67%** late delivery rate.
* **Critical Seasonality:** The timeline curve completely inverts compared to the US, presenting critical delay peaks exclusively in the month of January.
* **Analyst's Diagnosis:**
* *Infrastructure Bottleneck:* The fact that Puerto Rico generates much less revenue but demands the same 3.50 days (or more) of transit time as the US proves that maritime or air forwarding imposes an unavoidable physical barrier on lead times.
* *The January "Hangover" Effect:* The delay peak in January reflects local port and customs congestion following the holiday season. Because Puerto Rico relies heavily on imports, the local supply chain freezes at the beginning of the year. *Fitness Products* (likely driven by customers' New Year's resolutions) suffer from stockouts or a total breakdown in local last-mile delivery networks on the island.



---

## 🛠️ Recommended Business Action Plan

1. **Summer Route Optimization & Capacity (US):** Contract specialized, on-demand third-party fleets (*Spot Fleet*) tailored for oversized freight specifically for the months of June through August in the US, prioritizing the distribution of *Golf Bags*.
2. **Local Inventory Pre-positioning (Puerto Rico):** For the Puerto Rican market, inventory for *Fitness Products* must be shipped from the main hub to the island before November. This prevents high-demand goods from getting trapped in the inevitable January port and customs bottleneck.
## 🚀 How to Use

1. **Download:** Download the `.xlsx` dashboard file from this repository.
2. **Explore:** Open the file in Microsoft Excel and navigate to the main visual interface.
3. **Filter:** Use the **Year** and **Customer Country** slicers to dynamically watch the charts, KPIs, and Pareto distributions adapt, replicating the analytical investigation detailed above.
