# Permitting Service Data Analysis – Environment Agency (2025)

This project analyzes permit application data from the Environment Agency’s Centralised Services Team to evaluate performance, identify bottlenecks, and suggest improvements using both Python (Google Colab) and Power BI dashboards.

## 📌 Objective

To evaluate the **Permitting Service’s performance** over three financial years by addressing key questions related to application types, refusal rates, processing timelines, and request patterns for additional information.

## 🛠️ Tools Used

| Tool           | Purpose                            |
|----------------|------------------------------------|
| Python (Colab) | Data cleaning, EDA, feature engineering |
| Power BI       | Interactive dashboard & insights   |
| Pandas, Matplotlib | Data handling & visualization in Python |
| DAX            | Calculated measures in Power BI    |

## 📊 Key Insights

1. **Most common application type:** New Permit  
2. **Highest refusal rate in 2022/23:** 28% in Sector 10  
3. **Avg. Determination Time by Complexity (Cat1 → Cat5):** 24 to 587 days  
4. **Additional Info Requests:** Fluctuated year-to-year  
5. **Additional patterns explored:**  
   - Link between complexity and refusal rate  
   - Impact of pre-application support  
   - Sector-specific delays  

## 📈 Power BI Dashboard

Interactive dashboard includes:
- **Application Type Trends**
- **Average Determination Time by Category**
- **Refused Rates by Sector**
- **Additional Info Request Trends**

> 📁 Located in: `dashboards/powerbi-summary.pdf`

## 📂 Repository Structure

```text
notebooks/          - Google Colab notebook for EDA and calculations
dashboards/         - Exported Power BI visuals/report
presentation/       - Final presentation slides
report/             - Task brief and written submission
data/               - (Redacted) Input data structure description
