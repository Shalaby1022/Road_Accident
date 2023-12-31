# Road Accident Data Analysis with Power BI

## Overview
This comprehensive Power BI project delves into the analysis of road accident data in England, providing valuable insights and actionable information through interactive reports and dashboards. The project covers various critical aspects, from data preprocessing to advanced analytics and visualization techniques, ensuring a holistic understanding of road safety trends.

## Table of Contents

- [Overview](#overview)
- [Project Steps](#project-steps)
- [Functionalities](#functionalities)
- [Data Transformations](#data-transformations)
- [Measures](#measures)
- [Relationships](#relationships)
- [Power BI Service Link](#power-bi-service-link)
-  [Power BI App Link](#power-bi-app-link)


---

## Project Steps

1. **Creating Workspace in Power BI:**
   - Set up a collaborative workspace for efficient project management.

2. **Static and Dynamic RLS:**
   - Implemented both static and dynamic Row-Level Security for controlled and flexible data access.

3. **Publishing to Power BI Service:**
   - Made the project accessible by publishing it to Power BI Service.

4. **Data Gateway:**
   - Ensured secure data connectivity between on-premises and Power BI Service using Data Gateway.

5. **Role Subscription and Alert:**
   - Enhanced user experience with role subscriptions and alerts.

6. **Sharing and App Development:**
   - Facilitated collaboration by sharing the report and developed a dedicated app for a seamless user experience.

7. **Data Visualization and Dashboard:**
   - Utilized various visualization techniques and created a comprehensive dashboard for key metrics.

---

## Functionalities

- **Connect Power BI to MS SQL Server:**
  - Established a seamless connection between Power BI and MS SQL Server.

- **Data Modeling with Three Tables:**
  - Organized data from three distinct tables using Power BI's data modeling capabilities.

- **Data Cleaning in Power Query:**
  - Utilized Power Query for effective data cleaning, ensuring accuracy and consistency.

- **Time Intelligence Function:**
  - Implemented time intelligence functions to analyze temporal patterns in the dataset.

- **Create Key Performance Indicators (KPIs):**
  - Developed KPIs to measure and evaluate essential performance metrics derived from the data.

- **DAX Queries:**
  - Leveraged various DAX functions for diverse data calculations and manipulations.

- **Shapes and Formatting:**
  - Enhanced visual appeal and clarity by incorporating various shapes and meticulous formatting.

- **Generate Insights from Charts:**
  - Analyzed charts to extract meaningful insights for decision-making.

---

## Data Transformations

- Removed columns: "Day_of_Week," "Carriageway_Hazards," "Junction_Detail"
- Replaced occurrences of "Fetal" with "Fatal" in the "Accident_Severity" column.

---

## Measures

- **cy accidents:**
  - Total accidents year-to-date.

- **cy Casualties:**
  - Total casualties year-to-date.

- **py accidents:**
  - Count of accidents for the same period last year.

- **py Casualties:**
  - Total casualties for the same period last year.

- **yoy accidents:**
  - Year-over-year percentage change in the number of accidents.

- **yoy Casualties:**
  - Year-over-year percentage change in casualties.

---

## Relationships

1. **One-to-Many Relationship with Calendar Table:**
   - Established a one-to-many relationship between the calendar_table and Data.

2. **Many-to-One Relationship for Dynamic RLS:**
   - Introduced a many-to-one relationship linking Access Control with Local_Authority_(District) in the Data Table.

3. **Dynamic RLS Management through Access Control and Calendar Table:**
   - Implemented a relationship between Access Control and Local_Authority_(District) for efficient Dynamic Row-Level Security (RLS) roles.

---

## Power BI Service Link

[Link to Power BI Service](https://app.powerbi.com/groups/d9d09094-3b7d-4cec-b93f-691b0623f5f6/list?experience=power-bi)

## Power BI App Link

[Link to Power BI App](https://app.powerbi.com/groups/me/apps/c7a9823d-fdec-4184-baa2-fe2bcb19b528/reports/bf1a676b-d7e6-43dc-90db-06a1e3dd09e8/ReportSection?experience=power-bi)


---

Feel free to enhance and personalize this template based on your specific project details. Add visuals, badges, or any other elements that can make your README even more engaging and informative.
