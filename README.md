# Miami Retail Shops: Weather, Sales, and Customer Demographics Analysis

## 📌 Project Overview
This project delivers an end-to-end data analytics solution for the **Miami Retail Shops** network, evaluating performance across four major Florida locations (Miami, Orlando, Tampa, and Jacksonville). Daily sales across these shops are heavily influenced by local weather patterns and changing customer demographics. By building a relational database in MySQL and designing an interactive Power BI dashboard, this project uncovers the true drivers of customer demand to optimize business planning, staffing, and marketing promotions.

---

## 🛠️ Tech Stack & Tools
* **Database & Data Transformation:** MySQL
* **Data Visualization & Modelling:** Power BI
* **Key Concepts Applied:** Relational Database Design, Data Aggregation, Time-Series Analysis, Demographic Segmentation, Correlation Analysis.

---

## 💡 Business Case Analysis (STAR Framework)

### 1. Situation (The Context)
Management at **Miami Retail Shops** noticed unpredictable daily sales fluctuations across their Florida branches. While they suspected that external factors like weather and customer profiles played a role, leadership lacked data-driven clarity on why certain days or locations outperformed others, leading to inefficiencies in inventory and staffing management.

### 2. Task (The Goal)
My objective was to act as a Data/Business Analyst to build a unified relational database combining daily sales logs, local weather tracking (temperature/rainfall), and customer survey data, and then design the "Miami Retail Shops" dashboard to analyze correlations and provide data-driven operational insights.

### 3. Action (Our Approach)
* **Step 1: Build Database & Clean Data** – Gathered and cleaned daily transactional sales, weather metrics, and survey data using MySQL.
* **Step 2: Develop SQL** – Wrote optimized SQL queries using `INNER JOIN` to merge datasets on date and location for a unified, flat-table analysis.
* **Step 3: Analyze Data** – Explored descriptive statistics to detect key business correlations (e.g., Temperature vs. Sales, Rainfall Effects, and Weekend Lift).
* **Step 4: Create Power BI Dashboard** – Imported the processed SQL views into Power BI, established robust relationships, and designed an interactive dashboard for stakeholders.

---

## 📊 Dashboard Questions & Analytical Visuals

#### ❓ Q1: How strongly do temperature and rainfall affect daily sales?
* **Visual Used:** Scatter Plot (Sales vs Temperature) and Dual-Axis Line Chart (Sales & Rainfall trend over time).
* **Insight:** Discovered a positive correlation between optimal warm temperatures and sales volume, while heavy rainfall caused a significant drop in foot traffic, particularly in outdoor-accessible shop layouts.

#### ❓ Q2: Which shop performs best, and why?
* **Visual Used:** Bar Chart (Total Revenue by Shop Location) stacked with product categories.
* **Insight:** The **Miami** and **Orlando** locations outperformed other branches due to higher tourist volumes and a stronger alignment between hot weather and seasonal product availability.

#### ❓ Q3: Who are our customers (Families vs Singles, Male vs Female) and how does this change over time?
* **Visual Used:** 100% Stacked Bar Chart & Donut Charts paired with a Time Slicer (`Year`/`Quarter`).
* **Insight:** Weekends are heavily dominated by **Families**, whereas weekdays see a higher volume of **Single** shoppers. Demographics shift dynamically during major holiday quarters.

#### ❓ Q4: Are there predictable seasonal patterns in sales?
* **Visual Used:** Line Chart (Monthly Sales Trend YoY) with weekend vs weekday shading.
* **Insight:** Clear seasonal spikes occur during late spring and summer months, with a predictable and consistent **"Weekend Lift"** across the entire retail network.

---

## 🚀 Data-Driven Recommendations (What Actions to Take)

1. **Optimized Staffing & Scheduling:** Increase frontline staff during high-probability weekend shifts and warm, clear days based on local weather forecasts to capture maximum customer demand.
2. **Dynamic Inventory Management:** Stock up on family-oriented bundles and high-margin seasonal items right before the weekend rush and peak summer quarters.
3. **Weather-Triggered Promotions:** Implement automated marketing campaigns (e.g., flash discounts on indoor products or digital vouchers) on heavy rainfall days to mitigate the drop in brick-and-mortar foot traffic.

---

## 📸 Dashboard Preview & Interaction
> 💡 *Below is the visual showcase of the interactive "Miami Retail Shops" Dashboard.*
**Coming Soon!**
