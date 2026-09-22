# 📊 Project Management Analytics Dashboard

An interactive **Power BI** analytics dashboard designed to monitor end-to-end performance, completion rates, financial impact metrics, and project risk distributions across multiple regions and management tiers.

---

## 📸 Dashboard Preview

![Dashboard Preview](docs/dashboard_preview.png)[cite: 1]

---

## 🎯 Business Problem & Context

Managing portfolio performance across geographically dispersed projects often leads to delayed risk detection, misaligned financial metrics, and siloed department reporting[cite: 1].

This project provides an executive decision-support tool to:
- Monitor **99 active and historical projects** spanning 4 regional sectors (East, South, North, West)[cite: 1].
- Provide self-service exploration across departments, project phases, and risk levels[cite: 1].
- Enable rapid identification of underperforming or on-hold initiatives for corrective risk planning[cite: 1].

---

## 📈 Key Metrics & Financial Impact

The dashboard aggregates over **$870M+ in cumulative financial impact** across key financial drivers[cite: 1]:

- **Income Generation:** $237.93M[cite: 1]
- **Process Improvement:** $222.23M[cite: 1]
- **Cost Reduction:** $194.57M[cite: 1]
- **Working Capital:** $219.25M[cite: 1]

---

## ✨ Key Features & Insights

1. **Executive KPI Scorecards:** Top-level metrics tracking overall portfolio impact and total volume (99 projects)[cite: 1].
2. **Decomposition Tree Analysis:** Breakdown of project completion rates by Department (Admin & BI, Supply Chain, Warehouse) and Phase (Explore, Implement, Measure)[cite: 1].
3. **Manager Workload Distribution:** Visual breakdown of project allocation across managers (e.g., Aleena Khan, Brenda Chandler, Kamari Norris)[cite: 1].
4. **Complexity & Risk Profiling:** Categorization by project complexity (High: 40, Low: 30, Medium: 29) alongside ongoing (80%) vs. on-hold (84%) monitoring rates[cite: 1].
5. **Benefit vs. Cost Trends:** Monthly financial breakdown evaluating return on investment across the timeline[cite: 1].
6. **Multi-Attribute Slicers:** Filtering by year (2018, 2020, 2021), Region (East, South, North, West), and Status (Cancelled, In-Progress, Completed, On-Hold)[cite: 1].

---

## 🛠️ Tools & Technologies Used

- **Business Intelligence Tool:** Microsoft Power BI Desktop[cite: 1]
- **Data Transformation:** Power Query / DAX[cite: 1]
- **Data Source:** Microsoft Excel / Data Modeling[cite: 1]

---

## 📁 Repository Structure

```text
├── docs/
│   └── dashboard_preview.png       # Screenshot of the dashboard layout
├── data/
│   └── project_management_data.xlsx # Source dataset used for modeling
├── pbix/
│   └── Project_Management_Dashboard.pbix # Power BI file
└── README.md                       # Project overview documentation
