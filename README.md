# Exploratory-Data-Analysis-in-R
Exploratory Data Analysis of NYC Airbnb Data via R
## Project Background 
The project involved analyzing data on Airbnb listings in New York City using R programming. The data contains information about Airbnb listings in the five burrows of New York, namely Queens, Manhattan, Brooklyn, Bronx and Staten Island. The data includes information such as listings id, neighbourhood group, price, reviews and many more. The project focuses on the neighbourhood_group, price, number_of_reviews, and room_type. The project's goal is to identify outliers in the data, determine the relationship between prices and reviews, and the most price Airbnb listings and in which burrows (neighbourhood_group).
## Dataset information
Source: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data
## Tools and Methodology
* R programming
## Executive Summary
This project is an exploratory data analysis (EDA) that examines the various Airbnb listings in New York City (NYC) by utilizing the tidyverse for data cleaning and ggplot 2 for visualization. From the analysis, Manhattan and Brooklyn have the most bnb listings with varied pricing structures. The analysis forms a foundation for implementing a predictive housing and pricing model in NYC to guide the entry of new Airbnb owners into the market. 
### Business Problem
The purpose of this analysis is answering three core questions:
* Market Distribution: Where is the highest density of airbnb listings? How are they distributed per neighborhood?
* Pricing Strategy: What factors influence the pricing of Airbnb listings?
* Host Dynamics: How do hosts with multiple airbnb listings manage their properties in comparison to hosts with single listings?
### Overview of Findings
#### Airbnb concentration and pricing 
Manhattan and Brooklyn have the most Airbnb listings. Manhattan, however, has bnbs with a higher median price than the rest of the boroughs. Manhattan has the highest count of listings priced above $1,000 and $5,000. Brooklyn seconds Manhattan in the volume of luxury listings while the Bronx and Staten Island have the least listings of high-end airbnbs. 
The "L" shaped terend of the scatterplot reveals listings below $2500 as the most reviewed airbnbs. There is also an inverse correlation between reviews and prices of listings since when prices reach $10,000, reviews significantly decrease, showing that luxury listings receive less turnover or booking rate compared to listings below that price.
#### Room Type
The most lucrative listing are "Entire home/apt" listings. However, "shared rooms" represent a negligible part of the market as most clients do not prefer them, which shows strong consumer preference for provacy in New Yock City.

## Recommendations
Investors should focus on the listings of "Private Rooms" in boroughs like Queens or the Bronx since there is less competition and a favorable price-to-acquisition ratio in comparison to Manhattan. On the other hand, hosts should ensure they maintain high availablity scores for listings under the "Entire Home" category for better competition. The data depicts that "Pro" hosts dominate this category, which should not be the case for healthier competition. 
## Caveats and Assumptions
#### Data Currency
The analysis uses a snapshot of New York City's dataset that keeps changing with time, especially due to the influence of local legislation, like Local Law 18, which might significantly impact the number of legal listings. 
#### Price vs Revenue
The "price" variable of the analysis is just a representation of the nightly rate when the data was collected. It does not depict the actual realized revenue since factors like booking and occupancy rate are not entirely captured.
#### Outliers
Some data outliers such as listings above $1000 and $5000 were filtered out to prevent distorting some of the plots and maintain clarity of data visualization. 



