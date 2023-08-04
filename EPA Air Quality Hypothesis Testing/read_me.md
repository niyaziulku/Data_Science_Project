# EPA Air Quality Hypothesis Testing
![](https://mlawiy0je0ms.i.optimole.com/206F41w.2d6g.2d53d/w:1024/h:576/q:auto/https://www.planetwatch.io/wp-content/uploads/2022/08/Air-pollution.jpg)
Working for fictional environmental think tank called Repair Our Air (ROA) which is formulating policy recommendations to improve the air quality in America, using the Environmental Protection Agency's Air Quality Index (AQI) to guide the decision making. 
In this data science project, we have been tasked with leveraging AQI data to help them determine their strategy for the following questions:

- Whether a metropolitan strategy shall be applied all over California or there is a meaningful difference between Los Angeles and the rest of California in terms of pollution?
- As a next regional office, is New York a better choice than Ohio in terms of pollution?
- A policy will be implemented all over the states having a mean AQI equal or more than 10 parts per million, whether Michigan should be among those states or not?

## About the Dataset
The dataset "c4_epa_air_quality.csv" contains air quality readings for various counties in the United States. It includes 260 rows and 10 columns, with information on AQI readings, date, state, county, city, and pollutant parameters. 
An AQI value close to 0 signals "little to no" public health concern, while higher values are associated with increased risk to public health.

## Goal
The objective of the project is to help the environmental think tank, Repair Our Air (ROA), prioritize their strategy in different part of United States by considering the air quality data and comparing the means of various state-level pollution metrics to make a decision.

## Methodology
Hypothesis testing is conducted to analyze key research questions. For each test, the null and alternative hypotheses are formulated, and a 5% significance level is set.
For comparison of two samples, two samples t-test (stats.ttest_ind), and for comparison of one sample with a specified value, one sample t-test (stats.ttest_1samp) is used to compare means of different groups.
The p-value is calculated to determine the statistical significance of the results.

## Significance
The project is important to demonstrate whether even with small sample sizes, the variation within the data allows for statistically significant conclusions or not.
The insights revealed from the hypothesis tests will guide ROA's decisions regarding a metropolitan strategy to be followed in California, the next regional office of ROA and whether an across-state level policy should be implemented in a specific state or not.