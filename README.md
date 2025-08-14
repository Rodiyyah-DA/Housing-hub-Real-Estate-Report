# Housing-hub-Real-Estate-Report

## Table of Contents

- [Introduction](#introduction)
- [Data Sources](#data-sources)
- [Problem Statement](#problem-statement)
- [Power BI and Analytics Technical Skills](#power-bi-and-analytics-technical-skills)
- [Data Modelling](#data-modelling)
- [Report Design and Visualization](#report-design-and-visualization)
- [Analytics and Insights](#analytics-and-insights)
- [Conclusions and Recommendations](#conclusions-and-recommendations)
- [Deployment to Power BI Service](#deployment-to-power-bi-service)

### Introduction
---

The Housing-Hub Real Estate Report is an interactive Power BI dashboard designed to provide a comprehensive overview of property sales trends across multiple cities. It consolidates real estate data to present key metrics such as annual and monthly sales prices, property counts by location, average sales by city, and sales distribution by bedroom count. By integrating these insights, the dashboard enables stakeholders to track market performance, identify growth opportunities, and make informed decisions.

<img width="745" height="415" alt="RODIYYAH'S PROJECT 1" src="https://github.com/user-attachments/assets/a5b1eda3-844e-40ff-a23f-a5ab84a36c1e" />

### Data Sources
---

The data used for this report was sourced from the Housing-Hub property sales dataset, containing detailed information about property transactions across multiple cities. Key fields included:
- Property Details: City, number of bedrooms, and vacancy status.
- Transaction Data: Sales price, sale year, and monthly sales figures.
- Aggregated Metrics: Total property counts, total sales value, and average sales prices by city.
  Here is the link to the data [Download here](https://drive.google.com/file/d/161wLH6DHmi_6aq5HG_TbJzIGVXkGcafO/view?usp=drivesdk)

### Problem Statement
---

The real estate market is highly dynamic, with property values and sales volumes fluctuating based on location, season, and market demand. However, without a centralized and interactive reporting tool, stakeholders struggle to gain a holistic view of market trends. Traditional static reports often fail to highlight real-time changes, city-specific performance, and price variations, making it difficult for investors, property managers, and policy makers to respond effectively. The Housing-Hub Real Estate Report addresses this challenge by providing a visual and data-driven solution to track property sales metrics, analyze market patterns, and support strategic decision-making.

### Power BI and Analytics Technical Skills
---

- Project Planning and Documentation
- Data Gathering
- Power Query
- Data Modelling
- Report Design
- Data Visualization
- Data Analysis Expression (DAX)
- Feedback and Continuous Improvement

### Data Modelling
---

The data model was structured to ensure accurate relationships and efficient filtering across the report. Key modeling steps included:
- Establishing a relationship between the main sales data table and a Calendar table via the Date field for time-based analysis.
- Creating calculated measures in DAX for metrics like total sales value, average sales price, and monthly trends.
- Implementing filters and slicers for Year, Property City, and Vacancy Status to provide dynamic, user-driven analysis.
This model ensured high performance and accuracy in visual aggregation.

<img width="747" height="503" alt="Data modelling Project 1" src="https://github.com/user-attachments/assets/679f6fb8-3e3e-4354-b2c5-ff8b87181bc2" />

### Report Design and Visualization
---

The Report Canvas was designed in Power Point and imported to PowerBI as canvas background. Here is a sample of the slide in Power Point

<img width="918" height="510" alt="Presentation A" src="https://github.com/user-attachments/assets/a600422a-5978-457f-9ec1-73c2fb2e6167" />

### Analytics and Insights
---

The dashboard revealed several important trends:
- Annual Sales Price: Highest recorded sales in 2015 with a total of 7 billion, while 2013 had the lowest at 3 billion.
- City Performance: Nashville led the market with over 40K property sales and the highest average sales value.
- Seasonal Trends: Peak monthly sales occurred in mid-year, particularly around May–July, before declining towards year-end.
- Bedroom Analysis: Properties with 3–4 bedrooms accounted for the majority of sales value, showing a preference in the buyer’s market.
- Market Value: The dataset represented a total of 56.48K properties, 6 billion in value, and 18 billion in total sales.

 ### Conclusions and Recommendations
 ---

  The Housing-Hub Real Estate Report demonstrates the value of interactive business intelligence tools in understanding property market trends. By enabling real-time filtering, city-level performance tracking, and year-over-year comparisons, it offers a strategic advantage to decision-makers.
Recommendations:
- Focus marketing strategies on top-performing cities like Nashville and Joelton.
- Analyze mid-year peaks to align property listings and promotions with buyer activity.
- Explore the demand for 3–4 bedroom homes to target high-value customer segments.

 ### Deployment to Power BI Service
 ---

The report was published to the Power BI Service for cloud-based access, enabling:
- Collaborative sharing among stakeholders.
- Scheduled data refreshes to keep insights up to date.
- Secure access controls for data governance.
