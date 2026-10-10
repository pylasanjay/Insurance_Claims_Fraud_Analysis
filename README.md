
# 📊 Insurance Claims & Fraud Risk Analysis Dashboard

## 📌 Project Overview

The **Insurance Claims & Fraud Risk Analysis Dashboard** is an interactive business intelligence project developed using Microsoft Power BI. The primary objective of this project is to analyze insurance claim data, identify potential fraud patterns, and understand claim trends across different categories.

The dashboard transforms raw insurance data into meaningful insights through interactive visualizations, key performance indicators (KPIs), and comparative analysis.

This project demonstrates practical skills in data visualization, business intelligence, data analysis, and dashboard development.

## 🎯 Business Problem

Insurance companies process large numbers of claims every day. Analyzing these claims manually can make it difficult to identify unusual patterns, understand claim distributions, and prioritize claims that may require further investigation.

This project addresses these challenges by presenting claim information and fraud risk indicators in a centralized dashboard.

The report helps users explore:
- Overall insurance claim performance.
- Fraudulent versus non-fraudulent claims.
- Claim amounts across different categories.
- Regional differences in claims.
- Fraud risk score patterns across customer groups.
- Premium amounts across claim types and regions.

**Note:** Fraud risk scores are indicators for analysis and should not be treated as proof of fraud.

## 🎯 Project Objectives

- Analyze total insurance claims and claim amounts.
- Compare fraudulent and non-fraudulent claims.
- Understand claim distribution by claim type and status.
- Analyze claim patterns across geographical regions.
- Explore fraud risk scores across claim types, regions, and gender.
- Compare average claim amounts and premium amounts.
- Present important metrics through an interactive Power BI report.
- Support data-driven analysis and reporting.

## 🖼️ Dashboard Preview

### 1. Executive Dashboard

This dashboard provides a high-level overview of insurance claims, including key metrics and visual comparisons.

**Key insights explored:**
- Total number of claims.
- Number of fraud claims.
- Total claim amount.
- Fraud versus non-fraud claims.
- Claims by claim type.
- Claim amount by claim type.
- Claims by claim status.
- Fraud claims by claim type.
- Claims by region.
- Average claim amount by region.

![Executive Dashboard](screenshots/executive-dashboard.png)

*Figure 1: Executive Dashboard — Insurance Claims Overview*

### 2. Risk Analysis Dashboard

The Risk Analysis Dashboard focuses on fraud risk indicators, claim amounts, and premium trends across different categories.

**Key insights explored:**
- Average fraud risk score by claim type.
- Average fraud risk score by region.
- Average fraud risk score by gender.
- Fraud risk score distribution.
- Average claim amount by claim status.
- Average claim amount by region.
- Average premium amount by claim type.
- Average premium amount by region.
- Average premium amount by gender.

![Risk Analysis Dashboard](screenshots/risk-analysis-dashboard.png)

*Figure 2: Risk Analysis Dashboard — Fraud Risk and Premium Analysis*

## 📈 Key Performance Indicators (KPIs)

The report includes key metrics that help summarize insurance claim activity.

| KPI | Purpose |
|---|---|
| Total Claims | Measures the overall volume of claims |
| Fraud Claims | Shows the number of claims categorized as fraudulent |
| Total Claim Amount | Represents the total claim value |
| Average Claim Amount | Helps compare typical claim values |
| Average Fraud Risk Score | Summarizes the fraud risk score |
| Average Premium Amount | Helps compare premium amounts |

*Note: KPI definitions and calculations depend on the measures implemented in the Power BI report.*

## 🔍 Analysis Performed

### Claim Analysis
Examines claim volumes, claim amounts, claim types, and claim statuses to understand the overall distribution of insurance claims.

### Fraud Analysis
Compares fraud and non-fraud claims and explores how fraud-related indicators vary across claim categories.

### Regional Analysis
Compares claim volumes, claim amounts, and fraud risk scores across different regions.

### Customer Category Analysis
Explores differences in average fraud risk scores and premium amounts across gender categories.

### Risk Score Analysis
Examines the distribution and average values of fraud risk scores to identify patterns that may warrant further investigation.

## 🛠️ Tools and Technologies

- **Microsoft Power BI Desktop:** Dashboard creation and interactive reporting.
- **Power Query:** Data cleaning and transformation, where implemented.
- **DAX:** Calculated measures and KPIs, where implemented.
- **Data Visualization:** KPI cards, charts, and comparative visuals.
- **GitHub:** Project versioning and portfolio presentation.

## ⚙️ Project Workflow

1. **Data Understanding:** Review the insurance claims dataset and identify relevant fields.
2. **Data Preparation:** Check data quality and prepare fields for analysis.
3. **Data Modeling:** Organize the data and relationships, where required.
4. **KPI Development:** Create or configure measures for claims, amounts, and risk scores.
5. **Dashboard Development:** Build the Executive and Risk Analysis report pages.
6. **Visual Analysis:** Compare metrics across claim types, regions, statuses, and customer categories.
7. **Documentation:** Publish the project overview and dashboard screenshots on GitHub.

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open `Project_Dashboards.pbix`.
4. Configure the data source if Power BI requests it.
5. Refresh the data if the source is available and refresh is required.
6. Navigate between the report pages.
7. Use the available filters and visual interactions to explore the report.

## 📂 Repository Structure

```text
Insurance-Claims-Fraud-Analysis/
│
├── README.md
├── Project_Dashboards.pbix
│
└── screenshots/
    ├── executive-dashboard.png
    └── risk-analysis-dashboard.png
```

## 💡 Skills Demonstrated

- Power BI dashboard development.
- Data visualization and reporting.
- KPI analysis.
- Insurance claims analysis.
- Fraud risk indicator analysis.
- Regional and category-based comparisons.
- Business intelligence storytelling.
- Technical documentation using Markdown.
- GitHub project publishing.

## 🔮 Future Enhancements

- Add monthly and yearly claim trend analysis, if date fields are available.
- Include additional claim investigation indicators.
- Add drill-through pages for detailed claim analysis.
- Document the DAX measures and data model.
- Improve report navigation and filtering.
- Add data refresh automation, where supported.
- Include a data dictionary and detailed methodology.

## ⚠️ Limitations

- The accuracy of the analysis depends on the quality and completeness of the underlying dataset.
- Risk scores do not independently establish whether a claim is fraudulent.
- Results should be validated against the actual dataset and business definitions.
- Data source availability may affect report refresh functionality.

## 👨‍💻 Author

**Sanjay**

Aspiring Data Analyst | Power BI | SQL | Excel

This project demonstrates practical application of business intelligence concepts through an interactive insurance claims analysis dashboard.

## ⭐ Conclusion

The Insurance Claims & Fraud Risk Analysis Dashboard demonstrates how Power BI can convert insurance data into an interactive reporting solution. By combining claim metrics, regional comparisons, and fraud risk indicators, the report makes it easier to explore patterns and support further investigation.

---

If you find this project useful, feel free to explore the report and star the repository!
