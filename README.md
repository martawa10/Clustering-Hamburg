# FINAL_PROJECT

## Summary
The aim of this project is to examined city of Hamburg and explore venues around metro stations. After gathering all nassesery data we take a look on different neighborhoods. Data has been devided using K-means clustering into four clusters. Two of clusters are more common and two are unique. However, when it comes to the most common categories of venues, all the clusters look similar to each other, indicating that Hamburg is quite homogeneous in terms of available venue categories.

## 1. Introduction
The Hamburg U-Bahn is a rapid transit system serving the cities of Hamburg, Norderstedt and Ahrensburg in Germany. Although technically an underground, most of the system's track length is above ground. The network is interconnected with the city's S-Bahn system, which also has underground sections. With Metro System is easier and faster to get to other parts of the city. Many people looks for their flats situated next to metro. At the same time they want to live close to shops, restaurants, coffeshops or parks.

The company specializing in long-term as well as short-term aparments renting wants to obtain deeper knowlage about city to build housing recommendation system based on clients preferences. There is a lot of recommendation systems on the market now, but while doing reaserch on Germany market we found out that there is none designed for meeting all needs in one place. People looking for housing needs to search among lots of websites to gain information they need. Different people can have their specific preferences such as favourite stores, shopping location etc. In my project I want to analyze different neighboorhoods of Hamburg which will help to build final recommendation system in the future.

## 2. Data
For the project its needed to obtain:

geo-locational information about metro stations in Hamburg - latitude and longitude of every station. Informations will be obtain based on names of stations. Data will be scrapped from wikipedia page: https://en.wikipedia.org/wiki/List_of_Hamburg_U-Bahn_stations and geo-location information will be added using geopy library.
Forsqure API will be used to find location information about venues. Explore function will be used to get the most common venues categories next to each metro station like restaurants, art galeries, shops.
After collecting data some visualization and statystical analysis will be made. Location of stations will be shown on map prepered with folium library. As the next step this data will help to group metro neighborhoods in clusters. Thanks to collected data we will be able to compare neighborhoods and find differences between them which will help rental company to personalize they offer.

## 3. Results
During the analysis, several important statistical features of the boroughs were explored and visualized. Becasue of not so big data set we have 4 clusters. We can see that some clusters are more common and some are unique. We can see differences from areas closer to city center and other districts - in city center we can find bigger variety of different categories. However, all the clusters look similar to each other, indicating that Hamburg is quite homogeneous in terms of available venue categories.

## 4. Discussion
During analysis of project data I had observation which can be base for futher development.

Like in lots of analytical problems we have to made some assumptions and simplifications to understand and present solution in a better way.Analysis was performed on limited data. If more data would be avaliable our results could be more detailt. If data about prices in different neighborhoods would be provided we could already make some recommendation. For now we can just assume that centrum of the city is more expensive because of a lot of different businesses around. In center of the city we have more more choice and variety of venues.

Forsquere is a good sourse of data, but to performe more detailt analysis we need premium account.

## 5. Conclusion
Although all of the goals of the project were met there is still a huge potential to improve this reaserch. As a next step its possible to develope recommendation system which will help people to get accomodation they dream about.
