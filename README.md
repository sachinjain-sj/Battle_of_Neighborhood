# Battle_of_Neighborhood

# Predicting the target locations to open a Chinese Restaurant in Pune, India

## Introduction: Business Problem

In this project we will try to find an optimal location for a restaurant. Specifically, this report will be targeted to stakeholders interested in opening a Chinese restaurant in Pune, India.
Since there are lots of restaurants in Pune we will try to detect locations that are not already crowded with restaurants. We are also particularly interested in areas with no Chinese restaurants in vicinity. We would also prefer locations as close to city centre as possible, assuming that first two conditions are met.
We will use our data science powers to generate a few most promising neighbourhoods based on this criterion. Advantages of each area will then be clearly expressed so that best possible final location can be chosen by stakeholders.

## Data

Based on definition of our problem, factors that will influence our decision are:
•	number of existing restaurants in the neighbourhood (any type of restaurant)
•	number of and distance to Italian restaurants in the neighbourhood, if any
•	distance of neighbourhood from city centre
We decided to use regularly spaced grid of locations, centred around city centre, to define our neighbourhoods.
Following data sources will be needed to extract/generate the required information:
•	centres of candidate areas will be generated algorithmically and approximate addresses of centres of those areas will be obtained using Geopy Nominatim
•	number of restaurants and their type and location in every neighbourhood will be obtained using Foursquare API
•	coordinate of Pune centre will be obtained using Geopy Nominatim of well-known Pune location (Shivajinagar)


