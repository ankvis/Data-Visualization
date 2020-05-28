# Ford GoBike System Data

Ford GoBike is a company that provides on-demand bike rentals for customers in San Francisco, Redwood City, Palo Alto, Mountain View, and San Jose. Users can unlock bikes from a variety of stations throughout each city, and return them to any station within the same city. Users pay for the service either through a yearly subscription or by purchasing 3-day or 24-hour passes. Users can make an unlimited number of trips, with trips under thirty minutes in length having no additional charge; longer trips will incur overtime fees.

This data set includes information about individual rides made
in a bike-sharing system covering the greater San Francisco
Bay area.

(Represented in chorological order of the table) <br>
1. Trip Duration (seconds)
2. Start Time and Date
3. End Time and Date
4. Start Station ID
5. Start Station Name
6. Start Station Latitude
7. Start Station Longitude
8. End Station ID
9. End Station Name
10. End Station Latitude
11. End Station Longitude
12. Bike ID
13. User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)

# Project Data: 
The realtime dataset has been accumulated from: <br>
https://www.lyft.com/bikes/bay-wheels/system-data

exploration_template.ipynb - This Jupyter Notebook contains section templates for exploration, starting from loading in the data, working through univariate visualizations, and ending with bivariate and multivariate exploration. At the end, the findings are summarized.

slide_deck_template.ipynb - This Jupyter Notebook contains starter cells for the slide deck deliverable. These cells provide an example of how the slide deck should be organized, including pre-set slideshow settings.

# Key Insights

1. Throught the year: People like to rent bikes during the month of October the most. Over 100000 bikes were rented during this month.
Top 3 months of the year for rentals:

October
September
November
Based on the given data - People hardly use bikes in June.

2. Looks like the bikes are rented during the weekdays, If I had to guess - bikes are used to commute to the work place.
3. Mostly, bikes are rented for around 12 mintues or 0.2 hour
4. Subscribers do use the rental bikes more than Non-Subscribers. Probably because of the discounts or lower rate of charges.
5. The top 5 stations for bike pick up and drop points are the same but they have different number of bikes involved.
6. Since there are more subscribers we see the trend of more rental bike usage by them but, it is interesting to see Non-Subscribers usually use the bike for longer period over subscribers. I am assuming they use bike for leisure unlike the subscribers who usually use them for communting to work place.
7. October had the most number of rentals which we found previously.The Faceting shows us - it also holds the record for most 10 minutes rentals followed by November and September.
8. Up to 100 mintues per day - Both user types are heavily utilizing the bike rentals but it fades away slowly reaching to a mark of 1400 mintues which is not very usual.

# Summary

**Based on our findings we have confirmed that out that Subscribers tend to use the bikes on weekdays for their communting due to high traffic in San-Francisco. The Non-Subscribers use the bikes mostly on weekends probably as a leisure activity.** 

**The Autumn season is the most popular for renting bikes because the weather is pleasant.**

**Some stations like Caltrain, Ferry Building and Embarcadero are popluar spots for bike rentals.**
