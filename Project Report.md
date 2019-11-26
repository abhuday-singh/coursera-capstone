# Battle of Neighborhood- A Capstone Project

## Business Problem
For candidates who want to pursue their higher education abroad can apply for a university of their choice but to find a decent housing of rental basis or a good neighbourhood can be tricky. Same applies for a family migrating to some other country because of a job change or relocation it becomes important for them to look for a neighbourhood that is decent in price and has most of the facilities as required plus has good schools and colleges nearby them so as to continue the education of their children.<br>So to address this problem we predictthe solution to create an analysis of features of neighbourhood cities in astate of Canada between Neighborhoods. The features include School ratings,median Housing price, weather conditions, crime rate etc. This will helpstudents to figure out which country to choose, which universities to plan, whatwill the approx budget before going to that place where they are gonna starttheir new life.
<br>
The aim of the project is to help students/parents explore different possibilities and take better decision on choosingthe best neighbourhood out of many neighbourhoods in Scarborough city based onthe various features in and around that neighbourhood.    
<br>
<br>
## Selection Criteria of Neighborhood
In this project, we define a good neighbourhood by the goodHousing price and the good university/schools ratings. We can consider moreparameter to like low crime rates in that area, good weather conditions.<br>1. Compare School ratings<br>2. Compare Median of HousePrices
<br>
<br>
## The Location : Scarborough
Scarborough is a place which has good schools anduniversities so students are interested in going there. even it is a greatdestination for immigrants in Canada. As a result, it is one of the mostdiverse and multicultural areas in the Greater Toronto Area, being home tovarious religious groups and places of worship.
<br>
<br>
## Data Collection & Use of FourSquare API
For this project we collected data by scraping postal data from <a href="https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M">Wikipedia</a> and with the use of FourSquare API as a source of the dataof places as it has millions of places. They even provide the ability to performlocation search, location sharing and business details.We will Use credentials of Foursquare API features ofnear-by places of the neighbourhoods would be mined. Due to Http requestlimitations the number of places per neighbourhood parameter would reasonably beset to 100 and the radius parameter would be set to 500.

## K-Means Clustering
We will compare the similarities between two cities, we decidedto explore neighbourhoods, segment them, and group them into clusters to findsimilar neighbourhoods in a big city like Toronto. To be able to do that, weneed to cluster data which is a form of unsupervised machine learning: k-means clustering algorithm.
<br>
<br>
## Work Flow
Using credentials of Foursquare API features of near-byplaces of the neighbourhoods would be mined. Due to HTTP request limitations thenumber of places per neighbourhood parameter would reasonably be set to 100 andthe radius parameter would be set to 500. Steps taken were:<br>
1.    Dataacquisition and cleansing<br>2.    Datapreparation<br>3.    Featureselection<br>4.    Clustering<br><br><br>
## Data acquisition and cleansing
Data acquisition was a 2-step process:<br>1.    Obtainingthe postcodes for neighbourhoods in Toronto.<br>2.    Obtaining venues within these neighbourhoods.<br><br>
## Clustering Approach
To compare the similarities of two cities, we decided to explore neighbourhoods,segment them, and group them into clusters to find similar neighbourhoods in abig city like New York and Toronto. To be able to do that, we need to clusterdata which is a form of unsupervised machine learning:  k-means clustering algorithm.<br><br>

## Neighbourhood Most Common Venues

## Neighbourhood Median House Prices

## Neighbourhood School Ratings

## Conclusion
In this project, through a k-means cluster algorithm weseparate the neighbourhood into 03 clusters, which have similar neighbourhoodsaround them. Using the charts above decision leading to a particularneighbourhood based on average house prices and school rating can be made.
