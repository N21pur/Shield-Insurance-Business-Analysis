# Shield-Insurance-Business-Analysis

This project involves analyzing insurance-related data provided in five CSV files. Each file contains key data on customers, policies, premiums, settlements, and dates. The goal of this project is to explore relationships between these datasets, perform data cleaning, validation, and create insightful reports and visualizations to aid decision-making.

## Files and Columns

1. **dim_customer.csv**: Contains customer information.
   - `customer_code`: Unique identifier for each customer.
   - `dob`: Date of birth of the customer.
   - `city`: The city where the customer resides.

2. **dim_date.csv**: Provides date-level information.
   - `date`: Daily-level date.
   - `mmm_yy`: Month and year (in "MMM-YY" format).
   - `day_type`: Day of the week (Sunday, Monday, etc.).
   - `week_no`: Week number of the year.

3. **dim_policies.csv**: Includes policy details.
   - `policy_id`: Unique ID for each policy.
   - `base_cover`: Base coverage amount of the policy.
   - `base_premium_amt (INR)`: Premium amount for the policy.

4. **fact_premiums.csv**: Contains details about policy premiums.
   - `date`: Date when the policy was sold.
   - `customer_code`: Unique identifier for each customer.
   - `policy_id`: Unique ID for each policy.
   - `sales_mode`: Mode of sales (Offline-Agent, Offline-Direct, Online-App, Online-Website).
   - `final_premium_amt (INR)`: Final premium amount paid by the customer.

5. **fact_settlements.csv**: Provides information on policy settlements.
   - `age`: Age of the policyholder.
   - `settlement%`: Percentage of settlements for each age group.

## Tools and Technologies

- **Power BI**: For data visualization and reporting.
- **Python**: For data cleaning and validation.
- **Pandas**: For data manipulation and transformation.

## Key Objectives

- Analyze customer demographics and purchase behavior.
- Track premium trends and settlement rates.
- Generate visual reports to identify patterns in policy sales and settlement rates.
