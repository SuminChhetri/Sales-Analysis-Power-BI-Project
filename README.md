# Sales Analysis Power BI Project

## Project Overview
This **Sales Analysis Dashboard** is built in Power BI to analyze product sales across different regions, customer demographics, and product categories. It tracks sales performance, targets, and profitability from 2020 to 2022 and is segmented by country, product category, and territory for detailed insights.

## Project Goals
- Analyze overall sales performance and identify trends across regions.
- Break down sales by product categories and identify high-margin products.
- Provide interactive, filterable visuals for strategic business insights.

## Dataset Information
This project uses three main datasets:

1. **Sales Data**: Includes fields like `OrderDate`, `Customer Key`, `Sales Territory Region`, `Order Quantity`, `Unit Price`, and `Freight`.
2. **Territory Rollup**: Lists sales territories by region and country.
   - Key countries: United States (Northwest, Northeast, Central, Southwest, Southeast), Canada, France, Germany, Australia, and the United Kingdom.
3. **Product Rollups**: Classifies products by `Product Subcategory` and `Product Category`.
   - Categories include: **PC-Accessories**, **PC-Bikes**, **PC-Clothing**, and **PC-Components**.

## Key Metrics and Visualizations

The Power BI report contains the following key visuals and metrics:

1. **Total Sales and Targets**:
   - Summarizes total sales against targets for a quick snapshot of overall performance.

2. **Sales Trends Over Time (2020-2022)**:
   - Line chart illustrating sales performance across the years to identify seasonal and annual trends.

3. **Sales by Region (Country Bar Graph)**:
   - Bar graph showing sales by country, with slicers for **year** and **continent** to allow regional comparisons.

4. **Margin % by Product Category**:
   - Bar chart of margin percentages by category, highlighting high-margin products.

5. **Interactive Tooltips**:
   - Custom tooltips on hover for specific products, countries, and time periods, enhancing user interactivity.

## Data Preparation and Modeling
- **Data Cleaning**: Ensured consistency and accuracy.
- **Data Grouping and Hierarchies**: Built hierarchies for `Territory` and `Product Categories` to enable drill-down capabilities.
- **Relationships and Modeling**: Connected `Sales Data` with `Territory Rollup` and `Product Rollups` tables for a comprehensive analysis.

## Usage Instructions
To explore the report:
1. Download the `.pbix` Power BI file from this repository.
2. Open it in Power BI Desktop.
3. Use **slicers** and **filters** to view specific years, regions, or product categories.

## Future Enhancements
- **Automated Updates**: Schedule data refreshes for up-to-date sales data.
- **Dashboard Publication**: Publish to Power BI Service for broader access.
- **Additional Filters**: Introduce filters for customer segments or sales channels for deeper insights.

## Technologies Used
- **Power BI**: Data visualization and report creation.
- **DAX**: For calculated measures and tooltips.
- **GitHub**: Project documentation and version control.

## Repository Structure
- `README.md`: Project overview, data sources, and usage instructions.
- `Sales_Analysis.pbix`: Power BI report file with all visuals and data models.
- `Data_Files/`: Folder for raw data files, if shared.
- `Images/`: Screenshots of main visuals for a project preview.

---
This project highlights interactive reporting skills and advanced Power BI features for actionable insights. Feel free to download, explore, and provide feedback!
