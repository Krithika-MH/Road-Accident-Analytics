# Road Accident Analytics Dashboard

## 📌 Project Overview
Road safety remains a critical concern for public health and urban planning. This project focuses on transforming raw and complex accident data into a comprehensive **Power BI Analytics Dashboard** to identify high-risk factors and trends.

By analyzing variables such as accident severity, vehicle types, road conditions, and temporal patterns, the dashboard provides a **data-driven foundation for policymakers and city planners** to implement targeted safety interventions.

The system helps answer critical questions such as:
- Where accidents occur most frequently
- When accidents are most likely to happen
- Which road conditions and vehicle types contribute most to casualties

Ultimately, the goal is to support **evidence-based decision making to reduce road casualties and improve traffic safety.**

---

## 📊 Dashboard Preview
<p align="center">
  <img src="https://github.com/Krithika-MH/Road-Accident-Analytics/raw/main/Road%20accident%20dashboard.png" width="900" alt="Road Accident Analytics Dashboard">
</p>

---

## 🛠️ Key Features & Technical Details

### End-to-End Data Pipeline
Managed the complete lifecycle of the analytics workflow, starting from raw dataset ingestion, followed by data cleaning, transformation, modeling, and final visualization in Power BI.

### Advanced Data Cleaning
Used **Power Query** to handle multiple data quality issues such as:
- Correcting inconsistent category labels and spelling errors
- Standardizing fields like *Junction Control* and *Accident Severity*
- Grouping granular categories for better analytical clarity

### Robust Data Modeling
Developed a **custom Calendar Table using DAX** to enable advanced **Time Intelligence operations**, including:
- Year-to-Date (YTD) analysis
- Year-over-Year (YoY) comparisons
- Monthly and yearly trend analysis

### Interactive Visual Analytics
Designed an interactive dashboard with multiple analytical components including:
- **Geospatial accident map** with zoom and lasso selection
- **Monthly trend area charts** for casualty patterns
- **Dynamic Urban vs Rural toggle** for location-based segmentation
- Slicers for filtering by **year, road type, weather condition, and vehicle category**

---

## 💡 Key Insights

### Trend Analysis
The analysis revealed a **9.9% year-over-year decrease in total casualties**, with a particularly notable **46.7% reduction in fatal accidents**, indicating improvements in road safety measures over time.

### Infrastructure Vulnerability
**Single carriageway roads** were identified as the highest-risk road type, contributing to the largest share of accident casualties.

### Environmental vs Behavioral Factors
A significant number of accidents occurred during **daylight conditions and on dry roads**, suggesting that **driver behavior and perceived safety conditions may play a larger role than environmental hazards**.

---

## 📂 Repository Contents

**Road Accident Analytics.pbix**  
The main Power BI project file containing the complete data model, DAX measures, and interactive report.

**Summary Report.docx**  
A detailed documentation file explaining the methodology, data cleaning process, key DAX formulas, and analytical insights derived from the dashboard.

---

## 🚀 Getting Started

1. Clone this repository to your local machine.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. Use the interactive slicers to explore the dataset by:
   - Year
   - Road Type
   - Weather Conditions
   - Vehicle Categories etc

## Data Source:
[Public Road Safety Dataset](https://drive.google.com/file/d/1yTI0506e7lZglRl7fsG2_TL0fHcd-G6D/view)
