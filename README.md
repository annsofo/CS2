# CS2: Significance of Tree Density in NYC
*CS2 Assignment for DS 4002, Spring '23*

## Contents

This repo includes all necessary materials to complete the assignment, 'Signifiance of Tree Density in NYC'. They are linked below:

1. [Introducion](./Hook%20document.pdf)
2. [Rubric](./Rubric.pdf)
3. [Data](./treeDensity_data.csv)

## Data Dictionary

This data is a result of merging data from the U.S. Census Bureau and NYC Open Data

| Variable Name | Source/Description |
| --- | --- |
| Total population | From the Kaggle NYC Census dataset |
| Income per capita | From the Kaggle NYC Census dataset |
| Unemployment rate | From the Kaggle NYC Census dataset |
| Poverty rate | From the Kaggle NYC Census dataset |
| Percentage of Professional Occupation | From the Kaggle NYC Census dataset |
| Percentage of population that walks to work (Walk) | From the Kaggle NYC Census dataset |
| Mean commute time (MeanCommute) | From the Kaggle NYC Census dataset |
| Percentage Age Above 65 | From Decennial Census data at data.census.gov: P16 POPULATION IN HOUSEHOLDS BY AGE |
| Percentage Age Below 18 | From Decennial Census data at data.census.gov: P16 POPULATION IN HOUSEHOLDS BY AGE |
| Percentage Renter Occupied Houses | From Decennial Census data at data.census.gov |
| Population Density | Total population over census tract area square miles |
| Census Tract Area Square Miles | From NYC Open Data Census Tracts Geometry Files |
| Percentage with Bachelor’s Degree and Up for 25+ Year Olds | From Decennial Census data at data.census.gov: DP2 SELECTED SOCIAL CHARACTERISTICS |
| Percentage without High School Degree for 25+ Year Olds | From Decennial Census data at data.census.gov: DP2 SELECTED SOCIAL CHARACTERISTICS |
| Mean Household Size | From Decennial Census data at data.census.gov: PCT008 AVERAGE HOUSEHOLD SIZE |
| Tree density | Trees per square mile of each census tract, found on NYC Open Data |



## Sources 

### Model Building
- [Classification Tree Model](https://bookdown.org/jhvdz1/ml2/classification-decision-trees.html)
- [Additional Code with Gini Index/Variable Importance](https://rstudio-pubs-static.s3.amazonaws.com/108298_75e23efda7f845f98af2c549a26b5958.html)

### Project Context
- [NYC Parks: MillionTreesNYC](https://www.nycgovparks.org/trees/milliontreesnyc)
- [NYT Article on tree density disparities](https://www.nytimes.com/interactive/2021/06/30/opinion/environmental-inequity-trees-critical-infrastructure.html)
- [Existing Project on socioeconomic and spatial inequalities of street tree abundance](https://www.sciencedirect.com/science/article/abs/pii/S0169204620314766)
