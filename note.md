# Data Cleaning and Initial Business Insights

## Cleaning Steps:
- The dataset contains 2823 rows and 25 columns.
- The ORDERDATE column was originally in object format and was converted to datetime.
- Missing values were handled:
  - ADDRESSLINE2 (71%) → filled with "Unknown"
  - STATE (29%) → filled with "Unknown"
  - POSTALCODE (15%) → filled with "Unknown"
- No duplicate rows were found.
- The cleaned dataset was saved as `cleaned_data.csv`.

## Initial Business Insights:
- The highest number of orders was recorded in 2004 (1351 orders).
- 92.6% of all orders have the status "Shipped", indicating a strong and efficient delivery process.
- SALES statistics:
  - Minimum: 482
  - Maximum: 14082
  - Average: 3553
  - Median: 3184
- The top 5 countries by number of orders (such as USA, Spain, France, etc.) represent the main sources of revenue, and marketing strategies should focus on these regions.
