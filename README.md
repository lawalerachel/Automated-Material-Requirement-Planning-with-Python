# Project Overview
## Aim
The aim of this project is to enhance the material requirement planning process by transitioning from Excel-based planning to an automated solution using Python. This project focuses on optimizing production processes by ensuring a continuous and efficient supply of materials, leveraging the power of Python for advanced analytics and automation.

## Key Features
+ Automated Planning: Automates material requirement planning for all production dates in monthly buckets.
Data Integration: Seamlessly integrates various data sources such as monthly production plans, opening stock levels, and material master data.
+ Advanced Analytics: Utilizes Python's robust libraries for data analysis and visualization to provide insightful metrics and decision-making support.

## Data Sources
+ Monthly Production Plan: Outlines the production schedule for the next three years, crucial for understanding demand for different SKUs in various pack sizes.
+ Material Master Data Sheet: Contains detailed information about raw and packaging materials, including opeing stock, unit of measure, material category, bill of material, safety stock, and minimum order quantity.

## Tools and Technologies
+ Python: Used for automating the material requirement planning process.
+ Pandas: For data manipulation and analysis.
+ NumPy: For numerical operations.

## Project Outcome
The project provides an automated MRP sheet detailing:
- Planned usage
- Reorder quantity
- Projected closing stock
- Days of Cover (DOC) per month for each material

###### The automated MRP process translates the production schedule for finished goods into time-phased raw material requirements. Visual cues in the form of conditional formatting allow quick assessment of material stock levels, projected DOC, and required purchase quantities. This user-friendly representation enhances the overall effectiveness of the MRP process, ensuring material planning aligns with production needs while minimizing the risk of shortages or excess stock.

## Limitations
The accuracy and success of the model depend on the quality of the input data. Discrepancies or inaccuracies in the data sources could impact the reliability of the model's predictions and recommendations.

## Getting Started
## Prerequisites
- Python 3.x
- Pandas
- NumPy
