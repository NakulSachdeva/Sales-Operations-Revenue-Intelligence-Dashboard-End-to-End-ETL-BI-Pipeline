# 📈 Sales Operations & Revenue Intelligence Hub
> **Project Scope:** Transforming a fragmented **$13.44M** dataset into an Executive-Grade BI Pipeline.

I couldn't just build charts on top of that—the numbers would have been wrong.

## ⚙️ Phase 1: High-Integrity ETL & Data Hygiene
Before any visualization could happen, I engineered a robust **ETL (Extract, Transform, Load)** pipeline using **Power Query** to sanitize a fragmented dataset of 1,184+ records. 

### 🛠️ The Technical Deep-Clean:
To ensure the **$13.44M** revenue figure was bulletproof, I executed the following transformations:

* **Attribute Standardization:** Used `Text.Proper` and `Conditional Columns` to resolve naming conflicts (e.g., merging "TX", "Tex", and "Texas" into a single "Texas" attribute) for accurate regional grouping.
* **Data Type Enforcement:** Audited and corrected mixed-type errors in the "Revenue" and "Date" columns, preventing calculation breaks in the backend Pivot models.
* **Deduplication & Null Handling:** Identified and removed 12+ "ghost" records and handled null values in the Lead Source column to prevent skewed ROI metrics.
* **Schema Optimization:** Transformed a wide, flat table into a clean, analysis-ready schema by removing redundant metadata and enforcing strict column headers.
  
Before & After: Data Transformation
| Raw Unstructured Input | Cleaned & Standardized Output |
|---|---|
| ![Raw Data Sample](Raw%20Data%20-%20Sample.png) | ![Cleaned Sample](Post%20Cleaning%20&%20Transformation%20Sample.png) |

## 🧩 Phase 2: Architecting the Analytical Engine
With a clean dataset, I built a relational backend using multiple **Pivot Table Models**. The goal wasn't just a static report, but a **Dynamic Decision Tool** that allows leadership to stress-test the **$13.44M** pipeline from three critical angles.

### 👥 Problem 1: Sales Team Efficiency & Performance Audit
**The Analysis:** A granular audit of individual performance across the sales force to identify high-performers vs. coaching opportunities.
* **The Solution:** This pivot tracks the "Middle of the Funnel." It identifies which reps are successfully converting high-value deals versus those stalled in the "Discovery" phase. This allows management to move away from generic meetings and toward targeted data decisions.
  
![Sales Team Audit](Sales%20Team%20Performance%20Audit.png)

### 🔍 Problem 2: Identifying "Waste" in Marketing Spend
**The Analysis:** An audit of **Lead Quality** to ensure every dollar of the $13.44M pipeline is being spent on the right channels.
* **The Solution:** By calculating the conversion rate per vendor, I identified that while **VoltEdge** provided the highest volume (43%), **SunLead Pro** delivered an 18% higher ROI per lead. This insight provides the evidence needed for strategic budget reallocation.
  
![Marketing ROI Analysis](Marketing%20ROI.png)

### 🌍 Problem 3: Regional Market Saturation & Expansion
**The Analysis:** A high-level view of **Market Penetration** across the US to find untapped growth.
* **The Solution:** This view isolates revenue by State and Region. It revealed that the **Midwest** was hitting a 52% conversion rate—significantly outperforming the national average—signaling a prime geographical area for team expansion and increased marketing spend.
  
![Regional Market Insights](Regional%20Market%20Penetration.png)

> **The Connector:** All three engines are tied to a **Global Slicer Panel**. A single click on a "Region" or "Manager" slicer updates all three views simultaneously, providing an instant, 360-degree audit of any business segment.

## 📊 Phase 3: The Executive BI Interface
The final layer of the project is a high-fidelity **Executive Dashboard** designed for C-Suite decision-making. By applying a "No-Grid" UI/UX approach, I transformed a standard spreadsheet into a functional business application that provides a **$13.44M** bird’s-eye view.

### 🖼️ The Final Control Center
![Executive Dashboard](Executive%20Dashboard.png)

### 📈 Strategic Revenue Insights
I synthesized the entire $13.44M pipeline into a final audit of **Conversion Strategy** and **Growth Benchmarks**.

* **The High-Level Audit:** Confirmed a total revenue of **$13.44M** with a healthy **48%** conversion rate across all channels.
* **Lead Quality Variance:** Discovered that despite **VoltEdge** contributing 43.1% of lead volume, they lagged behind **SunLead Pro** in ROI per lead—proving that volume doesn't always equal value.
* **Geographical Dominance:** Identified the **Midwest** as the top-performing region, consistently hitting a **52%** conversion rate, making it the primary target for further marketing spend.

![Final Project Insights](Final%20Insights.png)

> **The Technical Polish:** I implemented custom number formatting (`$#,,.00"M"`) for clarity, zero-border charting for a modern UI, and dynamic KPI cards that update instantly when sliced by Representative or Region.

The Big Number: A crystal clear $13.44M total revenue KPI.

Conversion Truths: Discovered we have a rock-solid 48% conversion rate, but some "high volume" vendors were actually underperforming on quality.

Custom UI: Used custom formatting ($0.00"M") so the C-suite doesn't have to squint at long strings of zeros.

### 📁 How to Use This
1. **[Download the Master Analysis File (.xlsx)](Analysis%20-%20(Cleaned%20File,%20Analysis%20&%20Dashboard).xlsx)**
2. Open the file and navigate to the **Executive Dashboard** tab.
3. Use the integrated **Slicers** to filter by Region, Lead Vendor, or Sales Representative.

## 🛠 Skills & Tools Applied
* **Data Visualization:** KPI Card Design, Dynamic Slicers, Custom Number Formatting, UI/UX for Executive Reporting.
* **ETL & Data Cleaning:** Power Query, Data Validation, Error Identification, Standardizing Categorical Data.
* **Business Intelligence:** Pivot Table Logic, Multi-Dimensional Filtering, ROI Analysis, Lead Conversion Tracking.
* **Domain Knowledge:** Sales Operations, Revenue Intelligence, CRM Data Audit.

---

## 🤝 Let's Connect
If you have questions about the logic behind this $13.44M audit or want to discuss Data Analyst opportunities, feel free to reach out!

* **LinkedIn:** [Nakul Sachdeva](https://www.linkedin.com/in/nakulsachdeva0/)
* **Portfolio:** [Check out my other projects](https://github.com/NakulSachdeva)
* **Email:** [nakulsachdeva.careers@gmail.com]
