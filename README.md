# 🚗 Car Sales Analysis Dashboard | Power BI

## 📊 Project Overview

Interactive **Power BI dashboard** analyzing 12,000+ car sales records to uncover key business insights about automotive sales trends, customer preferences, and dealer performance.

**Live Dashboard Preview**: [Screenshots Below]

---

## 🎯 Business Questions Answered

- **When** do customers buy? → December peak ($100M+ revenue)
- **What** do customers prefer? → SUVs (26.9%) | Manual (52%)
- **Who** buys? → High-income drives Premium/Luxury segment
- **Which** brands lead? → Chevrolet, Ford, Dodge

---

## 📈 Key Insights

| Metric | Value |
|--------|-------|
| **Total Revenue** | $100M+ |
| **Peak Month** | December (2x average) |
| **Manual vs Auto** | 52% / 48% |
| **Top Brands** | Chevrolet, Ford, Dodge |
| **Best Selling Body** | SUVs (26.9%) |

---

Car-Sales-Analysis-Dashboard/
├── Car_Sales_Dashboard.pbix # Power BI file
├── README.md # This file
├── images/
│ ├── executive_summary.png # Dashboard preview
│ └── customer_analysis.png
├── DAX_Measures.md # All formulas documented
└── Insights_Summary.md # Business recommendations

## 📁 Repository Structure

---


---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI** | Dashboard & Visualization |
| **Power Query** | Data Cleaning |
| **DAX** | Measures & KPIs |
| **Excel** | Initial Exploration |

---

## 📐 Sample DAX Measures

```dax
Total Revenue = SUM(car_data[Price ($)])
Total Cars Sold = COUNTROWS(car_data)
MoM Growth % = DIVIDE([Total Revenue] - [Revenue Last Month], [Revenue Last Month]) * 100

----

##💡 Business Recommendations
Year-end campaigns – December sales spike proves holiday promotions work

Stock SUVs – Highest selling body style (26.9%)

Maintain manual inventory – Still 52% of market

Target high-income segments – Premium/Luxury customers drive revenue

🚀 How to Use
Download Car_Sales_Dashboard.pbix

Open with Power BI Desktop (free)

Explore interactive slicers (Company, Region, Month)

📫 Connect With Me
Email: safa.moeen4545@gmail.com

LinkedIn: linkedin.com/in/safa-moeen (Replace with your actual URL)

GitHub: github.com/safamoeen (Replace with your actual URL)

⭐ Why This Project?
Real-world business problem – Automotive sales analytics

End-to-end workflow – Data cleaning → DAX → Visualization → Insights

Professional documentation – Ready for recruiter review

Interactive dashboard – Slicers for dynamic exploration
