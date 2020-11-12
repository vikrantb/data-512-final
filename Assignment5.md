# Is COVID affecting some ethnic groups disproportionately?

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

## Research questions and hypothesis
### Research question:
Does being from a certain ethnicity, gender increase your risk of dying with covid?
Does this risk vary based on your education level, employment status and area where you live?

### Hypothesis:
As we encounter the above questions, we will come across multiple scenarios where we will need statistically significant observations. We will use hypothesis testing for those.
Example: Does being a black male from New york area increase your risk by x% compared to if you were from Seattle.

## Background/Related work
There has already been some research and data points shared by CDC which show that there is some evidence of disproportionate death rate across different ethnic groups and gender.
Below is the related CDC website that has links to other resources
https://www.cdc.gov/coronavirus/2019-ncov/community/health-equity/race-ethnicity.html

The below two websites explores this in more details and shows a difference in death rates between various ethnic groups
https://covidtracking.com/race
https://covid.cdc.gov/covid-data-tracker/#demographics

However, the question that these do not answer is - "How do other factors like economic conditions, education and unemployment affect the death rates?"

## Methodology
Below are the few steps that I plan to do

### Data gathering and cleaning
There are few datasets that I mentioned above that are important for my analysis. My first step is to make sure that all the data is collected, cleaned and available to be used for processing.
This also includes finding any common keys that I can use to join by like the county ids etc

### Exploratory data analysis
After I have the data ready, the next step is to do exploratory data analysis on the data.
This includes looking at various charts and doing a quick review to observe and see if there are some obvious patterns.
I also plan to use some animations if required to see if some of the data changes with time.
The next step is to validate the specific research questions that I have already mentioned in the Research questions section.
As I explore the research questions, I may come across various hypothesis that may seem convincing but I want to go a step further and ensure that they are statistically sound and hence I will do some hypothesis testing. 