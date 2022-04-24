# Index of Economic Freedom

## Overview
* As we are in the election period, a group of businessmen hired the Heritage Foundation company to identify whether and how much the integrity of a government can impact the judicial effectiveness of a country.
* For twenty-eight years, the Heritage Foundation has delivered, through the Index of Economic Freedom, thoughtful analysis in a clear, friendly, and straight-forward format. The index is measured based on 12 quantitative and qualitative factors, grouped into four broad categories as follows:
 - Rule of Law (property rights, **government integrity**, **judicial effectiveness**)
 - Government Size (government spending, tax burden, fiscal health)
 - Regulatory Efficiency (business freedom, labor freedom, monetary freedom)
 - Open Markets (trade freedom, investment freedom, financial freedom)

* Each of the twelve factors is graded on a scale of 0 to 100. A country’s overall score is derived by averaging these factors, with equal weight being given to each. The closer to 100, the more economic freedom the country is, or the closer to 0, the more repressed the country is. 

* My analysis initiates with the hypothesis that the higher is the **Government Integrity**, the higher will be the **Judicial Effectiveness**. 


## Objective
* As a Data Analyst from the Heritage Foundation, I have been asked to uncover insights of whether and how much the **Government Integrity** impacts the **Judicial Effectiveness** of a country. The result of my analysis will compose the research program that will inform the population of the importance of voting for candidates with integrity and commitment to their country. 

## Analysis Process and Dataset
*Analysis Process
 - Started the project installing and importing the needed Python libraries. 
 - From “All Index Data” menu, I selected data from all countries and regions from 1995 to 2022. Downloaded the data by region and grouped the csv files in one using Python. 
 - Found latitude and longitude and assigned to each country to further explore the scores in the map. Then, explored the dataset, counted data, checked duplicates, analyzed the missing values, performed descriptive analysis, wrangled the data and confirmed that the data was prepared for visualization in Tableau. 

*Datasets
 - Citation: “2022 Index of Economic Freedom”, accessed from https://www.heritage.org/index/  on 10th of March 2022.
Reference Period: The data presented in a determined year  (e.g., 2022) covers the second half of two years ago (e.g., 2020) and the first half of one year ago (e.g., 2021).
 - **Datasets:**  


## Challenges and Decisions

#### Finding Latitude and Longitude data
* The challenge was to identify data with quality for geo-localization (latitude and longitude) and group them into my dataset for the all countries. 
* To resolve that, I investigated and found an add-ons extension (“Geocode”) from Google Sheets that generates automatically geo-localization for all countries that I needed. Then, created an additional table to associate the geo-localization to each country.

#### Grouping Regions into my Dataset
* The challenge was to download, map and associate the "Region" to each country. 
* To resolve that, I went the the "Explore the Data" section in the Heritage Foundation, accessed "All Index Data", downloaded the data individually for each region from 1995 to 2022. Then, created a table to correlate the region for each country, then associated to my full dataset.


## Tools & Analytical Techniques
*Problem Solving
* Investigated factors that could support the businessmen to inform the population about what impact the Government Integrity and Judicial Effectiveness of a country.

*Storytelling
* Produced the story based on the project objective. Then planned the key story points, the message behind them and the visuals to support.

*Exploratory Analysis
* This technique was my main guideline to conduct the analysis related to the project objective. I started looking for the linear relationships between all the 12 variables, then noticed the strongest relationship between the Government Integrity and the Judicial Effectiveness with an upward trend, meaning that the higher the government integrity, the higher was the judicial effectiveness of a country. I could also notice that for a group of countries with lower scores, the relationship was not so strong as the higher scores. What makes me to conduct a cluster analysis.


**[Python scripts (.ipynb)](https://drive.google.com/file/d/1nfFrlsGLkpVGfkTMFQSUUqVeByiLgfSR/view?usp=sharing)**


## Retrospective
*What went well
* The Index of Economic Freedom data has quality, the methodology and data dictionary are also provided. The data and information in general are of high quality.

*Lessons Learnt
* It is important to take a moment to reflect and discuss a lot about the project objective, the hypothesis and the measurement objective and keep the focus on identifying the key variables that will respond their objectives. It is easy to waste time analyzing useless data and losing focus on the purpose of the project, especially when there are too many variables to analyze. For the next project, I will create a relationship matrix correlating the measurement objective with the candidate variables.

*Areas of Improvement
* Define clearly the business case in order to map as soon as possible the candidate variables for the analysis. 


## Results and Recommendations
*Results
* The USA and Canada scores higher in the Americas. They are also the richest and most developed countries in this region. The USA has its legislation enacted in 1789 and Canada in 1867. Clearly their democracy is well stablished what results in high government integrity and judicial effectiveness.

﻿Europe is the region where concentrates the higher number of  developed countries with the higher scores.

﻿Australia and New Zealand scores higher in Asia and the Pacific, consequently, they are the most developed and richer countries in the region. 

*Recommendations
* Analyze the impact of additional variables, including the gross domestic product per capita, on the Government Integrity and the Judicial Effectiveness.

* Investigate other factors that make a country be developed and rich.

* Inform the business men and the population that the Government Integrity impact directly the Judicial Effectiveness of a country. 

Tableau – click **HERE** (https://public.tableau.com/app/profile/cleber.juliano.f/viz/IndexofEconomicFreedom_16507221580520/Story1?publish=yes) to access the Storyboard
