# Data Jobs Dashboard v2.0

![Dashboard v2.0](/images/dashboard-v2.png)

## Overview

This repository contains the second iteration of the Data Jobs Dashboard. Version 2.0 consolidates everything into a single interactive page with improved visuals, updated metrics, and smoother interactions. The main Power BI file is `data_jobs_dashboard_2.0.pbix`.

You can use slicers (e.g., by job title) to filter the view. The example below shows the same dashboard with a filter applied:

![Dashboard v2.0 – Filtered](/images/dashboard-v2-filtered.png)

## Key Features

The dashboard includes the following visuals and interactions:

- **Summary Cards:**
  - Total job postings, number of countries, yearly and hourly salary counts.
- **Job Trends Over Time:**
  - Line chart showing the evolution of job postings by month, with trend lines and data labels.
- **Job Title Breakdown:**
  - Table and bar chart showing job counts, salary counts, and trends for top job titles (e.g., Data Engineer, Data Analyst, Data Scientist).
- **Salary Analysis:**
  - Stacked area chart visualizing yearly salary counts by job title and quarter.
  
Note: v2.0 does not include separate drill-through pages; all exploration happens on the single overview page via filtering and cross-highlighting.

## How to Use

### Open the Dashboard

- Download and install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) if you don't have it already.
- Open the `data_jobs_dashboard_2.0.pbix` file in Power BI Desktop.

### Explore the Data

- Use filters and slicers (e.g., job title dropdown) to interact with the data.
- Cross-select in visuals to highlight related data across the page.

## Data Quality Notes

- The `job_postings_flat` table has now been fixed with good values representing the real-world data.

## Troubleshooting

- If you encounter errors or incorrect visuals, check the data types and formatting in the affected columns.
- For further customization or data cleaning, use the Power Query Editor in Power BI Desktop.

## Screenshots

Example views for version 2.0 are available in the `images/` folder:

- `dashboard-v2.png`: Main dashboard overview
- `dashboard-v2-filtered.png`: Same dashboard with filters applied

## Feedback

If you have suggestions or improvements, please open an issue or submit a pull request.

## Acknowledgement

Thank you [Luke Barousse](https://www.youtube.com/@LukeBarousse) for providing this free insanely valuable course on Power BI, it would've been much harder to learn this tool without your guidance.
You can have a look to his tutorial here: [Power BI for Data Analytics - Full Course for Beginners](https://www.youtube.com/watch?v=FwjaHCVNBWA&t=12130s)

## Conclusion

So I now finished the entire power BI course. It was a great adventure and now I'm ready to put into practice my newly learnt skill into practice!

I took about 1 week to follow the entire course and I'm not going to lie there were a lot of time where I didn't have the motivation to follow along because of how long it was but consistency is the key!

If you're looking to learn Power BI then for sure go learn Luke, he is a very good instructor.
