# COVID-19 Data Analysis
 Worked with COVID19 dataset, published by John Hopkins University, which consist of the data related to cumulative number of confirmed cases, per day, in each Country. 
 Also used another dataset consist of various life factors, scored by the people living in each country around the globe. 
## Task :
Analysis of these two datasets to see if there is any relationship between the spread of the virus in a country and how happy people are, living in that country.

### Divided into following Section:
#### Section 1: 
Visualization of data for India, China & US countries using COVID19 dataset & Python Libraries

#### Section 2: Finding a good Measure - 
Calculated the maximum ‘Infection Rate’ for each country and stored it in a new column named ‘max_infection_rate’.
Created a New Data Frame named ‘Corona Data’ with ‘Country/Region’ as an index and ‘max_infection_rate’ as a column.

#### Section 3: World happiness report dataset -
Created a DataFrame named ‘data’ by merging ‘happiness_report’ with ‘Corona Data’ and found correlation among all variables.

#### Section 4: Visualization using Folium Map 
#### Section5: Visualization of results using Seaborn - 
  GDP vs maximum Infection rate
  Social support vs maximum Infection rate
  Healthy life expectancy vs maximum Infection rate
  Freedom to make life choices vs maximum Infection rate
