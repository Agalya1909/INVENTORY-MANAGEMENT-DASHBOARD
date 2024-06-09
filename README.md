# Inventory Management Dashboard

## Table of Contents
1. [Introduction](#introduction)
2. [Description](#description)
3. [Data Sources](#data-sources)
4. [Features](#features)
5. [Usage](#usage)
6. [Project Outputs](#project-outputs)
7. [Conclusion](#conclusion)

## Introduction
In the realm of supply chain and operations management, effective inventory management is crucial for ensuring optimal stock levels, minimizing holding costs, and preventing stockouts. Detailed analysis of inventory data provides deep insights into stock turnover, demand patterns, and replenishment cycles. Assessing key metrics such as inventory turnover ratio, stock levels, and order quantities underpins efficient inventory control and cost management strategies. Furthermore, aggregating inventory data by product category, supplier, and location yields granular insights into inventory trends and operational dynamics.

Multifaceted inventory data analysis unveils richer insights. For example, identifying top-selling products or high-demand periods spotlights potential stock replenishment strategies. The breakdown of inventory by product category and supplier reveals supply chain efficiency trends, highlighting potential areas for optimization. A comprehensive understanding of inventory performance, as indicated by various inventory metrics and KPIs, informs strategic planning and decision-making. Collectively, these analyses enable firms to make data-driven decisions that enhance operational efficiency, reduce costs, and optimize inventory management.

## Description
This comprehensive inventory management analysis aims to facilitate data-driven decision-making and strategic planning. The analysis encompasses multiple key attributes including SKU ID, product category, stock levels, order quantities, reorder points, and key inventory metrics. The objective is to extract actionable insights and trends that can drive business optimization and inventory efficiency.

Monthly and daily inventory data are scrutinized to identify stock turnover trends and demand patterns, enabling precise forecasting and inventory replenishment. Key performance indicators (KPIs) such as inventory turnover ratio, stock levels, and order quantities are assessed to provide a holistic view of the company’s inventory health and supply chain performance. Inventory metrics are analyzed to gauge stock efficiency, guiding inventory control and cost management strategies.

Additionally, the aggregation of inventory data by product category, supplier, and location offers detailed insights into inventory trends and supply chain efficiency. Temporal analysis through the sum of stock levels and order quantities by period reveals inventory behavior patterns, optimizing stock allocation and replenishment planning. This multi-faceted analysis enhances business operations, reduces costs, and improves inventory efficiency through rigorous, data-driven insights.

## Data Sources
The dashboard is constructed using the following data sources:
- **Stocks Table**: Encompasses detailed stock data, including fields for SKU IDs, product categories, stock levels, and reorder points.
- **Past Orders Table**: Contains historical order data, including fields for order quantities, order dates, and SKU IDs.

## Features
- **Inventory Performance Analysis**: Comprehensive reports on inventory metrics segmented by temporal, product, and supplier dimensions.
- **Stock Level Monitoring**: Visual representations of stock levels and reorder points, facilitating a deep understanding of inventory health.
- **Turnover Analysis**: Dynamic analysis of inventory turnover ratios, aiding in the recognition of high and low turnover products.
- **Interactive Visualizations**: Advanced drill-down capabilities and interactive filtering to enable detailed exploration of specific data points and segments.

## Analysis
The analysis was conducted using Microsoft Power BI.

### Steps

1. **Data Import**:
   - The raw data in CSV file format was imported and converted into Microsoft Excel for initial processing.

2. **Data Cleaning**:
   - The data was meticulously cleaned to ensure accuracy and consistency, including standardizing formats and correcting errors.

3. **Data Transformation**:
   - The data was transformed to be suitable for sophisticated analysis. This involved complex calculations, aggregations, and filtering operations. New columns were created as required for the analysis using Microsoft Excel.

4. **Data Visualization**:
   - The analyzed data was visualized using advanced charts and graphs available in Microsoft Power BI. A dynamic and interactive dashboard was created to present the insights derived from the analyzed data.

## Insights
- **Total SKUs**: 500
- **Total Stock Levels**: 150K units
- **Average Stock Level per SKU**: 300 units
- **Total Order Quantities**: 600K units
- **Average Order Quantity per SKU**: 1200 units

### Inventory Turnover Analysis
- **High Turnover Products**:
  - Products with high turnover ratios indicating strong demand and efficient inventory management.
- **Low Turnover Products**:
  - Products with low turnover ratios indicating slow movement and potential overstocking issues.

### Stock Level Monitoring
- **Stock Level by Category**:
  - Analysis of stock levels across different product categories to identify potential stock shortages or surpluses.
- **Reorder Points**:
  - Monitoring of stock levels against reorder points to ensure timely replenishment and prevent stockouts.

### Order Quantity Trends
- **Order Quantities by Period**:
  - Temporal analysis of order quantities to identify demand patterns and peak ordering periods.
- **Order Quantities by Supplier**:
  - Analysis of order quantities segmented by supplier to evaluate supplier performance and reliability.

## Usage
1. **Navigating the Dashboard**: Utilize the navigation pane on the left side to transition between different report pages, such as inventory performance, stock levels, and turnover analysis.
2. **Interacting with Visuals**: Engage with charts, graphs, and other visual elements to filter and emphasize data dynamically. This interactivity allows for comprehensive exploration and analysis of specific segments or data points.
3. **Exporting Reports**: Export the analytical reports by navigating to `File` > `Export` and selecting the desired format, such as PowerPoint or PDF.

## Project Outputs
- **Annual Inventory Turnover**: Computed using a DAX measure to aggregate stock levels and order quantities over the past year.
- **Inventory Performance Dashboards**: Offer in-depth insights into inventory metrics by product, supplier, and temporal factors.
- **Stock Level Reports**: Highlight current stock levels, reorder points, and potential stock shortages or surpluses.
- **Order Quantity Analysis**: Depict order quantities over time to help identify demand patterns and forecast future inventory needs.

## Conclusion
The Inventory Management Dashboard provides a robust, interactive platform for visualizing and analyzing inventory data. By leveraging Power BI's advanced capabilities, this dashboard enables stakeholders to gain actionable insights into their inventory performance, identify stock management opportunities, and make informed strategic decisions. The integration of multiple data sources and the use of sophisticated analytical techniques ensure that users can explore inventory data from various perspectives, ultimately enhancing their decision-making process and optimizing inventory strategies. This tool is essential for businesses seeking to enhance their inventory management and achieve data-driven operational efficiency.

### Stock Level and Order Trends
- The top-selling products and high-demand periods highlight areas for potential stock replenishment strategies.
- The breakdown of inventory by product category and supplier reveals key areas for potential supply chain optimization and cost savings.

### Inventory Health Indicators
- Key inventory metrics such as turnover ratios, stock levels, and reorder points provide a comprehensive snapshot of the company’s inventory health, guiding strategic planning and decision-making.

### Recommendations
- **Seasonal Inventory Strategies**:
  - Implement targeted inventory strategies during peak demand periods to maximize stock efficiency and prevent stockouts.

- **Monthly Inventory Planning**:
  - Focus on optimizing stock levels during low-demand periods through strategic adjustments and inventory control measures.

- **Category-Specific Initiatives**:
  - Expand high-turnover product categories to further enhance inventory efficiency and meet demand.

- **Supplier Management**:
  - Monitor and manage supplier performance to ensure timely and reliable stock replenishment.

- **Inventory Ratio Monitoring**:
  - Regularly monitor key inventory ratios to ensure the company’s inventory health and make necessary adjustments.
