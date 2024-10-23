# Agricultural Data Analysis 

## Overview
This project involves the analysis of agricultural data across India using a combination of Python for data cleaning and Tableau for data visualization. The primary objectives were to understand the production trends, yield performance, and major contributing crops across states and agro-climate regions (ACR). The analysis also includes the calculation of the Compound Annual Growth Rate (CAGR) for cultivated area, crop production, and yield performances over the years.

## Data Description
The dataset contains the following key features:

- **Crop Name:** The name of the crop.
- **Crop Year:** Year in which the crop data was recorded.
- **Season:** Season in which the crop was cultivated (e.g., Kharif, Rabi, Summer).
- **State and District:** Geographic regions where the crops were grown.
- **Area:** Total cultivated area (in hectares).
- **Production:** Crop production (in metric tonnes).

## Data Cleaning
The data was pre-processed using Python to ensure its integrity and usability. The steps included:

- **Handling Missing Values:** Filled or removed missing entries for key variables.
- **Outlier Detection and Removal:** Identified and removed extreme values that could distort analysis.
- **Data Type Correction:** Ensured all numeric and categorical fields had the appropriate data types.

## Visualizations
The visual analysis was performed using Tableau. The following key dashboards were created to answer several questions related to the agricultural performance of Indian states and agro-climate regions (ACRs):

### 1. Overall Crop Production and Yield Trends
- **Total Production:** Displaying the total production over the years.
- **Total Cultivated Area:** Showing the aggregate cultivated area for all crops.
- **Average Yield:** Yield performance over time and across regions.
- **Production Over the Years:** Trend analysis showing how production and yield changed from 1997 to 2017, displayed for both individual states and districts.

### 2. Agro-Climate Region (ACR) Analysis
- **Crop Production in ACRs:** Shows the contribution of different crops to production in each agro-climate region.
- **CAGR for Production & Yield:** Calculated the CAGR for various crops in different regions, offering insights into their long-term growth rates.
- **Area Comparison Across ACRs:** Visualizing performance across years in relation to different climates.

### 3. District-Level Analysis
- **Production and Yield by Districts:** Detailed dashboard for crop performance at the district level.
- **Major Crops per Season:** Identified top-performing crops for each season and district.

## Key Insights
### State-Level Performance:
- States like Punjab and Uttar Pradesh showed high production levels, with large cultivated areas and yields.
- Some states, such as Kerala, were leading in specific crops like coconut and spices.

### ACR-Level Insights:
- The CAGR for production and yield varied significantly across ACRs. For instance, ACRs in Northern India showed higher growth rates in crop production compared to central and southern regions.
- Some regions showed negative growth for certain crops, indicating areas that may need agricultural interventions.

### Major Contributing Crops:
- Coconut, Rice, and Sugarcane were the highest contributors to overall production across India.
- Crops like Jowar and Bajra showed negative growth, which could indicate reduced popularity or productivity over the years.

### Production and Yield Trends:
- Crop yield has fluctuated significantly over the years, with some regions showing a decline after 2005, potentially due to environmental factors such as droughts or changing agricultural practices.

## Features in Tableau Dashboards
- **Filters:** Users can filter the data by crop, season, and state to explore specific performance metrics.
- **Maps:** Geospatial data visualization enables analysis of crop distribution and performance across India.
- **CAGR Analysis:** Allows users to view the growth rates of different crops and agricultural areas over time.

## File Attachments
Screenshots of the dashboards have been attached to provide a visual summary of the analysis:

- **Overall Crop Production and Yield Trends:** Overview of crop production and yield trends across states.
  
  ![swd](https://github.com/user-attachments/assets/10d0a71c-482a-44b6-a250-766dd77c65a2)

- **ACR's Analysis:** Detailed analysis of crop production and yield across different agro-climate regions.
  
  ![ACR's Analysis](https://github.com/user-attachments/assets/f5e62c4d-9715-4273-a902-a24029a57620)

- **District Analysis:** District-wise analysis showcasing major crops and seasonal performance.
  
  ![111](https://github.com/user-attachments/assets/39e39b16-f280-45d4-b83a-8ee82db57fc2)

## Conclusion
This analysis provides an in-depth look at agricultural productivity across various regions in India, highlighting trends that can guide future agricultural policies and interventions. The integration of Tableau for visualization allows easy exploration of these trends, making it an effective tool for stakeholders in the agricultural sector.
