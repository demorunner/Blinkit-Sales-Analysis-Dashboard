# Blinkit-Sales-Analysis-Dashboard

# Blinkit Sales Analysis Dashboard 📊

### Table of Contents

1.  [Project Overview](#project-overview)
2.  [Data Source](#data-source)
3.  [Key Metrics (KPIs)](#key-metrics-kpis)
4.  [Dashboard Visualizations](#dashboard-visualizations)
5.  [Dashboard Highlights](#dashboard-highlights)
6.  [Technical Details](#technical-details)
7.  [Future Enhancements](#future-enhancements)
8.  [Repository Contents](#repository-contents)
9.  [How to Use](#how-to-use)
10. [Author](#author)

---

### Project Overview 🚀

The primary objective of this project is to conduct a detailed analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution. The goal is to identify actionable insights and optimization opportunities by leveraging various Key Performance Indicators (KPIs) and data visualizations in Power BI.

### Data Source 📁

The analysis is based on the following dataset:

* `BlinkIT Grocery Data.xlsx`: This Excel file contains the raw data used to create the Power BI dashboard, including details on sales, items, outlets, and customer ratings.

### Key Metrics (KPIs) 📈

The following Key Performance Indicators (KPIs) were used to measure performance:

1.  **Total Sales:** The overall revenue generated from all items sold.
2.  **Average Sales:** The average revenue per sale.
3.  **Number of Items:** The total count of different items sold.
4.  **Average Rating:** The average customer rating for items sold.

### Dashboard Visualizations 🎨

The dashboard is composed of several interactive charts and visualizations, each designed to answer specific business questions. Below is a breakdown of the charts and their objectives. You should add a screenshot for each chart to visually represent the analysis.

* **Total Sales by Fat Content:** A Donut Chart is used to analyze the impact of fat content on total sales.
    **Screenshot:** Add a screenshot of the Donut Chart here.

* **Total Sales by Item Type:** A Bar Chart is used to identify the performance of different item types in terms of total sales.
    **Screenshot:** Add a screenshot of the Bar Chart here.

* **Fat Content by Outlet for Total Sales:** A Stacked Column Chart is used to compare total sales across different outlets, segmented by fat content.
    **Screenshot:** Add a screenshot of the Stacked Column Chart here.

* **Total Sales by Outlet Establishment:** A Line Chart is used to evaluate how the age or type of outlet establishment influences total sales.
    **Screenshot:** Add a screenshot of the Line Chart here.

* **Sales by Outlet Size:** A Donut/Pie Chart is used to analyze the correlation between outlet size and total sales.
    **Screenshot:** Add a screenshot of the Donut/Pie Chart here.

* **Sales by Outlet Location:** A Funnel Map is used to assess the geographic distribution of sales across different locations.
    **Screenshot:** Add a screenshot of the Funnel Map here.

* **All Metrics by Outlet Type:** A Matrix Card provides a comprehensive view of all key metrics (Total Sales, Average Sales, Number of Items, Average Rating) broken down by different outlet types.
    **Screenshot:** Add a screenshot of the Matrix Card here.

### Dashboard Highlights ✨

This section highlights the most important features and insights of the dashboard, giving a quick overview of its capabilities.

* **Key Performance Indicators (KPIs):** The top section of the dashboard prominently displays the main KPIs, including Total Sales, Average Sales, Number of Items, and Average Rating, giving a quick snapshot of the overall performance.
    **Screenshot:** Add a screenshot of the top section showing all the main KPI cards.

* **Filter Panel:** The interactive filter panel on the left allows users to dynamically explore the data by Outlet Location Type, Outlet Size, and Item Type.
    **Screenshot:** Add a screenshot of the filter panel on the left side of the dashboard.

### Technical Details ⚙️

The Power BI file `blinkit_analysis.pbix` leverages the following technical components:

* **Data Transformation:** Power Query was used to clean and shape the raw data for analysis.
* **Data Modeling:** The data is structured with a star schema to optimize performance and relationships between tables.
* **DAX Measures:** Several DAX (Data Analysis Expressions) measures were created to calculate key metrics such as Total Sales and Average Sales.

### Future Enhancements 💡

This project can be further enhanced with the following features:

* **Advanced Analytics:** Implement time-series forecasting to predict future sales trends.
* **What-If Analysis:** Add parameters to the dashboard to allow users to perform what-if analysis on key variables like pricing or promotions.
* **Customer Segmentation:** Analyze customer behavior to create different customer segments for targeted marketing strategies.
* **Sentiment Analysis:** Use text analytics on customer review data to gain deeper insights into customer satisfaction.

### Repository Contents 📦

This repository includes the following key files and folders:

* `blinkit_analysis.pbix`: The Power BI Desktop file containing the complete data model, transformations, and dashboard visualizations.
* `BlinkIT Grocery Data.xlsx`: The raw data file used as the source for the analysis.
* `screenshots/`: A directory where you should place all dashboard screenshots as mentioned above.

### How to Use 📖

1.  Clone this repository to your local machine.
2.  Ensure you have **Power BI Desktop** installed.
3.  Open the `blinkit_analysis.pbix` file using Power BI Desktop to view and interact with the dashboard.
4.  You can also inspect the data and data model within Power BI.

---

### Author 👨‍💻

* **Shantanu Chaturvedi**
