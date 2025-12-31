# coffee-sales-dashboard
This project is an end-to-end data analysis solution built entirely in **Excel** to track and analyze coffee sales performance. The goal was to transform raw transaction records into an interactive dashboard that helps stakeholders identify top-selling products, key customer segments, and regional trends.
## 🛠️ Tools & Technologies
* **Microsoft Excel:** Core tool for data cleaning, analysis, and visualization.
* **Advanced Formulas:** `XLOOKUP`, `INDEX & MATCH`, and `IF` statements for dynamic data retrieval.
* **Pivot Tables & Charts:** Used to summarize 1,000+ transaction rows into actionable metrics.
* **Slicers:** Added for interactive filtering by date, roast type, and loyalty status.

## 📊 Key Features & Insights
* **Dynamic Data Enrichment:** Merged data from three separate sheets (`Orders`, `Customers`, `Products`) into a single master dataset using `XLOOKUP` to bring in Customer Names, Email, Country, and Coffee Type.
* **Sales by Country:** Visualized sales distribution showing the **United States** as the leading market, followed by Ireland and the UK.
* **Top Customer Analysis:** Identified high-value clients (e.g., Allis Wilmore, Brenn Dundredge) to support loyalty retention strategies.
* **Product Performance:** Analyzed sales volume across different **Coffee Types** (Arabica, Robusta, Liberica, Excelsa) and **Roast Types** (Light, Medium, Dark).
* **Time Series Analysis:** Tracked monthly sales trends from 2019 to 2022 to identify seasonal peaks.

## 📂 Data Structure
The analysis is based on three main tables:
1.  [cite_start]**Orders Table:** Transactional data including `Order Date`, `Quantity`, and `Unit Price`[cite: 5].
2.  **Customers Table:** Demographics including `City`, `Country`, and `Loyalty Card` status.
3.  **Products Table:** Product details including `Coffee Type`, `Roast Type`, and `Size`.

## 📷 Dashboard Screenshot
<img width="1763" height="778" alt="Screenshot 2025-12-31 152539" src="https://github.com/user-attachments/assets/a085e49a-8e05-45c1-90bb-995de4673b3f" />
