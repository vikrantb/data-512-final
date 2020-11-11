# Is COVID affecting some groups disproportionately?

## Motivation
My main motivation of this project is to find any patterns that raise ethical and fairness questions in covid deaths.

I think this is important because this will help us provide more better facilities to the people who are more needy. This will also allow other interested researchers to dig in deeper and try to see if there are any inherent issues on why these patterns might exist.
We currently do not have an understanding on the way covid deaths are distributed by ethnicity, race, gender, poverty and finally how do they vary based on where you live.
My analysis hopes to present these in greater details. I am planning to do the analysis on county level data.
I also hope to learn more about the data science process like data joining, cleaning and presenting them in the most understandable way.


## Data selected for analysis

There are 3 datasets that I am planning to join to do the analysis

### Census data at county level

#### Dataset uri

https://www.census.gov/data/tables/time-series/demo/popest/2010s-counties-detail.html

Click on United States

https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/counties/asrh/cc-est2019-alldata.csv

I am planning to use the census data by US government at county level. This contains the demographics information.
Below is the way to extract the data


### Economic research data at county level

#### Dataset URI

https://www.ers.usda.gov/data-products/county-level-data-sets/

Specifically, I am going to join with poverty, population and unemployment data

### Covid deaths data

I am planning to join the population, education and unemployment data with the covid deaths at county level.
I may also join it separately or along with the same above join with demographic data.

#### Dataset uri

https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-County-and-Ra/k8wy-p9cg

### License
All the data is available on public domain.

### Why this dataset is useful for ethical considerations?

I would like to join the above datasets and observe patterns and dig more into the details.

This dataset is suitable for my analysis because this is firstly available on public domain and I do not need to worry about copyright issues. Also, this data is at appropriate granularity level. Too high level may not be very useful and too low level maybe difficult to decipher.

Few ethical considerations that I would like to derive from here is to understand and confirm if there is really any racial and ethnic influencing factors in the covid related deaths. If it turns out that there are any patterns, I would like to do more in depth analysis to observe if these patterns are for any specific sub-category. Eg. poverty/population or education.

## Unknowns and dependencies

I have not yet validated the data quality and completeness. That is certainly something to look out for.
I also need to validate if the columns on which to join the data are existing in both datasets otherwise I may miss out on some records in the join.
Some of the population, unemployment and education data is available till year 2019. However, since these factors dont change drastically so often, I feel this will not be a blocking issue.
