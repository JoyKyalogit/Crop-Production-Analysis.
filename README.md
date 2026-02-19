# Crop Production & Financial Analysis (Kenya)

##  Project Overview
This project provides a data-driven look into the agricultural economy of Kenya. By analyzing yield, cost of production, and market prices, I developed an interactive **Power BI Dashboard** that identifies the most profitable crop varieties and high-performing counties.



---

## Key Business Insights
* **Revenue vs. Profit:** Despite high revenues in certain months, profit margins fluctuate significantly based on crop variety.
* **Geospatial Performance:** Nairobi and Mombasa lead in revenue, while agricultural hubs like Eldoret and Nakuru show the highest yield-to-cost efficiency.
* **Variety Optimization:** Organic crops demonstrate a higher profit-per-acre ratio compared to local and hybrid varieties in specific regions.

---

## Tech Stack
* **Visualization:** Power BI Desktop
* **Data Processing:** Power Query (M Language)
* **Analytics:** DAX (Data Analysis Expressions) for Calculated Measures
* **Data Source:** Cleaned Excel/CSV Agricultural Datasets

---

## 📊 Dashboard Preview
<img width="945" height="550" alt="image" src="https://github.com/user-attachments/assets/8c8a1be9-92cd-4ab2-b2fc-bd32ca683e3f" />

*Interactive dashboard featuring county filters, crop-type slicers, and geospatial revenue mapping.*

---

## Technical Implementation
1. **Data Cleaning:** Handled inconsistent county naming and imputed missing yield values using Python/Pandas prior to import.
2. **Data Modeling:** Established a Star Schema with a central Sales/Yield fact table and dimension tables for Geography and Crop Varieties.

