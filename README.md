# Walmart Sales Analysis Dashboard \| Power BI

An interactive **Power BI dashboard project** built to explore Walmart
sales performance, store-level results, holiday impact, and potential
sales drivers.

This repository contains the Power BI report, dashboard screenshots,
project README, and the dataset used for the analysis.

## Project Overview

The project analyzes Walmart historical sales data to turn raw business
data into clear, interactive insights. The report is organized into two
dashboard pages:

1.  **Executive Summary** -- provides a high-level view of sales
    performance and store results.
2.  **Sales Drivers Analysis** -- explores how selected business and
    economic variables relate to sales.

Users can interact with the report using the available slicers,
including **Store**, **Year**, and **Holiday Type**.

## Dashboard Pages

### 1. Executive Summary

This page gives an overview of the main sales KPIs and trends.

**KPI cards displayed** - Total Sales - Total Stores - Average Weekly
Sales - Holiday Sales - Sales Growth %

**Visuals** - Sales trend over time - Top 10 stores by sales - Holiday
vs. non-holiday sales - Year-wise sales analysis - Sales by month

![Walmart-Sales-Drivers-Analysis](images/Dashboard%201.png)
### 2. Sales Drivers Analysis

This page explores sales alongside selected external and economic
indicators.

**KPI cards displayed** - Average Temperature - Average Fuel Price -
Average CPI - Average Unemployment - Average Sales per Store

**Visuals** - Sales by holiday type - Sales vs. temperature - Fuel price
trend - CPI vs. sales - Average unemployment by year

![Walmart-Sales-Drivers-Analysis](images/Dashboard%202.png)

> **Note:** The dashboard screenshots above are linked to the suggested
> image paths. Save your screenshots in the `images` folder using these
> exact filenames, or update the paths in this README to match your
> filenames.

## Tools and Technologies

-   **Microsoft Power BI Desktop** -- data modeling, report development,
    interactive visuals, and dashboard design
-   **Power Query** -- data import and transformation (where used)
-   **DAX** -- measures and calculations (where used)
-   **Microsoft Excel / CSV** -- dataset storage and initial inspection

## Dataset

Upload the dataset used in this project to the repository and update
this section with its exact source and filename.

Suggested details to document: - **Dataset file:**
`data/walmart_sales.csv` (replace with your actual filename) -
**Source:** Add the original dataset source or attribution link. -
**Coverage:** Add the date range and number of records after checking
the dataset. - **Grain:** Explain what one row represents (for example,
store-week observations), based on the actual dataset. - **Main
fields:** Include the fields present in your file, such as store, date,
weekly sales, holiday flag, temperature, fuel price, CPI, and
unemployment, if applicable.

Do not describe a field as present in the dataset unless it is included
in the uploaded file.

## Key Questions Explored

-   How do sales change over time?
-   Which stores generate the highest sales?
-   How do holiday and non-holiday sales compare?
-   Which months and years show stronger or weaker sales?
-   How do temperature, fuel price, CPI, and unemployment move alongside
    sales?
-   Which business patterns may be worth investigating further?

## How to Use the Project

1.  Download or clone this repository.
2.  Download the dataset and place it in the location configured in the
    Power BI report.
3.  Open the `.pbix` file using **Power BI Desktop**.
4.  If Power BI asks for the dataset location, update the source path in
    **Transform data → Data source settings** or in Power Query.
5.  Select **Refresh** to load the data.
6.  Use the slicers to explore the report by store, year, and holiday
    type.

> If the report uses a local file path, you may need to update that path
> on your computer before refreshing.

## Repository Structure

``` text
walmart-sales-analysis/
│
├── README.md
├── Walmart_Sales_Analysis.pbix
├── data/
│   └── walmart_sales.csv
│
└── images/
    ├── executive-summary.png
    └── sales-drivers-analysis.png
```

Rename the example files and folders to match the files you actually
upload. If you keep the dataset in the repository root, update the
structure above accordingly.

## Important Notes

-   KPI values shown in screenshots represent the report state at the
    time the screenshots were captured. They may change when slicers or
    filters are applied.
-   The dashboard is an analytical and learning project. Relationships
    shown in charts should not automatically be interpreted as proof of
    causation.
-   Include the dataset's original source and license or usage terms
    before redistributing it.
-   A `.pbix` file is best viewed with Microsoft Power BI Desktop.

## Author

**Harshit Kumar Pandey**\
MBA -- Business Analytics\
Interested in Data Analytics, Business Intelligence, and data-driven
decision-making.

------------------------------------------------------------------------

If you find this project useful, feel free to ⭐ the repository.
