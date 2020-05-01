Newyork city Airbnb open data Analysis.
Airbnb is an online marketplace for arranging or offering lodging, primarily homestays, or tourism experiences.
trying to find out exploratory data analysis, visualizations, interactive plots,and other interesting insights into the Airbnb data

NYC Airbnb Data
In this notebook we retrieve the relevant data from data webisite for airbnb hostings and is downloaded from the website link provided NYCAirbnb. lthough there are around 113 columns for some of the data set in the website we extract the relevant columns aslisted below for our purpose.

Description of columns
- idlisting: ID 
- name
- name of the listing 
- host_id: host 
- ID host_name: name of the host 
- neighbourhood_group
- location 
- neighbourhood: area 
- latitude: latitude coordinates 
- longitude: longitude coordinates 
- room_type listing: space type 
- price: price in dollars
- minimum_nights: amount of nights 
- minimum number_of_reviews: number of reviews 
- last_review: latest review 
- reviews_per_month: number of reviews per month 
- calculated_host_listings_count: amount of listing per host 
- availability_365: number of days when listing is available for booking

In this notebook wich can be considered to be the first part of the study, we import, read, wrangle the data. We drop missing values that are not important to our investigation and convert some datatypes:
Tasks we plan to do:
On Data Cleaning
Combine the data from different .csv's neighbourhood_group
Extract the comments from our data and analye it
Clean, drop, replace types into appropriate form
On Analysis
Compare Price per room_type and within neighbourhood_group
Use the geodata to map the location of the airbnb's in NYC
Analysis on commnets and categorize postive, negative, and/or neutral
Identify popualr words on comments
