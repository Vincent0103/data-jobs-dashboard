# Data Jobs Dashboard

![Dashboard Page 1](/images/dashboard.png)

## Overview

This project provides an interactive Power BI dashboard for analyzing global data jobs. The dashboard visualizes job postings, salary trends, job types, and more, helping users explore the data job market in detail. The main Power BI file is `data_jobs_dashboard.pbix`.

## Dashboard Pages Overview

Below are the main pages of the dashboard, each providing a different perspective on the data jobs market:

**Page 1: High-Level Market View**  

![Dashboard Page 1](/images/dashboard.png)

Gives an overview of the global data jobs market, including total job counts, salary statistics, job trends over time, and a breakdown by job title.

**Page 2: Job Title Drill Through**  

![Dashboard Page 2](/images/job-title-drill-through.png)

Allows you to drill through to a specific job title for detailed insights, such as salary breakdowns, work-from-home rates, education requirements, global job distribution, and job platform analysis.

## Dashboard Features

The dashboard includes the following key visualizations and features (see example screenshots in the `images/` folder):

- **Summary Cards:**
  - Total job postings, number of countries, yearly and hourly salary counts.
- **Job Trends Over Time:**
  - Line chart showing the evolution of job postings by month, with trend lines and data labels.
- **Job Title Breakdown:**
  - Table and bar chart showing job counts, salary counts, and trends for top job titles (e.g., Data Engineer, Data Analyst, Data Scientist).
- **Salary Analysis:**
  - Stacked area chart visualizing yearly salary counts by job title and quarter.
- **Drill-Through Functionality:**
  - Select a job title to view a detailed breakdown, including:
    - Salary gauges (yearly/hourly)
    - Work from home %, no degree mention %, health insurance %
    - Global job distribution map
    - Job platform and schedule type breakdowns

## How to Use

1. **Open the Dashboard**

- Download and install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) if you don't have it already.
- Open the `data_jobs_dashboard.pbix` file in Power BI Desktop.

1. **Explore the Data**

- Use filters and slicers (e.g., job title dropdown) to interact with the data.
- Click on job titles to drill through to detailed views.
- Navigate through report pages to explore job trends, salary distributions, and job characteristics globally.

## Data Quality Notes

- The `job_postings_flat` table contains some badly formatted data in the `salary_hour_avg` and `salary_year_avg` columns. This may affect the accuracy of salary-related charts and models.
- For best results, consider cleaning the data source or using Power Query within Power BI to reformat these columns.

## Troubleshooting

- If you encounter errors or incorrect visuals, check the data types and formatting in the affected columns.
- For further customization or data cleaning, use the Power Query Editor in Power BI Desktop.

## Screenshots

Example dashboard views are available in the `images/` folder:

- `dashboard.png`: Main dashboard overview
- `dashboard-filtered.png`: Dashboard filtered by job title
- `job-title-drill-through.png`: Detailed view for a selected job title

## Feedback

If you have suggestions or improvements, please open an issue or submit a pull request.

## Acknowledgement

Thank you [Luke Barousse](https://www.youtube.com/@LukeBarousse) for providing this free insanely valuable course on Power BI, it would've been much harder to learn this tool without your guidance.
You can have a look to his tutorial here: [Power BI for Data Analytics - Full Course for Beginners](https://www.youtube.com/watch?v=FwjaHCVNBWA&t=12130s)

## Conclusion

This is my first ever data project I made. It was made to further enhance my Power BI skills for my upcoming internship in data where my tutor told me to learn about that tool.
I'm very satisfied of the outcome even though I still have some issues with the formatting of the values in the data model.

I now know the very basics of power BI and I'm now ready to create very insightful and beautiful charts.
