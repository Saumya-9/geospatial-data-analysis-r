# Linear Regression Analysis
Tools: R, RStudio, tidyverse, tidycensus, sf, tmap

Methods: Linear Regression, Multiple Regression, Spatial Analysis, Data Visualization

## Project Overview:
This project examines the relationship between demographic characteristics and education and healthcare employment across North Carolina using 2020 American Community Survey (ACS) data. By comparing county-level and census tract-level data, the analysis explores how geographic scale influences statistical relationships and model performance.

## Research Questions:
How is the population aged 65 and older associated with education and healthcare employment?
Do these relationships differ between counties and census tracts?
Does including undergraduate enrollment and median home value improve model performance?

## Methodology:
Using R and the tidycensus package, I collected demographic and employment data from the U.S. Census Bureau. I developed linear regression models to examine the relationship between elderly population and education and healthcare employment at both county and census tract levels. I then built a multiple regression model incorporating undergraduate enrollment and median home value. Scatterplots and spatial residual maps were used to visualize relationships and evaluate geographic patterns in prediction errors.

## Key Findings:

Geographic scale matters: The county-level model explained approximately 93% of variation in employment, compared with 12.3% at the census tract level.

Additional variables improved performance: Including undergraduate enrollment and median home value increased the census tract model's adjusted R² from 0.1233 to 0.2315.

Demographic relationships: Elderly population was positively associated with education and healthcare employment across both geographic scales.
Spatial variation: Residual maps revealed geographic differences in model prediction errors.

## Skills Demonstrated:
Collecting and preparing Census data using R
Building and interpreting linear regression models
Evaluating statistical significance and model performance
Creating geospatial visualizations and residual maps
Communicating quantitative findings

## Project Files:

Assignment8.Rmd — R Markdown source code and analysis

Assignment8.html — Complete report with statistical outputs and visualizations
## Limitations:

Because the analysis uses population counts, differences in geographic population size may influence the observed relationships. The results demonstrate statistical associations rather than causal effects.

## View the Full Analysis

[View the completed analysis and visualizations](Assignment8.html)
