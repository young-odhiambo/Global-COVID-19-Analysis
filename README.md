# Global COVID-19 Analytics
## Project Overview
This project is an interactive Power BI dashboard that analyzes global COVID-19 data to provide insights into confirmed cases, recoveries, deaths, testing, and recovery trends across countries and continents. 
The dashboard is designed to help users quickly understand the global impact of the pandemic through intuitive visualizations and key performance indicators (KPIs).

----

## Objectives
- Analyze global COVID-19 cases and trends.
- Compare cases, recoveries, and deaths across countries.
- Calculate Recovery Rate and Death Rate using DAX.
- Create an interactive dashboard for data exploration.
- Demonstrate data modeling and visualization best practices.

----

## Dashboard Highlights
Key Performance Indicators (KPIs)
- Total Cases: 1.4 Billion
- Total Recovered: 1.2 Billion
- Total Deaths: 14.0 Million
- Total Population Tested: 7.0 Billion
- Recovery Rate: 87.7%
- Death Rate: 0.99%

## Visualizations
![image alt](https://github.com/young-odhiambo/Global-COVID-19-Analysis/blob/4461449a5616cd9b1e8f75b82b20f4022c29ee62/Screenshot%202026-07-06%20010956.png)

----
# Key Insights
## Global Overview
The dataset reports approximately 1.4 billion confirmed cases globally.
Around 1.2 billion patients recovered, resulting in an overall 87.7% recovery rate.
Global deaths totaled approximately 14 million, representing a 0.99% death rate.
## Continental Analysis
Europe recorded the highest number of confirmed cases and deaths.
Asia ranked second in total confirmed cases while maintaining strong recovery numbers.
Africa and Oceania reported comparatively fewer cases and deaths than other continents.
## Country Analysis
The United States recorded the highest number of confirmed cases.
Other highly affected countries include India, France, Germany, Brazil, South Korea, Japan, Italy, the United Kingdom, and Russia.
The highest recorded deaths were concentrated in the United States, Brazil, India, Russia, and Mexico.
## Recovery Trends
Several countries achieved recovery rates approaching 100%, indicating effective case resolution relative to confirmed infections.
The global recovery rate of 87.7% demonstrates that the majority of reported infections resulted in recovery.

# Tools & Technologies
- Power BI Desktop
- Power Query
- DAX
- Interactive Visualizations

# DAX Measures
Some of the measures created include:

```DAX

Recovery Rate =
DIVIDE(
    SUM(Covid_19[Recovered]),
    SUM(Covid_19[Cases]),
    0
)

Death Rate =
DIVIDE(
    SUM(Covid_19[Deaths]),
    SUM(Covid_19[Cases]),
    0
)
```

## Skills Demonstrated
- Data Cleaning
- Data Transformation
- DAX Calculations
- KPI Design
- Dashboard Design
- Data Visualization
- Business Intelligence
- Analytical Storytelling

## Dashboard Preview

Include screenshots of the dashboard here after uploading them to your repository.
![image alt](https://github.com/young-odhiambo/Global-COVID-19-Analysis/blob/46fcc92c09bc432f5827ebd26fcb0b997e81aa32/Screenshot%202026-07-06%20010956.png)
![image alt](

