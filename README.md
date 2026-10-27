# Marketing Funnel & Conversion Performance Analysis

## Project Overview
This project analyzes direct-marketing campaign data using Microsoft Power BI to evaluate subscription outcomes, compare conversion rates across customer segments, and explore campaign performance.

**Important:** The dataset represents direct-marketing contacts and term-deposit subscriptions rather than a website visitor-to-customer funnel.

## Objectives
- Measure total contacts, successful subscriptions, unsuccessful contacts, and conversion rate.
- Compare conversion performance across contact channels and months.
- Analyze successful subscriptions and conversion rates by job category.
- Explore how conversion rates vary with campaign contact frequency.
- Build an interactive Power BI report using slicers and visualizations.

## Tools Used
- Microsoft Power BI Desktop
- Power Query
- DAX
- GitHub

## Dataset
**Source:** UCI Machine Learning Repository — Bank Marketing Dataset  
https://archive.ics.uci.edu/dataset/222/bank+marketing

The analysis uses `bank-full.csv`, containing 45,211 records and 17 columns.

## Key Performance Indicators
- **Total Contacts:** 45,211
- **Successful Subscriptions:** 5,289
- **Unsuccessful Contacts:** 39,922
- **Overall Conversion Rate:** 11.70%

## Report Features
- KPI cards for campaign outcomes
- Conversion rate by contact channel
- Monthly conversion trend
- Campaign outcome distribution
- Successful subscriptions by job category
- Monthly conversion-rate matrix by contact channel
- Interactive month, contact-channel, and job-category slicers
- Campaign contact-frequency analysis

## Methodology
Data was imported and prepared in Power Query. DAX measures were created to calculate contact totals, successful and unsuccessful subscriptions, and conversion rate. The resulting measures were used in interactive visualizations to compare campaign outcomes.

## Key Findings
The overall subscription conversion rate is approximately 11.70%. The report enables further comparison of conversion rates across contact channels, months, job categories, and campaign contact frequency. Segment-specific conclusions should be based on the final report's filtered visual results.

## Files
- `Marketing_Funnel_Conversion_Analysis.pbix` — Power BI report
- `screenshots/` — report screenshots

## How to View
Download the `.pbix` file and open it using Microsoft Power BI Desktop.

## Disclaimer
This project is for educational and analytical purposes. It uses the UCI Bank Marketing dataset and does not represent a live banking campaign.
