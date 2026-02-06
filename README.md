# Optimizing IT Support Team Performance Using Analytics

## Project Overview
This project analyzes IT support ticket data to evaluate team performance, identify operational inefficiencies, and generate actionable insights.  
The analysis is performed using **Python (Pandas) in Jupyter Notebook within Visual Studio Code**, and the insights are visualized through an **interactive Power BI dashboard** to support data-driven decision-making in IT support operations.

---

## Problem Statement
IT support teams handle a high volume of tickets with varying priorities, issue types, and customer expectations.  
Due to limited analytical visibility, teams often face:
- Delayed ticket resolution
- Repeated or recurring issues
- Uneven workload distribution
- Declining customer satisfaction  

This project aims to use analytics to uncover these challenges and recommend improvements for optimizing IT support performance.

---

## Dataset Description
- **Source:** Synthetic IT Support Ticket Dataset (Kaggle)
- **Format:** CSV
- **Type:** Structured data
- **Records:** ~100,000 tickets

### Key Columns:
- `created_at` – Ticket creation timestamp  
- `customer_segment` – Type of customer  
- `channel` – Support channel used  
- `product_area` – Affected product/module  
- `issue_type` – Category of issue  
- `priority` – Ticket urgency  
- `status` – Ticket status  
- `resolution_time_hours` – Time taken to resolve ticket  
- `csat_score` – Customer satisfaction score  
- `region` – Geographic region  

---

## Data Cleaning & Preparation
Data cleaning was performed using **Pandas** in Jupyter Notebook (VS Code), including:
- Removal of unnecessary text-heavy columns
- Handling missing values using appropriate statistical methods
- Datetime parsing and feature extraction (year, month)
- Standardization of categorical values
- Outlier treatment for resolution time
- Feature engineering for Power BI–ready KPIs

The final dataset was optimized for dashboard performance and usability.

---

## Key Performance Indicators (KPIs)
The following KPIs were derived and analyzed:
- **Total Tickets**
- **Average Resolution Time (Hours)**
- **Customer Satisfaction Score (CSAT & CSAT %)**
- **High-Priority Ticket Volume**
- **SLA Breach Rate**
- **Ticket Distribution by Category and Region**

---

## Power BI Dashboard
An interactive **Power BI dashboard** was developed to visualize:
- Ticket distribution by priority, issue type, and channel
- Resolution time trends over time
- Region-wise and country-wise ticket analysis
- CSAT performance across categories
- Comparison of performance across regions
- Identification of recurring issues

The dashboard supports dynamic filtering using slicers for:
- Date
- Region
- Priority
- Customer segment

---

## Key Insights
- High-priority tickets tend to have longer resolution times.
- Certain issue categories recur frequently, indicating unresolved root causes.
- Customer satisfaction decreases as resolution time increases.
- Performance varies across regions, highlighting resource imbalance.
- Workload distribution across support categories is uneven.

---

## Recommendations
- Allocate additional resources to high-priority and high-volume issue categories.
- Address root causes of frequently recurring issues.
- Improve workload balancing across regions and channels.
- Track CSAT alongside operational KPIs to improve service quality.
- Use analytics-driven insights to proactively manage SLA compliance.

---

## Tools & Technologies

### Development Environment
- **Visual Studio Code**
- **Jupyter Notebook**

### Technologies
- **Python** – Data cleaning, preprocessing, analysis
- **Power BI** – Dashboard creation and visualization

### Python Libraries
- `pandas`

---
