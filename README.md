# Phantom Logistics & Supply Chain BI Dashboard (Power BI)

## 📌 Executive Summary
An interactive **4-Page Business Intelligence Dashboard** engineered in **Microsoft Power BI** for **Phantom Logistics**.

Completing my end-to-end MIS and Data Analytics portfolio alongside my **PostgreSQL** and **Advanced Excel MIS** projects, this report transforms raw supply chain and delivery records into an executive decision-support system featuring custom DAX measures, Star Schema data modeling, and seamless page-navigation UI.

---

## 📊 4-Page Dashboard Walkthrough

### 1. Executive Overview
*Tracks high-level KPIs, total shipment volume, overall revenue, and month-over-month operational trends.*

<img width="1342" height="783" alt="image" src="https://github.com/user-attachments/assets/2f99bc6a-d169-48aa-a3e8-aad81ce0ff36" />


---

### 2. Delivery & SLA Performance
*Monitors On-Time Delivery (OTD) rates, average transit lead times, and delayed shipment bottlenecks.*

<img width="1340" height="773" alt="image" src="https://github.com/user-attachments/assets/f40d0336-7699-4833-99c6-d6099ffeaf3e" />


---

### 3. Regional & Route Insights
*Breaks down shipping volume, hub performance, and demand distribution across key geographic regions.*

<img width="1351" height="782" alt="image" src="https://github.com/user-attachments/assets/d8dadb38-2283-4990-bdc1-fec557db108d" />


### 4. Operational Cost & Fleet Efficiency
*Evaluates freight expenses, cost-per-shipment ratios, and carrier efficiency across delivery modes.*

<img width="1342" height="783" alt="image" src="https://github.com/user-attachments/assets/2ec0cdb6-4025-44a5-aba3-522d5fc0edfb" />


---

## 🛠️ Technical Architecture & Skills Demonstrated
* **Power Query (ETL & Data Shaping):** Cleaned raw logistics data, handled null delivery timestamps, standardized regional strings, and created custom conditional columns.
* **Data Modeling (Star Schema):** Built clean one-to-many relationships between central Fact tables and Dimension tables (Date, Region/Route, Carrier/Mode) for fast filter propagation.
* **DAX Calculations:** Engineered custom measures for Total Shipments, On-Time Delivery (OTD) %, Average Transit Lead Time, Freight Cost per Order, and Month-over-Month (MoM) variance.
* **UI/UX Design & Navigation:** Designed a cohesive white-and-blue corporate layout featuring rounded KPI summary cards, interactive cross-filtering slicers, and top button navigation across all 4 report pages.

---

## 🎯 Key Business & Operational Insights
* **SLA & Delivery Tracking:** Isolated on-time vs. delayed deliveries across routes to pinpoint bottleneck hubs and improve overall On-Time Delivery (OTD) performance.
* **Regional Demand Distribution:** Identified high-volume shipping corridors and seasonal demand spikes to guide fleet allocation.
* **Cost & Carrier Optimization:** Benchmarked freight expenses across delivery modes and weight brackets to highlight cost-saving opportunities.

---

## 📂 Repository Contents
* `Phantom_Logistics_Dashboard.pbix` — Complete 4-page interactive Power BI Desktop report file.
* `page1_overview.png`, `page2_delivery.png`, `page3_regional.png`, `page4_cost.png` — Visual previews of all 4 dashboard pages.
