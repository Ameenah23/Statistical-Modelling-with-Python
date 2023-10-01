# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
In this project we investigate and analyze data that taken from CityBikes company.

What is citybikes?
Citybikes is an API that provides bike sharing data for apps, research and projects. And supports more than 400 cities.

I chose NEW YORK city in the US country. It is ONE of the biggest cities in the world that uses citybikes serveries.
In this project we investigate and analyze data that taken from CityBikes company.

NEW YORK city contains the largest and commercial hub of the country. Major restaurants, hotels, and large businesses are situated in NEW YORK. Any person who wants to visit NEW YORK needs to know various locations within NEW YORK whatever the aims.

Therefore,  I will be fetching business name, category, review, and location. This will help to understand what kind of business will have a great impact and in what location within NEW YORKi.

I will be focusing on manipulating data in the categories of bars, restaurants, schools, and shops within NEW YORK and  analyzing the data that are in a 1000 m radius from NEW YORK.

This will help to get all of the places that have been rated by Yelp and Foursquare users within and around NEW YORK.

In this project, I make calls to the YELP API and Foursquare API for different purposes. To construct a URL to send a request to the API to search for a specific type of venues, to explore a particular venue, to explore a Foursquare user, to explore a geographical location, and to get trending venues around a location. Also, I will use the visualization library, Folium, to visualize the results. 

Finally, In this part of the project we will build the reggresion model for this system and interpret the results using statistical coeffients and viualization.


## Process
The Steps:

    - We will be focusing on Python functions used for Exploratory Data Analysis in Python. 

    - EDA is applied to investigate the data and summarize the key insights. And will give the basic understanding of the data, it’s distribution, null values and much more.

    - Explore data using graphs or through some python functions.

    - Explore the structure of the API, query the API and understand the data returned.

    - Send a request to CityBikes, Foursquare and Yelp for the New York city. With a small radius (1000m) for all the bike stations in New York city. 
    
    - Extract Data and parsed results into a DataFrame and compare between the results from API provided.

    - Join the data from Part 1 with the data from Part 2 and visualize the EDA.

    - Put all the results in an SQLite3 database.

    - Build a regression model. And Provide model output and an interpretation of the results. 

## Results
    - In this project, we identified popular businesses and business categories in New York city. 
    - We acquired the  data from Yelp and Foursquare and processed it, which included varient parameters. I found the data that collectecd by YELP API is more accurate from foursqure api.
    - I found the 'extr/slots' variable is the best variable to build  the agregation model. 
    The fitting is perfect all coefficients have significant p-values with high R-squared: 0.968


## Challenges 
(discuss challenges you faced in the project)
    - I faced many challenges in this project because of the time. There was an exam and project in one week.The project requires very high knowledge in programming and transferring files formats.
    - lack of real dirctions from the materials to optomizing the time. We turn around ourselves for two days until figure out how to access to the right API pages. How to converting between formats.
    - My computer is an old, hang, freezing, restarting alone. 
    - VSCode is not working well. Everytime, needs to install the libraries. contradict between the version libraries.
    - I had to travel out of the province for my medical appointment and the causes me huge trubles with the coordinators of the program.
    - I made a big mistake when I realized to the coordinators of the program about my disability to request a commodation according to my situation but that makes the staff of the program .... ect. 

![New York Map](NewYorkmap.png)

