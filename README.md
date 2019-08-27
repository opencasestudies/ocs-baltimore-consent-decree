# OpenCaseStudies

This case study is part of the [OpenCaseStudies]() project. This work is licensed under the Creative Commons Attribution-NonCommercial 3.0 ([CC BY-NC 3.0](https://creativecommons.org/licenses/by-nc/3.0/us/)) United States License.


### Title

The Effect of the Consent Decree on Arrest Rates in Baltimore

### Motivating question

Did the approval of the consent decree have an effect on arrest rates or arrest rate disparities between Black and White people in Baltimore?

### Data

Arrest records (last updated March 1, 2019) used in this analysis were originated from [Open Baltimore](https://drive.google.com/file/d/1_vxZb5m3C6UvxUtiwArbePkj5qU4k4cJ/view), a [web portal](https://data.baltimorecity.gov/) where the city's publishable data is made publicly available, and can be found [here](https://data.baltimorecity.gov/Public-Safety/BPD-Arrests/3i3v-ibrt).

American Community Survey data (2013-2017) for Baltimore City was obtained for its [Black](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_17_5YR_B01001B&prodType=table) and [White](https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_17_5YR_B01001A&prodType=table) populations. The two datasets used provided population counts by sex and age group. 

### Analysis

A poisson regression analysis is conducted. An offset is used to convert count data into rates. 

### Other notes and resources

This project is in development. Also: let us try to explain why we chose the packages we will be using before using them. This will help students know when to "come back" to a particular package. For example: dplyr, for data wrangling and summarization. 