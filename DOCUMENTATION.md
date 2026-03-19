# Comprehensive Documentation

## Project Overview
This project aims to analyze the ROI of the MyChart platform in the healthcare system. It includes various metrics and insights into usage and financial returns.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/heeralsheth/epic-mychart-roi.git
   ```
2. Navigate to the project directory:
   ```bash
   cd epic-mychart-roi
   ```
3. Install required dependencies:
   ```bash
   npm install
   ```
4. Configure the environment:
   - Set up `.env` file with the necessary API keys and database credentials.

## File Descriptions
- `main.py`: The main entry point of the project that triggers the analysis.
- `data_analysis.py`: Contains functions for data cleaning and preparation.
- `roi_calculator.py`: Module for calculating ROI based on usage metrics.
- `queries.sql`: SQL file with queries used for extracting data from the database.

## SQL Query Explanations
- `SELECT * FROM users;` - Retrieves all user records for analysis.
- `SELECT SUM(revenue) FROM transactions WHERE date > '2025-01-01';` - Calculates total revenue from transactions after Jan 1, 2025.

## Analysis Methodology
The analysis involves:
1. Gathering data from the MyChart database.
2. Cleaning and transforming data using Python scripts.
3. Calculating ROI by comparing costs against financial returns derived from the data.

## Key Findings
1. Increased user engagement correlates with higher ROI.
2. ROI calculations indicate a positive trend in quarterly profits since integrating MyChart.

## ROI Calculations
The ROI is calculated using the formula:
\[
ROI = \frac{(Total Revenue - Total Costs)}{Total Costs} \times 100
\]
Where Total Revenue consists of all benefits accrued from using MyChart, and Total Costs include implementation and operational expenses.

## Troubleshooting Guide
- If the project does not run, check the configuration in the `.env` file.
- Ensure all dependencies are installed and up to date.
- Review the logs for specific error messages that can guide resolution.

## Next Steps
1. Explore additional user metrics to further enhance the analysis.
2. Consider incorporating machine learning for predictive analytics.
3. Regularly update the documentation to reflect changes in methodology or findings.
