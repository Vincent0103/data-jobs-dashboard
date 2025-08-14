# Data Jobs Dashboard

## Overview

This project provides a Power BI dashboard for analyzing job postings data. The main Power BI file is `Visualisation.pbix`.

## How to Use

1. **Open the Dashboard**

- Download and install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) if you don't have it already.
- Open the `Visualisation.pbix` file in Power BI Desktop.

1. **Explore the Data**

- Navigate through the different report pages to view charts and data models related to job postings, salaries, and other metrics.
- Use filters and slicers to interact with the data as needed.

1. **Data Issues**

- Note: The `job_postings_flat` table contains some badly formatted data in the `salary_hour_avg` and `salary_year_avg` columns. This may affect the accuracy of charts and models related to salaries.
- If you wish to correct these issues, consider cleaning the data source or using Power Query within Power BI to reformat these columns.

## Troubleshooting

- If you encounter errors or incorrect visuals, check the data types and formatting in the affected columns.
- For further customization or data cleaning, use the Power Query Editor in Power BI Desktop.

## Feedback

If you have suggestions or improvements, please open an issue or submit a pull request.