# Power BI Business Intelligence Portfolio

This repository presents a complex, end-to-end Power BI business intelligence solution designed to support management decision-making, operational monitoring, and process automation.

The project demonstrates not only reporting and visualization skills, but also data modeling, DAX, Power Query transformations, Power Apps integration, and Power Automate workflows.

## Project Overview
This portfolio project is based on a real-world business intelligence solution developed for a workforce management and staffing organization.

The entire solution was designed and implemented end-to-end by me, covering data collection, data transformation, data modeling, DAX measure development, visual design, and Power Apps integration.

All company names, personal data, logos, and other sensitive information have been fully anonymized, replaced, or removed.

The report is structured as a multi-page interactive dashboard covering financial performance, operational efficiency, recruitment analytics, and management workflows.

## Key focus areas:
- Revenue, costs, profit and working hours
- Project manager and partner performance
- Recruitment funnel analysis
- Trend analysis with forecasting
- Workflow automation and approval processes
- End-to-end business visibility

## Navigation & UX

- Dedicated cover page with Page Navigator
- Consistent layout across pages
- Reusable slicers (Date, Partners, Project Managers)
- Drillthrough pages for deeper analysis
- Conditional formatting and dynamic visuals
- Bookmark-based visual switching

## Pages & Functionality

### 1 Project Managers Overview
- Financial summary table: Revenue, Workforce Cost, Profit, Hours
- Dynamic donut chart switching between Profit / Hours / Revenue
- Implemented using overlapping visuals controlled by visibility
- Slicers: Date, Partners, Project Managers

### 2 Partners Overview
- Identical analytical structure as the Project Managers page
- Focus shifted to partner companies
- Enables direct comparison across partners

### 3 Partner Drillthrough Page
- Drillthrough from partner-level visuals
- Displays detailed financial and operational information for a selected partner

### 4 Profit Analysis
- Two column charts:
  - Top partners by profit margin (based on management fee)
  - Top partners by absolute profit
- Enables comparison between margin efficiency and total contribution

### 5 Revenue Trends & Forecasting
- Revenue trend analysis with:
  - Min / Max indicators
  - Forecasting
- Gauge visual showing target achievement vs previous year
- Dynamic coloring based on performance

### 6 Recruitment Funnel Analysis
- Analysis of applications:
  - Successful
  - Unsuccessful
  - In progress
- Drillthrough to failure analysis using:
  - Donut chart
  - Waterfall chart

### 7 Partner Popularity Analysis
- Ranking partners based on number of applications
- Visuals for:
  - Top 5 most popular partners
  - Top 5 least popular partners

### 8 Commission Request Workflow (Power Apps Integration)
- Embedded Power Apps application inside Power BI
- Project managers submit commission requests
- Managers validate data directly in Power BI
- Approval or rejection based on verified metrics
- Demonstrates Power BI + Power Apps integration

### 9 Ideas & Future Enhancements
Conceptual and future-ready ideas:
- Partner map visualization
- Power Automate flow for sending automated reminder letters
- Marketing cost distribution visuals

Some visuals are conceptual due to missing source data, but demonstrate design thinking and scalability.

##  Data Model & Logic

- Data sources were primarily Excel-based, focusing on transformation, modeling and automation within Power BI
- Star-schema-based data model with two fact tables:
  - FACT_Jelentkezések (applications and recruitment data)
  - FACT_SzámlákTémák (financial and invoicing-related data)
- Shared dimension tables for Date and Partners
- Applicant dimension (DIM_Tagok) connected exclusively to the applications fact table
- All relationships implemented as many-to-one (fact-to-dimension), following Power BI best practices
- Clean, single-directional relationship structure to ensure predictable filtering behavior


## DAX & Power Query

- Custom DAX measures for:
  - Financial KPIs (revenue, labor cost, profit, profit margin)
  - Recruitment and application funnel metrics
  - Status-based logic to determine a single, prioritized outcome per applicant, avoiding duplicate counting
  - Distinct counting and ratio-based indicators (e.g. popularity index)
- Power Query transformations for:
  - Data cleaning
  - Standardization
  - Transformation logic

##  Tools & Technologies

- Power BI
- DAX
- Power Query
- Power Apps
- Power Automate
- Excel

##  Key Takeaways

- Demonstrates end-to-end BI thinking
- Strong focus on automation and operational efficiency
- Combines analytics with real business workflows
- Designed for both management and operational users

## Contact

Gabriel Pielka  
LinkedIn: https://www.linkedin.com/in/gabrielpielka
