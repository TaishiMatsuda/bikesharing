# Bike-Sharing Program in Des Moines
(Module 14 of UofT Data Analytics Boot Camp)

## Overview
Shared Mobility is one of the fastest growing industry in the United States with over 84 Million trips in 2018 [*1]. Citi Bike is the most successful bike share program based in New York City, however, there are multiples states or cities with the business opportunities including Des Moines, Iowa. 

#### Objective
* Conducte the data analytics of Citi Bike Data to find the key success factors of bike share program
* Provide business plan of bike share program in Des Moines (DM) based on the findings

#### Visualization
Please visit Tableau public for the visualization of the data analysis.
https://public.tableau.com/profile/taishi.matsuda#!/vizhome/BikeSharing_15909395256870/NYCCitiBikeAnalysis

## Analysis of Citi Bike
#### Is Large Population a key to Success?
Although the population of Des Moines is only few percent of New York City (214 thousands vs 8.3 million)[*2], the population is not the primary success factor of bike share program. It is more important to build the right size of stations and bikes that appropriately meets the demands.

* There are 152,181 annual subscribers to the Citi Bike [*2], which is less than 2% of the NYC population [*3].
* Multiple cities similar in size to Des Moines has successfully developed the bike share programs [*4].
* Large population country like China ended up creating bike share graveyard [*5].

#### Who uses Citi Bike? Who to target in Des Moines?
The target market of the shared bike in DM will be the male who takes short trips to their workplace.

* Majority of trips were by subscribers (= Annual Members).
* Male user takes approx. 3 quarters of total rides.
* Slight decrease of trips by subscribers during weekend indicating main purpose is commuting.
* Based on commuting charasteristics by sex prodived by Census [*6,7], the breakdown of transports by male and female are about half and half in both NYC and DM.
* Although use of own vehicle is the main way of commuting in DM, 30% of total trips are takes less than 15 minutes (55% takes less than 20 minutes). Many of these trips could potentially be replaced by the bikes.

#### Where should stations be located?
Usage by location in NYC suggests that bike share stations should be located near major stations of the transportation network. Collaboration with D-Line shuttles and Des Moines Area Resional Transit is essential for successful implementation of the bike share program in DM.

* The busiest Citi Bike stations are located near the major subway stations of NYC.
* Start and end points indicate people commuting uses bike share as a transit between subway stations in NYC.

#### Will people use bike share during winter?
Although decrease in the trips are expected, the Citi Bike data and the weather data [*8] suggests that there would still be sufficient demands during winter in DM.

* In December 2019, close to 1 million trips were made in NYC.
* Temperature in DM is slightly lower than that of NY.
* However the average precipitation in DM during winter is significantly lower than that of NYC, indicating better conditions for riding bike.

## Reference
1. Shared Micromobility in the U.S. 2018, NACTO, <https://nacto.org/shared-micromobility-2018/>
2. Citi Bike Data, <https://www.citibikenyc.com/system-data>
3. QuickFacts - New York city, New York; Des Moines city, Iowa, United States Census, <https://www.census.gov/quickfacts/fact/table/newyorkcitynewyork,desmoinescityiowa/PST045219>
4. Bike Share Finds Success in Small Cities, momentum magazine, <https://momentummag.com/bike-share-finds-success-in-small-cities/>
5. How China's Unicorn Shook a Bicycle Town, The New York Times, <https://www.nytimes.com/2019/04/27/business/china-bike-sharing-unicorns.html>
6. COMMUTING CHARACTERISTICS BY SEX - Des Moines, United States Census, <https://data.census.gov/cedsci/table?q=Des%20Moines&g=1600000US1921000&tid=ACSST1Y2018.S0801&layer=VT_2018_160_00_PY_D1&vintage=2018>
7. COMMUTING CHARACTERISTICS BY SEX - New York City, United States Census, <https://data.census.gov/cedsci/table?q=New%20York%20City%20Commuting&g=1600000US3651000&tid=ACSST1Y2018.S0801&t=Commuting>
8. Daily Weather Data, National Centers for Environmental Information, <https://www.ncdc.noaa.gov/>