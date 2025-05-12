Cardiovascular Risks in America: A Data- Driven Analysis of Risk Clusters of the Disease Prevalence. 
##Summary
This preliminary analysis explores the prevalence of three major cardiovascular risk factors; high blood pressure, diagnosed diabetes and coronary heart 
disease using the 2024 CDC PLACES dataset and the U.S Department of Agriculture’s Economic Research Service Median Household Income dataset to measure 
household income correlation. Cardiovascular disease remains the leading cause of death in the United States, and these three conditions contribute significantly 
to long-term morbidity and mortality. Understanding their geographic distribution can help the US National Cardiovascular Society identify priority areas for 
prevention and intervention. Analyzing available data, we have identified national hotspots and conducted a cross-statistical analysis with States where the 
burden is highest and lowest. The key findings indicate a strong overlap of risk in the rural areas of the Southeast States counties with low household income 
that suggest inaccessibility to preventative care. Our finding lays the foundation for deeper state to even county specific investigation and confident that 
this analysis supports the Society’s ongoing effort to help address cardiovascular disease and health disparities.

##Data and Methods
##Data Source
The data set used for this analysis came from the Center for Disease Control and Prevention 2024 CDC PLACES dataset and the U.S Department of Agriculture’s 
Economic Research Service Median Household Income dataset. This publicly available dataset provides a wide range of model-based estimates.  
This analysis focuses on three key selected variables from the dataset as see bub the table below, that includes the prevalence of high blood pressure, 
diagnosed diabetics and coronary heart disease among adults at the county level.

Category	Measure
Health Outcomes	Coronary heart disease among adults
Health Outcomes	Diagnosed diabetes among adults
Health Outcomes	High blood pressure among adults

These selected variables can be identified within the dataset which has Health Category and Measures variable at county level across 50 states and the 
District of Columbia. The U.S Department of Agriculture’s Economic Research Service Median Household Income dataset provides median household income 
for which the year 2022 was used in this analysis.

##Methods
For this report, a comprehensive analytical approach was used to uncover spatial and statistical patterns in cardiovascular health outcomes across U.S. 
counties. Data cleaning in R and ensuring data quality served as the foundational step, ensuring the dataset was standardized and structured for 
accurate analysis. This was followed by prevalence mapping and clustering, which visualized geographic hotspots and grouped counties based on similar 
disease burden profiles. Finally, a correlation matrix and co-prevalence detection were conducted to identify statistically significant associations 
among chronic conditions in a State with the highest prevalence to the lowest. Highlighting regions with overlapping health vulnerabilities was key to 
share public health approaches recommendations. 

##Requirements
R Packages: dplyr, tidyr, stringr, readr, ggplot2, sf, tigris, scales, ggrepel, readxl

See word document for full report "CardiovascularDisease_FinalProject_boljuan"


