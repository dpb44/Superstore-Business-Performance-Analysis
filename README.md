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



### **Key Financial Metrics:**  
- **Total Revenue:** **$1.9M**  
- **Total Profit:** **$0.2M** (**12% profit margin**)  
- **Total Orders:** **1.4K**  

While revenue figures are promising, the **12% margin** indicates opportunities for cost optimization and pricing adjustments.  



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



### **Customer Segment Performance – Revenue Contribution & Stability**  
A breakdown of revenue by **customer segment** highlights key drivers:  

- **Corporate (35%)** – Largest contributor but shows **profitability inconsistencies** (losses in January and March).

![Image](https://github.com/user-attachments/assets/07a4a172-da99-4242-8445-387fa536dbb3)
  
- **Home Office (24%)** – Second-largest contributor but with **unsteady profit margins** (loss in April).

![Image](https://github.com/user-attachments/assets/0eaeb81c-b2f4-4b4a-b9b4-af7263cac9af)

- **Consumer (21%)** – Generally profitable, except for **March (-23%) loss**.

![Image](https://github.com/user-attachments/assets/bb05533c-0576-46b4-9d8d-5f430928ee87) 
 
 
- **Small Business (21%)** – Modest profits in Q1, **significantly stronger performance in later months (21-26%).**

![Image](https://github.com/user-attachments/assets/2ccec213-99ed-43c4-8387-961cab7141e9)


**Takeaway:** **Corporate & Home Office segments require margin optimization.** Bulk orders from Corporate may be heavily discounted, reducing profitability. Meanwhile, **Small Business is emerging as a high-growth segment** in Q2, warranting **targeted engagement strategies.**  



### **Order Trends – When Are Sales Happening?**  
**Weekly Order Spikes:** **Consistent increases in sales occur in Weeks 4 (Jan, May), Week 5 (March), and Week 2 (April, June).**  

![image](https://github.com/user-attachments/assets/b699512c-824f-4191-891e-7451643a3a4a)

 **Day-Wise Performance:** **Saturday (24%) and Friday (16%) dominate sales**, while mid-week sales remain lower. 

 ![image](https://github.com/user-attachments/assets/64b702b9-9a12-4ee1-bc81-8d8de7f6b571)


**Analysis:**  
- High **weekend sales** indicate a **strong B2C demand cycle**—potential opportunity to introduce **midweek promotions** to balance revenue distribution.  
- End-of-month order spikes **could be driven by corporate procurement cycles**—a signal to **optimize bulk order offerings around these peaks.**  



### **Regional Performance – Identifying Gaps & Growth Areas**  
A **manager-wise revenue breakdown** exposes regional disparities:  

| **Manager (Region)** | **Revenue Share (%)** | **Profitability Trend** | **Key Concern** |  
|----------------------|----------------------|----------------------|----------------|  
| **Chris (Central)**  | 23%                  | **Stable (17%)**      | Balanced performance. |  
| **Erin (East)**      | 31%                  | **Improving (14%)**   | High losses in Jan & Feb (-12%, -5%). |  
| **Sam (South)**      | 19%                  | **Negative (-4%)**    | **Major losses in Feb (-24%) & March (-27%).** |  
| **William (West)**   | 27%                  | **Stable (14%)**      | Weak April (-6% profit). |  

**Critical Concern: Sam (South) is underperforming (-4% loss overall).**  
- **February (-24%) and March (-27%) losses** indicate possible **weak regional demand, operational inefficiencies, or high return rates.**  
- Needs **urgent intervention—product realignment, price optimization, and region-specific marketing.**  

**Takeaway:** Targeted **regional interventions are needed.** While Erin (East) has recovered, **Sam’s region remains a loss center.**  

---

## **Product Market Analysis**  

This section evaluates product performance, profitability, and purchasing behaviors, offering data-driven insights to optimize sales strategies.  


### **Key Sales & Profitability Metrics**  
- **Total Quantity Sold:** **25K products**  
- **Average Discount Provided:** **5%**

The discount is more or less consistent within the 4.5 to 5.2% range. So our previous consideration of possible high discounts causing imbalnces is disregarded. 

**Top Performers and Underperforming Products**  
![image](https://github.com/user-attachments/assets/ce51b8d5-8843-47db-bffe-d4633c7d3904)


**Labels (143% profit)** lead profitability, likely due to their low cost, high markup, and strong corporate demand, followed by copiers (24%), binders (32%), and fax machines (24%), which remain essential office staples. Conversely, rubber bands (-86%) suffer from excessive low margins, while scissors, rulers, trimmers (-19%), and envelopes (-11%) face intense competition and commoditization, limiting profitability.

**Takeaway:**  
- **Office supplies dominate profitability,** reinforcing that **corporate and home office customers drive demand.**  
- **Unprofitable items (rubber bands, scissors, envelopes) may require price adjustments or bundling strategies** to improve margins.  


### **Revenue Concentration – The 70/30 Rule (Pareto Chart Analysis)** 

![image](https://github.com/user-attachments/assets/d2e072f0-9e64-47d4-8dce-50c7d8f9e7f5)
 
A **Pareto analysis** shows that **70% of revenue** is generated by just a few key product categories:  
- **Top Contributors:** **Office Machines, Chairs, Telephones, Tables, Binders, Storage, Organizers.**  
- **Next 17% Contribution:** **Bookcases, Copiers, Computers, Office Furnishings, Appliances, Paper, and Art Supplies.**  
- **Bottom 3% Contribution:** **Rubber Bands, Scissors, and other low-margin office supplies.**  

**Takeaway:**  
- **The business is highly reliant on office-related products.**  
- **Low-revenue items are insignificant contributors to overall sales** and should either be repositioned or phased out.  



### **Delivery & Returns Analysis** 


- **Return Rate:** **~1%** (Low, indicating good product-market fit)  
- **67% of returned items are Tech Products** (Copiers, Telephones, etc.), likely due to **defective units or buyer remorse.**  

![image](https://github.com/user-attachments/assets/4d060242-d2b1-4375-a2f0-af953c2fc7a3)


**Delivery Mode Efficiency:**  
- **Average Delivery Time:** **~2 days**  
- **Low-priority orders take ~4 days (Regular Air, Truck), ~3.5 days (Express Air).**  
- **All other priority orders (Medium, High, Critical) are delivered within 1.5 days, regardless of transportation mode.**

![image](https://github.com/user-attachments/assets/f7640fae-6553-4562-9c02-ac2e6cefcd1e)


**Takeaway:**  
- **Expedited delivery offers little benefit unless for low-priority items**—indicating a potential cost-saving opportunity by limiting unnecessary "express" shipments.  
- **High return rate in tech products suggests a need for better product descriptions or post-sales support.**  


### **Packaging Insights** 

**Majority of orders are packed in:**  
- **Small Boxes (60%)** – Likely office supplies (Binders, Labels, Paper).  
- **Wrap Bags (19%)** – Likely lightweight, smaller items.  
- **Small Packs (16%)** – Often used for multipack office essentials.

![image](https://github.com/user-attachments/assets/23fcb8dd-99fa-4da0-8f9e-0ca01fa8e049)

**Larger packaging (Jumbo Box, Drum) is mainly used for furniture (Tables, Chairs, Bookcases).**  

![image](https://github.com/user-attachments/assets/01afeea9-b993-4892-897f-4e1495c09947)


**Takeaway:**  
- **Most shipments are small, lightweight office products,** reinforcing that corporate and home office customers drive sales.  
- **Furniture-related products require bulkier packaging, leading to higher shipping costs.**  


### **Product Category Analysis**  

| **Category**         | **Top Performers**                                     | **Loss-Makers**                                  | **Key Insights**                                                 |
|----------------------|------------------------------------------------|--------------------------------------|----------------------------------------------------------------|
| **Furniture**       | Chairs (19%), Office Furniture (19%)           | Bookcases                            | Bulk corporate purchases drive profitability; high storage & transport costs hurt bookcases. |
| **Office Supplies** | Labels (143%), Binders, Appliances             | Rubber Bands, Scissors, Envelopes    | Small, low-cost items may be underpriced or over-discounted. |
| **Technology**      | Copiers, Telephones, Office Machines (All Profitable) | None                                 | Higher price points create better margins despite higher return rates. |

**Takeaway:**  
- **Office supplies and tech products are core revenue drivers.**  
- **Heavy furniture (Tables, Bookcases) needs better logistics cost management.**  


### **Customer Segment Analysis – Who Buys What?**  
**Consumers:** **Favor Labels, Paper, and Binders** but experience **losses on Scissors.**  
**Corporate:** **Huge profit margin (365%) on Labels, Binders, Fax Machines.**  
**Home Office:** **Purchases mostly Chairs, Labels, Scissors.**  
**Small Business:** **Major buyers of Copiers & Envelopes.**  

**Takeaway:**  
- **Corporate customers dominate high-profit items (Labels, Binders).**  
- **Home Office & Small Business show diverse product needs, requiring tailored marketing.**  

---

## **Geographical Analysis and Trends**  

The **East (31%) and West (27%)** drive the majority of sales, while **Central (23%)** follows closely.  Despite strong revenue generation, **Central (17%)** remains the most profitable region, followed by **West (14%) and East (14%)**, whereas **South faces a -4% loss.** 

![image](https://github.com/user-attachments/assets/7caa5b31-6219-4537-ab34-409417b021d5)

The **South (19%)** underperforms, largely due to inconsistent profitability across its cities:

![image](https://github.com/user-attachments/assets/23b93781-2465-417f-9475-8235429ead6e)

City-wise, **Pensacola (33%) and Asheville (10%)** lead in profits, whereas **Danville (-57%) and Kissimmee (-18%)** drag overall performance down. Unlike other regions with stable city-level profitability, **South is highly volatile, with extreme highs and lows.**  


### **Product & Segment Performance by Region** 
  

| **Category**       | **Highest Sales**       | **Profitability**                                      | **Key Concern**                                  |
|--------------------|------------------------|------------------------------------------------------|------------------------------------------------|
| **Furniture**      | East & West            | **West (27%) profit**, **East (0%) despite high sales** | East's **high revenue but no profit** suggests cost inefficiencies. |
| **Office Supplies** | East                   | **East (27%) profit**, **Central (25%) profit despite lower revenue** | South struggles with losses in this category. |
| **Technology**     | West                    | **West (5%) profit**, **Central & East (19-25%) profit despite lower sales** | West has **high sales but low margins**—potential pricing or cost issue. |  



Customer-wise, **West dominates sales but has lower profit margins than Central & East.** **South struggles with corporate clients (-21% loss), making it the weakest segment-region combination.**  

---

## Key Recommendations – Data-Driven Business Actions  

| **Focus Area**              | **Recommendation**                                      | **Expected Impact**                              |
|-----------------------------|--------------------------------------------------------|------------------------------------------------|
| **Corporate Segment**       | Reevaluate bulk discounting, introduce tiered pricing. | Improve profit margins without sacrificing sales. |
| **South Region Strategy**   | Adjust product pricing, customer engagement, and cost structure. | Reduce losses and stabilize profitability. |
| **Office Supplies Pricing** | Reduce discounts on high-demand items (Labels, Binders, Copiers). | Maximize revenue from already strong-performing products. |
| **Loss-Making Products**    | Reassess Rubber Bands, Scissors, Envelopes—reprice, bundle, or discontinue. | Eliminate unprofitable SKUs or reposition them for better sales. |
| **Furniture Profitability** | Optimize shipping/storage costs, negotiate vendor terms. | Reduce cost inefficiencies, making East region profitable. |
| **Tech Returns Management** | Stricter quality checks and better post-sales support. | Minimize return rates, enhancing overall profitability. |
| **Peak Profit Periods (May & June)** | Amplify marketing & promotions during these months. | Capitalize on historically high revenue and profit trends. |

---

##  Conclusion  

This project provides a **comprehensive data-driven analysis of Superstore Sales**, covering **Overall Performance, Product Market Trends, and Regional Performance**. By implementing the recommended business actions, Superstore can **increase profitability, optimize logistics, and improve pricing strategies**.  

---
This repository includes:  
📂 **Excel Dashboard File (Power Query & Power Pivot)**  
📂 **Raw Dataset for Further Analysis**  




