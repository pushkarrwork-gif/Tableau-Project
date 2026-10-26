# 🧱 LEGO Sets & Pricing Analysis



## 📌 Project Overview
The **LEGO Sets & Pricing Analysis** project is a comprehensive visual exploration of historical LEGO set data spanning several decades. Using **Tableau**, this dashboard analyzes product pricing strategies, theme popularity, demographic targeting (age ranges), and piece-to-price ratios. 

This analysis provides valuable insights into LEGO's product catalog evolution, revealing how they balance their portfolio between traditional children's toys and the highly lucrative adult collector market.

## 📊 Dataset Description
The dataset (`Lego_10000_Sets_Data.xlsx`) contains information on nearly 10,000 LEGO sets. 
**Key attributes include:**
*   **Identifiers:** Set ID, Name
*   **Categorization:** Theme, Subtheme, Theme Group, Category
*   **Metrics:** Pieces, Minifigures (Minifigs), Minimum Age Range (`agerange_min`)
*   **Financials:** US Retail Price (`Us_retailPrice`)

## 📈 Key Performance Indicators (KPIs)
At a glance, the dashboard reveals the following macroeconomic metrics for the analyzed dataset:
*   **Total Sets Analyzed:** 9,502
*   **Average Minifigs per Set:** 2
*   **Average Pieces per Set:** 564
*   **Average Price per Piece:** $0.11
*   **Average Retail Price:** $61.00

## 🛠️ Dashboard Components
The Tableau dashboard is highly interactive, featuring top-level filters for **Theme, Minifigs, and Themegroup**. It comprises the following visualizations:

1.  **Sets Over Time (Line Chart):** Tracks the volume of LEGO sets released year over year (1998–2026), highlighting production trends and seasonal peaks.
2.  **Theme Group Popularity (Donut Chart):** Breaks down the overarching theme groups, showcasing the dominant market shares.
3.  **Audience Distribution (Bar Chart):** Analyzes the target minimum age for sets, revealing product density across different age demographics.
4.  **Minifigs by Age (Bar Chart):** Displays the average number of minifigures included in sets tailored for specific age groups.
5.  **Subtheme Pricing (Horizontal Bar Chart):** Compares the average retail price of top subthemes (e.g., Landmarks, Skylines, Construction).
6.  **Pieces per Theme (Word Cloud):** Visually weighs the most piece-heavy themes like Technic, Architecture, and Icons.

<img width="1593" height="856" alt="image" src="https://github.com/user-attachments/assets/535c1f0f-67e8-4a85-9b9f-9e93d0657319" />

## 💡 Key Business Insights
As a Data Analyst, diving into this dashboard reveals several strategic takeaways:
*   **The Power of Licensing:** "Licensed" themes are the undisputed driver of the catalog, making up **35.09%** of all sets. Action/Adventure follows at 25.33%. 
*   **The Adult Collector Boom:** While there is a massive cluster of products aimed at ages 5-8 (totaling over 4,500 sets), the single largest age demographic peak is the **18+ category (2,452 sets)**. LEGO's "Adults Welcome" strategy is a massive portion of their modern business.
*   **Premium Pricing for Display Models:** The most expensive subthemes on average are **Landmarks ($167.99)** and **Skylines ($147.13)**. These align perfectly with the Architecture and Icons themes, which are piece-heavy and targeted squarely at adults with disposable income.
*   **The Golden Ratio:** The average price per piece sits steadily at **$0.11**, serving as an excellent benchmark for consumers to determine if a new set is a "good deal" relative to historical averages.

## 🚀 How to Use This Dashboard
1. Download the Tableau Workbook (`.twb` or `.twbx` file) from this repository.
2. Open the file using **Tableau Desktop** or **Tableau Reader**.
3. Use the dropdown filters at the top right (`Theme`, `Minifigs`, `Themegroup`) to slice the data.
4. Hover over data points on the line charts and bar charts to view specific tooltips containing granular data (like exact Set Names or specific pricing).

## 👨‍💻 Author
**Pushkar Patil**
*   Data Analyst
*   [[LinkedIn](https://www.linkedin.com/in/pushkar-patil-a71477313/)]
