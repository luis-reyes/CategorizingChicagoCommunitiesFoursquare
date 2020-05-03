# Categorizing Chicago Communities using Crime Data and Foursquare

## Table of contents
* [Introduction / Business Problem](#introduction)
* [Data](#data)
* [Methodology](#methodology)
* [Analysis](#analysis)
* [Results and Discussion](#results)
* [Conclusion](#conclusion)

## Introduction / Business Problem <a name="introduction"></a>

The objective of this project is to obtain the safest communities taking into account the crime rate. The result of this study is aimed at those interested in living in the city of Chicago.

Chicago is one of the largest cities of the united states with a population of over 2 and a half million people. Chicago has 77 communities grouped into 9 districts.  The city has reported more than 7 million crimes of every category since 2001, 259 thousand just in 2019.  Business Problem  We will deal with the decision of “Which community has had the least crimes in 2019”, finding the right community to move into or beginning a business entrepreneurship based on the security and venue(residence) density in each community. 
 
## Data <a name="data"></a>

Our study will be based on the data extracted from:
 * Crime Data(using the datasets provided by <a target='new' href='https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present-Dashboard/5cd6-ry5g'>the city of chicago</a>)
 * Community information(scraped from <a target='new' href='https://en.wikipedia.org/wiki/Community_areas_in_Chicago'>this wikipedia page</a>)
 	* Using geopy to get each coordinate
 * Foursquare api to explore residences near our communities
 
**The study will be made using 2019 data**.
 