# Flu Risk Forecasting


## Overview

A medical staffing agency that supplies temporary personnel to clinics and hospitals across the United States is preparing for the upcoming 2018/19 influenza season. This analysis supports planning efforts by identifying high-risk population groups using age, examining seasonal trends, and developing a state-level risk profile to help determine when, where, and how many staff may be needed.


## Key Questions

1. Which age groups are most affected by influenza?
2. Is there a relationship between population size and influenza-related deaths?
3. When does influenza season typically start and end?
4. How does the severity of influenza vary from year to year?
5. Which states are most at risk?
6. Based on risk, when, where, and how many staff should be deployed?


## Tools Used 

- **Excel** - Data Preparation | Analysis
- **Word** - Reporting
- **Tableau** - Visualisation | Forecasting | Storytelling


## Skills Demonstrated

- Project Research | Design | Planning
- Data Exploration | Description | Profiling | Cleaning | Transformation & Integration
- Descriptive Statistics | Statistical Analysis | Hypothesis Testing | Trend Analysis | Seasonal Forecasting
- Deriving Insights | Data Visualisation | Reporting | Storytelling


## Data Sourced

This analysis uses publicly available data sourced from the **Centres for Disease Control and Prevention (CDC)** and the **US Census Bureau** that cover the period 2009 to 2017. The data was provided by **CareerFoundry** as part of their Data Analytics Course.

- [**Influenza-related deaths**](https://coach-courses-us.s3.amazonaws.com/public/courses/da_program/CDC_Influenza_Deaths_edited.xlsx) - Number of deaths by location, time, and age.
- [**Population**](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A1-A2_Influenza_Project/Census_Population_transformed_202101.csv) - Number of people by location, time, age, and gender.


## Deliverables

- **Interim Report** *(link to be added)*
- [**Interactive Tableau Storyboard**](https://public.tableau.com/views/MedicalStaffingPlan_17430147849920/Story1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- [**Detailled Case Study**](https://davidgriesel.com/data-analysis-informing-medical-staffing-plan/)


## Key Insights


### Vulnerable Populations - Who?
Adults aged 65 and older account for the vast majority of influenza-related deaths and display the greatest variation in mortality.

<table>
<tr>
<td align="center" width="33%">
  <img src="visuals/pie-deaths-agepng.png" ><br>
  <em>Adults aged 65 and older account for more than 60% of all influenza-related deaths — a trend that reinforces CDC classifications of this group as high risk.</em>
</td>
<td align="center" width="33%">
  <img src="visuals/box-age-group.png" ><br>
  <em>The 65+ age group shows a significantly wider spread and the highest median number of deaths, reflecting both elevated mortality and greater variation compared to younger age groups.</em>
</td>
</tr>
</table>


### Seasonality – When?
Although the annual severity of influenza varied considerably, peak mortality consistently occurred in January, with Southern states often reporting the highest totals — though vulnerable states were not limited to that region.

<table>
<tr>
<td align="center" width="50%">
    <img src="visuals/line-region-yearly.png" ><br>
    <em>Influenza deaths rise in November, peak sharply in January, and decline through April. The South shows a notably higher average peak compared to other regions.*/em>
</td>
<td align="center" width="50%">
    <img src="visuals/bar-deaths-year.png" ><br>
    <em>Influenza-related deaths vary from year to year, with notable surges in 2013 and 2015. The average annual death count across the period is 73,158 confirming that while flu season is consistent in timing each year, its severity can fluctuate.</em>
</td>
</tr>
</table>


### Risk Classification & Forecasting – Where & How Many?
States were classified into high, medium, and low risk based on their elderly populations, guiding an effective resource allocation framework.

<table>
<tr>
<td align="center" width="50%">
  <img src="visuals/map-vulnerable.png" ><br>
  <em>Geospatial view confirms that high-risk populations are not confined to the South — with large vulnerable populations in California, the Northeast, and parts of the Midwest.</em>
</td>
<td align="center" width="50%">
  <img src="visuals/bar-risk-population.png" ><br>
  <em>Shows the 65+ population across U.S. states grouped into High, Medium, and Low risk profiles.</em>
</td>
</tr>
</table>

</table>
<td align="center" width="50%">
  <img src="visuals/line-risk-forecast.png" <br>
  <em>Forecasted deaths for 2018 reveal sharp seasonal peaks in high-risk states, confirming the elevated burden in these areas. Low-risk states show minimal fluctuation, indicating a reduced need for additional staff.</em>
</td>
<td width="50%"></td> 
</tr>
</table>
