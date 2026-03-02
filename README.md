# International-Migration-Trends-Analysis-1980-2013

Canadian Immigration Analysis (1980 – 2013)

An end-to-end data analysis and geospatial visualization project using Python.

**📌 Project Overview**

This project analyzes a longitudinal dataset from the United Nations detailing international immigrant flows to Canada over a 33-year period. The goal was to transform raw Excel data into actionable insights through rigorous data cleaning, trend analysis, and interactive geospatial mapping.

**🛠️ Technical Stack**

Data Manipulation: Pandas, NumPy

Data Visualization: Matplotlib (Pyplot)

Geospatial Intelligence: Folium (Interactive maps with markers and popups)

**🚀 Data Pipeline & Workflow**

**1. Data Acquisition & Wrangling**

Source: United Nations Department of Economics and Social Affairs (2015).

Processing: Extracted data from the Canada by Citizenship sheet while skipping 20 rows of metadata and summary footers.

Dimensionality Reduction: Dropped non-essential columns such as AREA, REG, and DEV to optimize the dataframe for longitudinal analysis.

**2. Feature Engineering**

Renamed legacy column headers (e.g., OdName → Country, AreaName → Continent) for improved readability.

Calculated a 'Total' column representing the cumulative sum of immigrants for each country from 1980 to 2013.

**3. Visual Intelligence**

Trend Analysis: Visualized migration patterns across different decades and continents.

Interactive Mapping: Utilized Folium to create a world map with interactive markers (latitude/longitude) and popups to visualize immigration stop-points and regional density.

**📊 Key Insights (Sample)**

The dataset tracks migration flows from 195 countries.

Significant historical shifts were identified in immigration origins, specifically moving from European-centric to Asian-centric flows between 1980 and 2013.

