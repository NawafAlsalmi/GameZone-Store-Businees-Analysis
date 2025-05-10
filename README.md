# GameZone Sales & Shipping Dashboard

This project visualizes and analyzes GameZone's store order data using Power BI.

## 📁 Project Overview

1. **Data Preparation**
   - Raw data: 20,000+ rows from an Excel file containing customer orders, product details, dates, and shipping info.
   - Cleaning steps: Removed nulls, corrected dates, standardized regions.
   - Added metrics:
     - `Time to Ship (days)`
     - `Shipping Speed Category`
     - Grouped regions

2. **Power BI Dashboard**
   - Key KPIs: Total Sales, Total Orders, Avg. Time to Ship
   - Visuals:
     - Sales trends over time
     - Most ordered products
     - Shipping speed by region
     - Sales by marketing channel

## 📊 Dashboard Preview

![GameZone Dashboard](assets/GameZone_Dashboard.png)

## 🔧 Technologies Used
- Power BI
- Excel (for initial cleaning)

## 📁 Files
- `data/sample_cleaned_data.xlsx`: A sample of the cleaned dataset.
- `assets/GameZone_Dashboard.png`: Dashboard image.
- `powerbi/GameZone_Dashboard.pbix`: (Optional) Power BI file.

## 🚀 How to Use
1. Open the `.pbix` file in Power BI Desktop (if provided).
2. Load the cleaned data from `data/`.
3. Explore and interact with the visuals.

---

## 💡 Notes
- No sensitive data included in this repo.
- For larger datasets or automation, consider moving preprocessing to Power Query or Python.

