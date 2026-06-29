# Florida Retail Analytics: Weather, Sales, and Customer Demographics

## 📌 Project Overview
This project delivers an end-to-end data analytics solution analyzing four retail shops in Florida (Miami, Orlando, Tampa, and Jacksonville). Daily sales in these regions fluctuate significantly based on weather patterns and changing customer demographics. By building a relational database in MySQL and designing an interactive Power BI dashboard, this project uncovers the true drivers of customer demand to optimize business planning, staffing, and marketing promotions.

---

## 🛠️ Tech Stack & Tools
* **Database & Data Transformation:** MySQL
* **Data Visualization & Modelling:** Power BI
* **Key Concepts Applied:** Relational Database Design, Data Aggregation, Time-Series Analysis, Demographic Segmentation, Correlation Analysis.

---

## 💡 Business Case Analysis (STAR Framework)

### 1. Situation (The Context)
Management at four Florida retail shops noticed unpredictable daily sales fluctuations. While they suspected weather and demographics played a role, leadership lacked data-driven clarity on why certain days outperformed others, making inventory, staffing, and promotional planning highly inefficient.

### 2. Task (The Goal)
My objective was to act as a Business/Data Analyst to build a unified database combining daily sales, local weather tracking, and customer survey data, and then build a dashboard to analyze correlations and provide actionable recommendations.

### 3. Action (Our Approach)
* **Step 1: Build Database & Clean Data** – Imported and cleaned daily sales logs, weather metrics (temperature, rainfall), and customer survey datasets in MySQL.
* **Step 2: Develop SQL** – Wrote advanced SQL queries utilizing `JOINS` to merge the sales and weather tables by date and location for a unified view.
* **Step 3: Analyze Data & Modelling** – Explored descriptive statistics to find correlations (e.g., Temperature vs. Sales, Weekend Lifts).
* **Step 4: Create Power BI Dashboard** – Imported the SQL views into Power BI, established relationships, and created dynamic visual reports for stakeholders.

### 4. Result & Insights (Dashboard Questions & Actionable Solutions)

#### ❓ Q1: How strongly do temperature and rainfall affect daily sales?
* **Visual Used:** Scatter Plot (Sales vs Temperature) and Dual-Axis Line Chart (Sales & Rainfall trend over time).
* **Insight:** Discovered a positive correlation between optimal temperatures and sales volume, while heavy rainfall caused a significant drop in foot traffic, particularly in outdoor-accessible shops.

#### ❓ Q2: Which shop performs best, and why?
* **Visual Used:** Bar Chart (Total Revenue by Shop Location) stacked with product categories.
* **Insight:** **Miami/Orlando** outperformed other branches due to high tourist volumes and a stronger alignment between hot weather and seasonal product availability.

#### ❓ Q3: Who are our customers (Families vs Singles, Male vs Female) and how does this change over time?
* **Visual Used:** 100% Stacked Bar Chart & Donut Charts with a Time Slicer (`Year`/`Quarter`).
* **Insight:** Weekends are heavily dominated by **Families**, whereas weekdays see a higher volume of **Single** shoppers. Demographics shift dynamically during major holiday quarters.

#### ❓ Q4: Are there predictable seasonal patterns in sales?
* **Visual Used:** Line Chart (Monthly Sales Trend YoY) with weekend vs weekday shading.
* **Insight:** Clear seasonal spikes occur during late spring and summer months, with a predictable **"Weekend Lift"** across all four Florida locations.

---

## 🚀 Data-Driven Recommendations (What Actions to Take)

1. **Optimized Staffing & Scheduling:** Increase frontline staff during high-probability weekend shifts and warm, clear days based on local weather forecasts to capture maximum demand.
2. **Dynamic Inventory Management:** Stock up on family-oriented bundles and high-margin seasonal items before the weekend rush and peak summer quarters.
3. **Weather-Triggered Promotions:** Implement automated marketing campaigns (e.g., flash discounts on indoor products or digital vouchers) on heavy rainfall days to mitigate the drop in brick-and-mortar foot traffic.

---

## 📸 Dashboard Preview & Interaction
> 💡 *Below is the visual showcase of the interactive Florida Retail Dashboard.*
**Coming Soon!**
