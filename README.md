##  <center> Coursera Capstone Project </center>

###### <center> IBM Applied Data Science Capstone</center>

#  <center>*Opening a new Restaurant in Delhi,India* </center>


 ![](Desktop/Delhi_Restaurants.jpg )

 

 

 

 

### Business Problem

The objective of this project is to analyse neighborhoods of Delhi to select the best location to open a restaurant. 

 

 

 

 

 

## Introduction  
While Delhi has always been a food-loving with each region having its own special cuisine, they have never been very big on eating out in the past. But all that is changing now. The restaurant industry in Delhi has been growing at a rapid pace over the last decade or so and the growth story is set to continue for the next foreseeable future. Its increasing population, rapid urbanisation and growing awareness of western lifestyles and higher disposable income were some of the factors that contributed to the growth of the restaurant industry.
  Property developers, online food platform companies are taking the advantage of this trend to build new restaurants to meet the demands. However not every restaurants marked success. There are few considerations particularly the location of the restaurant that determines that whether the mall will be a success or failure.

 

 

 

 

 

 
  
### Using Data Science methodology techniques we will the answer the following questions:

* ***How is the frequency distribution of restaurants across Delhi?***
* ***What type of venues are present in each locality?***
* ***What is effect of other venues on frequency of restaurant in a locality?***

 

 

 

 

#### Questions to be answered intuitively:

* ***What is the effect of other restaurants on a new restaurant in a locality?***   
It can be clearly observed that if a location has lots of restaurants then opening new restaurants in such area is a bad idea. And similarly if a location has very few restaurants then it is a better idea to open a restaurant.
* ***What is effect of other venues on  a new restaurant in a locality?***
There are some venues that affect the working of restaurants. E.g. Shopping Malls, Bars, Government buildings etc.

 

 

 

 

### Target audience of this project

* Property Developers and investers who are looking to invest in Restaurants in Delhi.

* Those Online Food Platform Companies who are planning to invest in new restaurants in Delhi to improve their performance.

* Shefs or potential public who are aiming to open a new restaurant in Delhi.

This project is particularly helpful for online food platform companies and property developers and investors of Delhi. This is the high time because of which this project is timely and relevent.Lots of new restaurants are opening hence increasing competition.  

Nearly 82 per cent of the restaurants are domestic standalone outlet/chains, while the remaining 18 per cent restaurants being of international origin. A growing market for international origin restaurants as well, Delhi has many Mexican, Mediterranean, Lebanese and Arabian restaurants etc.


###  **Data**

**To solve the problem, we need the following data:**  

* List of neighborhoods in Delhi. This defines the range of area of consideration in the project which is Delhi,capital city of India
* Latitude and longitude coordinates of each neighborhoods. These are needed in order to plot the neighborhoods on map and also to get the venues in each neighborhoods.
* Venue Data, which will be used to perform clustering on neighborhoods.

### Sources of Data and its extraction

* The neighborhood list data can be found in the following wikipedia page link (https://en.wikipedia.org/wiki/Neighbourhoods_of_Delhi). By web scraping we can extract the data from the page, using python requests and BeautifulSoup packages.

* The latitude and longitude(geographical coordinates) data of the neighborhoods can be extracted using the geocoder package of python.However a very few neighborhoods geographical coordinates are not found using geocoder package which can be separately found

* Lastly we will use FourSquare API to get venue Data of neighborhoods. Foursquare has one of the largest Database of more than 105 million places worldwide.

 

 

 

 

In this project we will make use of Data Science tools such as web scraping, working with Foursquare API, Data cleaning, Data wrangling, machine learning(e.g. K-means clustering), folium (map visualisation) and Matplotlib.  
 In next section we will discuss about Data Science Methodology.


