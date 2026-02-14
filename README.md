# 📊 Advanced Data Architecture & Business Intelligence System

![Data Modeling](https://img.shields.io/badge/Architecture-Dimensional%20Modeling-blue)
![Excel Engine](https://img.shields.io/badge/Engine-Advanced%20Formulas-green)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success)

## 📖 Executive Summary
This repository houses a sophisticated analytical ecosystem designed to bridge the gap between raw data collection and strategic decision-making. Unlike standard flat-file analysis, this project implements a **relational data structure** within a spreadsheet environment, utilizing a hybrid of external data and custom-engineered logic.

---

## 🏗️ Technical Architecture

The project follows a **Modular Design Pattern**, separating raw data storage from the analytical processing layer.



### 1️⃣ The Dimension Layer (`*_dim` Sheets)
While the core attributes (IDs, Names) were sourced externally, the **intelligence** of these sheets was engineered by me. 
* **Formula-Driven Enrichment:** I implemented custom-calculated columns to transform static attributes into dynamic data points.
* **Logic Applied:** Used complex logical nesting to handle data normalization and hierarchical grouping.
* **Purpose:** These sheets act as the "Source of Truth," ensuring referential integrity across the entire model.

### 2️⃣ The Analytical Engine (Built from Scratch)
Every non-dimension sheet was conceptualized, structured, and built from a blank canvas. 
* **Fact Table Orchestration:** Consolidation of transactional data.
* **Complex Aggregations:** Developed high-level metrics using array formulas and dynamic ranges.
* **UI/UX Design:** Engineered a user-centric interface with interactive slicers and conditional visual cues.

---

## 🛠️ Engineering Deep Dive

### Data Processing Pipeline
1.  **Ingestion:** External data is imported into the `_dim` layers.
2.  **Transformation:** My custom formulas sanitize and categorize the raw input.
3.  **Modeling:** Data is linked via primary keys to the central calculation sheets.
4.  **Visualization:** The "Dashboard" layer interprets the processed data into visual KPIs.

### Key Technical Skills Demonstrated:
| Feature | Implementation Detail |
| :--- | :--- |
| **Logic Engineering** | $IFS$, $SWITCH$, and $LAMBDA$ for automated categorization. |
| **Data Retrieval** | High-performance $INDEX/MATCH$ and $XLOOKUP$ structures. |
| **Optimization** | Minimizing volatile functions to ensure workbook speed. |
| **Visual BI** | Dynamic charting with named ranges and automated formatting. |

---

## 📊 Visual Highlights

> [!TIP]
> **Proportional Design:** The dashboard utilizes a "Data-Ink Ratio" philosophy, ensuring that every visual element provides maximum insight with minimum clutter.

* **Heatmaps:** Automated color-scaling to identify outliers in seconds.
* **Trend Analysis:** Moving averages and period-over-period growth calculations.
* **Drill-Downs:** Modular tables that allow users to see the "Why" behind the "What."

---

## 📈 Roadmap & Future Enhancements
- [x] Initial Data Architecture & Star Schema Setup.
- [x] Implementation of custom logic in Dimension sheets.
- [x] Full Dashboard Build-out.
- [ ] Integration with Power Query for automated API fetching.
- [ ] Transitioning the backend logic to SQL for enterprise-scale testing.

---

## 👤 Author
**[Your Name]**
*Data Architect & Spreadsheet Engineer*
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](your-link-here)
[![Portfolio](https://img.shields.io/badge/Portfolio-View%20Work-orange?style=flat&logo=buffer)](your-link-here)

---
*Note: This project is a demonstration of advanced data modeling capabilities, specifically focusing on the intersection of raw data enrichment and custom analytical framework building.*