# Superstore-Business-Performance-Analysis

## **Overview**

This project is a **comprehensive sales dashboard** built entirely in **Microsoft Excel**, utilizing **Power Query, Power Pivot, and DAX** for data processing, modeling, and visualization. The dashboard provides insights into key performance metrics, product market trends, and regional sales distribution, allowing users to interactively explore sales data through **slicers and navigational controls**.

## **Features**

- **Built-in Excel**: No external tools or software required.
- **Power Query for Data Cleaning & Structuring**: Efficiently cleaned, transformed, and modeled the dataset.
- **Power Pivot for Data Modeling**: Created relationships, calculated measures, and developed a dynamic calendar table.
- **Interactive Dashboards**: Users can navigate seamlessly between three dashboards covering different aspects of sales performance.
- **Slicers for Filtering**: Users can filter by **Time, Region, Product Category, and Customer Segment**.
- **Diverse Visualizations**: Includes **KPIs, Pareto charts, bar charts, line charts, maps, and heatmaps** to highlight key insights.

![Image](https://github.com/user-attachments/assets/c6769b3d-e42a-46fb-a79d-3fc6694d8c63)
---

## **Introduction**  

This project analyzes a **Superstore Sales Dataset** from **January to June 2015**, focusing on sales performance across different product categories, regions, and customer segments. The data pertains to orders within the **United States**, and all monetary values are in **USD ($)**.  

The dataset includes:  

- **Orders Data:** Contains all essential transaction details, including order date, product category, quantity, sales, discount, profit, shipping mode, and customer segment.  
- **Returns Data:** Tracks product returns, helping assess return rates and their impact on profitability.  
- **User Data:** Includes managerial and regional assignments, aiding in sales performance analysis across different areas.  

To facilitate **time-based analysis**, a **Calendar Table** was created in **Power Query**, allowing advanced **DAX measures** to calculate critical date-based insights. The **Data Model** establishes relationships between these tables, enabling seamless data connectivity and in-depth analysis.

---

## **Performance Report – Superstore (Jan–June 2015)**  

This report provides a **data-driven assessment** of Superstore’s overall performance from **January to June 2015**, identifying key patterns, anomalies, and actionable insights based on sales, profit, and segment-wise contributions.  

---

### **Key Financial Metrics:**  
- **Total Revenue:** **$1.9M**  
- **Total Profit:** **$0.2M** (**12% profit margin**)  
- **Total Orders:** **1.4K**  

While revenue figures are promising, the **12% margin** indicates opportunities for cost optimization and pricing adjustments.  

---

### **Profitability Trends – Identifying Anomalies**  
A **month-over-month analysis** reveals significant fluctuations in profitability:  

| **Month**  | **Sales ($M)** | **Profit (%)** | **Key Observations** |  
|------------|---------------|----------------|------------------------|  
| January   | 0.3M          | 0%             | **Zero profit despite stable revenue**—possible excessive discounting or high operational costs. |  
| February  | 0.3M          | 11%            | Recovery likely due to **seasonal demand (Valentine’s Day) or strategic promotions.** |  
| March     | 0.3M          | 0%             | **Profitability drops back to zero**, highlighting an inconsistent pricing model. |  
| April     | 0.4M          | 14%            | First signs of sustained growth. **Small Business segment peak at 30%.** |  
| May       | 0.3M          | 22%            | **Most profitable month**—suggesting strong demand and better product mix. |  
| June      | 0.3M          | 19%            | Profit remains strong, **sales led by Corporate and Home Office segments.** |  


**Takeaway:** The **inconsistent profitability** in Q1 (Jan–March) suggests **poor cost control or heavy discounting**, whereas **April–June saw stabilization**, potentially due to refined sales strategies. This highlights a **need to reassess pricing and discount structures, particularly in Q1.**  

---

### **Customer Segment Performance – Revenue Contribution & Stability**  
A breakdown of revenue by **customer segment** highlights key drivers:  

- **Corporate (35%)** – Largest contributor but shows **profitability inconsistencies** (losses in January and March).  
- **Home Office (24%)** – Second-largest contributor but with **unsteady profit margins** (loss in April).  
- **Consumer (21%)** – Generally profitable, except for **March (-23%) loss**.  
- **Small Business (21%)** – Modest profits in Q1, **significantly stronger performance in later months (21-26%).**  

**Takeaway:** **Corporate & Home Office segments require margin optimization.** Bulk orders from Corporate may be heavily discounted, reducing profitability. Meanwhile, **Small Business is emerging as a high-growth segment** in Q2, warranting **targeted engagement strategies.**  

---

### **Order Trends – When Are Sales Happening?**  
📊 **Weekly Order Spikes:** **Consistent increases in sales occur in Weeks 4 (Jan, May), Week 5 (March), and Week 2 (April, June).**  
📆 **Day-Wise Performance:** **Saturday (24%) and Friday (16%) dominate sales**, while mid-week sales remain lower.  

**Analysis:**  
- High **weekend sales** indicate a **strong B2C demand cycle**—potential opportunity to introduce **midweek promotions** to balance revenue distribution.  
- End-of-month order spikes **could be driven by corporate procurement cycles**—a signal to **optimize bulk order offerings around these peaks.**  

---

### **Regional Performance – Identifying Gaps & Growth Areas**  
A **manager-wise revenue breakdown** exposes regional disparities:  

| **Manager (Region)** | **Revenue Share (%)** | **Profitability Trend** | **Key Concern** |  
|----------------------|----------------------|----------------------|----------------|  
| **Chris (Central)**  | 23%                  | **Stable (17%)**      | Balanced performance. |  
| **Erin (East)**      | 31%                  | **Improving (14%)**   | High losses in Jan & Feb (-12%, -5%). |  
| **Sam (South)**      | 19%                  | **Negative (-4%)**    | **Major losses in Feb (-24%) & March (-27%).** |  
| **William (West)**   | 27%                  | **Stable (14%)**      | Weak April (-6% profit). |  

🔴 **Critical Concern: Sam (South) is underperforming (-4% loss overall).**  
- **February (-24%) and March (-27%) losses** indicate possible **weak regional demand, operational inefficiencies, or high return rates.**  
- Needs **urgent intervention—product realignment, price optimization, and region-specific marketing.**  

**Takeaway:** Targeted **regional interventions are needed.** While Erin (East) has recovered, **Sam’s region remains a loss center.**  

---

### **Key Recommendations – Data-Driven Business Actions**  

1️⃣ **Optimize Corporate Segment Profitability** – Reevaluate bulk discounting and introduce **tiered pricing strategies** to improve margins.  

2️⃣ **Address Q1 Profitability Gaps** – **January and March require margin-focused strategies**, possibly limiting deep discounts and optimizing product mix.  

3️⃣ **Expand Small Business Focus** – Strong Q2 performance suggests an opportunity for **segment-specific promotions and loyalty incentives.**  

4️⃣ **Balance Sales Distribution** – **Midweek promotions** can reduce dependency on **weekend peaks.**  

5️⃣ **Regional Strategy for South** – **Loss-making region requires targeted adjustments** in product pricing, customer engagement, and potential cost restructuring.  

---

### **Visualizations to Support Analysis**  
To effectively present these insights, consider including:  
✅ **Stacked Bar & Line Charts:** Revenue, cost, and profit trends over months.  
✅ **Bar Charts:** Customer segment contributions and profitability.  
✅ **Pie Chart:** Day-wise sales distribution.  
✅ **Regional Heatmap:** Manager performance by location.  

**Conclusion:**  
Superstore’s first half of 2015 highlights **inconsistent profitability, regional disparities, and shifting segment performances.** While May and June saw **profit stabilization**, **losses in Q1 and South region underperformance remain key challenges.** Addressing these with **data-driven pricing, regional optimization, and segment-focused strategies** will be critical for sustainable growth.



