# Global Suicide Analysis


## Table of contents
* [General Info](#general-info)
* [Motivation](#motivation)
* [Technologies](#technologies-used)
* [Data Sources](#the-data)
* [Data Questions](#data-questions)
* [The Process](#the-process)
* [Cleaning Data](#cleaning-data)
* [Link To Dashboard](#link-to-dashboard)



## General Info
For my capstone project I’d like to find global suicide rates per country and see if they have gone up or down within the past 15 years? 
Are suicide rates climbing or falling in various countries? I would also like to see if there is a correlation between a number of
factors including year, genre, age, population, and health care expenditure.

## Motivation
More than 700,000 people die due to suicides every year. For every suicide there are many more people who attempt suicide.
A prior suicide attempt is the single most important risk factor for suicide in the general population.


If we could get more mental healthcare around the world, we could help stop the suicide crisis in the world!

## Technologies Used

### Python
-	Jupyter Notebooks
-	Pandas
-	Numpy
-	Webscraping and Beautiful Soup
-	Data Cleaning
-	Analysis

### Excel
-	Pivot Tables
-	Filtering
-	Cleaning Data
-	Coverting .txt to .csv

### Tableau
-	Graph and Chart Creation
-	Dashboard
-	Tableau Story

## The Data


Data.UN.gov: **[GDP](https://data.un.org/Data.aspx?q=gdp+per+capita&d=SNAAMA&f=grID%3a101%3bcurrID%3aUSD%3bpcFlag%3a1)** <br>
Data.UN.gov: **[Population, Growth, Mortality](https://data.un.org/_Docs/SYB/CSV/SYB65_246_202209_Population%20Growth,%20Fertility%20and%20Mortality%20Indicators.csv)** <br>
Wikipedia: **[Countries By Suicide Rate](https://en.wikipedia.org/wiki/List_of_countries_by_suicide_rate)**<br>
Wikipedia: **[Countries By Life Expectancy](https://en.wikipedia.org/wiki/List_of_countries_by_life_expectancy)**<br>
Who.int: **[Deaths by Sex and Age Group](https://platform.who.int/mortality/themes/theme-details/topics/indicator-groups/indicator-group-details/MDB/self-inflicted-injuries)**<br>
Who.int: **[Suicide rates per country per 100K](https://www.who.int/data/gho/data/themes/mental-health/suicide-rates)**<br>
Gapminder.org/Data./:  **[2019 Yearly Data on Suicide Rates By Age](https://www.gapminder.org/data/)**<br>


## Data Questions

Are suicide rates climbing or falling in various countries?

Is a correlation between a number of factors including, year, genre, age, and population?

What countries have the highest suicide rankings in the world and what are the correlation factors between them?

My streatch goal question I'd like to answer is why do some of the  "World's Happiest Countries" have higher suicide rates? What makes a Happy country?


## The Process
Collect all data from WHO.int, Data.un.org, and Gapminder.org.

From WHO, Data.UN.org, and Gapminder I collected over 15 files to clean and use for data.

Webscrape wikipedia using python and Beautiful soup. Collected over 6 csv's to clean and use for data


##  Cleaning Data

### Python
-  Not all country names matched, corrected names between the three data sets.
-  Dropped extra columns I did not need.
-  Deleted years that were unusable.
-  Merged 5 data frames to create one continous dataframe to show 5 years of Happiness Index Ranking.
-  Loading data into Tableau, building dashboards-
-  Move all data into Tableau and built maps and relevent charts to show data according to process.
-  Cleaned columns that had brackets around ages on multiple rows of a file.

### Excel
-  Removed extra rows above data and header row in .csv files from data.un



## Link To Dashboard
- Link Pending 
