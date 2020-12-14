# Understanding the effects of COVID on the society in United States

## Motivation
As SARS-CoV-2 is creating havoc in the world and affecting almost every country,the United States is currently the worst affected nation in the world. While it appears that everyone irrespective of their race and economic status is affected by the ill effects of the virus, I was curious to find out if that is true.

There are various different ways by which we can quantify the ill effects of COVID but the most obvious and severe effect is death.

Hence, I decided to study the death rates of COVID across various aspects like demographocs, unemployment, geographical area type and income ranges and observe if there are statistically significant differences in the mean death rates.

Below are the datasets. All of them contain data at county level and all the data is available on public domain.

#### Census data at county level

https://www.census.gov/data/tables/time-series/demo/popest/2010s-counties-detail.html

Click on United States

https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/asrh/cc-est2019-alldata.csv

This contains the demographics information.


#### Economic research data at county level

https://www.ers.usda.gov/data-products/county-level-data-sets/

The above dataset contains poverty and unemployment data. This has been downloaded in the `data/` folder for ease of analysis.

#### Covid deaths data

https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-County-and-Ra/k8wy-p9cg

#### Information of social classes in United States
https://en.wikipedia.org/wiki/Social_class_in_the_United_States#/media/File:Two_or_more_income_earners.png


## Scientific Abstract

### Background
There has already been some research and data points shared by CDC which show that there is some evidence of disproportionate death rate across different ethnic groups and gender. Below is the related CDC website that has links to other resources

https://www.cdc.gov/coronavirus/2019-ncov/community/health-equity/race-ethnicity.html

The below two websites explores this in more details and shows a difference in death rates between various ethnic groups

https://covidtracking.com/race https://covid.cdc.gov/covid-data-tracker/#demographics

Some of the resources explore the topic at a very high level and provide conclusion without enough information for a future scientist to explore. While some provide more simplistic answers without diving deep into the details and studying interactions between different factors.

Hence although the work is interesting to get started, I still feel a lot more needs to be done in this area.

### Purpose

The main purpose of this research is to answer and investigate the below questions

Is the mean death rate of people dying with COVID in United States the same across different geographical area types?

Is the mean death rate of people dying with COVID in United States the same across all income groups?

Is the mean death rate of people dying with COVID in United States the same across all races?

For each of these, we will do some basic EDA and then use relevant statistical tests to come up with conclusion. While answering the above questions, if we find interesting patterns, we will dive deep into each one of them. We might also be interested to study any interactions between these factors.


#### Particular interest/focus of paper

As SARS-CoV-2 is creating havoc in the world and affecting almost every country,the United States is currently the worst affected nation in the world. While it appears that everyone irrespective of their race and economic status is affected by the ill effects of the virus, I was curious to find out if that is true.

There are various different ways by which we can quantify the ill effects of COVID but the most obvious and severe effect is death.


Hence, I decided to study the death rates of COVID across various aspects like demographocs, unemployment, geographical area type and income ranges and observe if there are statistically significant differences in the mean death rates.

Detailed report [here](https://github.com/vikrantb/data-512-final/blob/main/report.ipynb)
