# Bike Sales Dashboard

In this project, I analyzed a bike company's data to understand factors customers consider before making a purchase decision. The final output is an Excel dashboard providing a comprehensive overview of bike sales data, allowing stakeholders to analyze trends, identify patterns, and make informed decisions.

> **Disclaimer:** All datasets and reports used in this project are dummy data and do not represent any institution, company, or country.

---

## Data Sourcing

After uploading the dataset in Excel, I created three sheets:

1. **Working Sheet:** A copy of the original data for performing all cleaning procedures without risking the raw data.
2. **Pivot Table Sheet:** A sheet where we create pivot tables based on analysis needs.
3. **Dashboard Sheet:** The final sheet for visualizations, including slicers for interactive filtering.

---

## Data Cleaning and Transformation

The initial stage involved familiarizing with the dataset and addressing data quality issues.

1. Removed duplicates, unwanted cells, and irrelevant columns.
2. Used `FIND` and `REPLACE` functions for clarity, e.g., changing "M" to "Married" in "Marital Status" and "F" to "Female" in "Gender".
3. Converted "Income" column to currency format.
4. Created a new column for age brackets using `NESTED IF` function.

---

## Data Analysis

Four pivot tables were created to summarize the data and reveal trends, focusing on the relationship between bike purchases and factors such as average income, commute distance, and age.

---

## Data Visualization

A user-friendly dashboard was created by customizing pivot charts and adding three slicers for interactivity.

![Snippet of the Final Dashboard in Excel](path/to/dashboard-screenshot.png) *(Replace with the actual path to your screenshot)*

---

## Insights

The analysis reveals key insights about bike purchasers:

1. **Income:** Males and females with higher average incomes in their categories were more likely to purchase bikes.
2. **Age Group:** Majority of purchasers were in the 31–54 year age bracket (middle age group).
3. **Commute Distance:** Most purchasers had a 0–1 mile commute, followed by 2–5 miles. Those with 5+ miles were less likely to purchase.
4. **Homeownership:** Homeowners were more likely to purchase bikes.

---

## Recommendations Based on Analysis

1. **Target the 31–54 Age Group:** This segment shows the highest number of purchases.
2. **Focus on Short-Distance Commuters:** An inverse relationship suggests long-distance commuters prefer other transport, so marketing should focus on those with shorter commutes.
3. **Engage Homeowners with Offers:** Homeowners are more likely to respond to offers and discounts, making them a valuable target for promotions.

---

## Getting Started

To view the dashboard:
1. Download the Excel file from this repository.
2. Open it in Excel and navigate to the "Dashboard" sheet for an interactive experience.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
