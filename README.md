# Seatle-AIrbnb-Listings-Project
Seatle-AIrbnb-Listings project

# Seatle Airbnb Listings Dashboard
This is a data cleaning and visualization project created in entirely in Tableau from a Kaggle dataset pertaining to Airbnb listings in the Seatle area of the US from 2016

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/3e3f2601-fca4-45a8-8c01-10e27084bf7a)

## Live Dashboard
The live dashboard can be viewed at the following link:
https://public.tableau.com/app/profile/shaheer.kamal/viz/SeattleAirbnbOpenDataDashboard/FinalDashboard


## Key metrics observed

### Average price of an Airbnb listing
This is shown as a bar graph and depicts the prices in USD for property listings ranging from those that have just a single bedroom to those that have six bedrooms at max.

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/be1d79ff-f3b3-4b27-922e-c9365e1ee3cf)

#### Insights
The prices can be seen to steadily increase with the number of bedrooms. Larger properties with more bedrooms generally have the capacity to accommodate more guests. Hosts often charge higher prices for properties that can house larger groups of people.

Properties with multiple bedrooms may cater to a different target audience, such as families or larger groups of travelers. Hosts may set prices based on the willingness of these groups to pay more for a larger and more accommodating space as well as additional offered facilities.


### Prices by Zipcodes
This is represented with both a bar graph format as well a more visually appealing map visual.

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/ceda142e-8e2b-452a-b632-4002f12a5878)


The map visual segments all of the property listings based on their zipcodes. Hovering over any segment on the map will display the zipcode of that particular locality as well as the average price of an Airbnb located within that vicinity.

### Revenue for the year
This line chart shows the variation in the total price for all the available Airbnb listings as per the 'Calendar' table throughout 2016.

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/3c1fc8d8-f329-4916-b100-73393c99f7cc)

#### Insight
The prices saw a steady rise from the months 'January' to 'March' and again after 'November'. This could possibly be due to the general perception of favourable weather conditions for tourists coming to Seatle from Janauary to March or due to a higher frequency of leisure actvities or events occuring between these months leading to increased demands and thus higher prices.

Also the period after November might coincide with winter vacations, Christnas and a general holiday season again leading to an increased demand and thus higher Airbnb prices overall.

### Total number of distinct bedroom listings
The distribution of the Airbnb listings ranging from a single bedroom all the way up to six bedrooms are representted as a table within the dashboard.

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/890750d7-25bd-4a17-8eba-5383ed97aa6f)

#### Insights
The properties with just a single bedroom are the greatest in number as shown by table reaching close to 2000 listings in total while the total number of properties offering two to six bedrooms are approximately 1000 in total, far less than those that offer just a single bedroom.

This implies that there might be a higher demand or preference for smaller accommodations with just a single bedroom within Seatle .It could also suggest that the market might be more oriented toward catering to individual travelers, couples, or small groups.

The data may also reflect the competitive landscape in the area. If there are more one-bedroom listings, hosts with larger properties may face less competition within their category.

## Dataset
The dataset pertains to Airbnb property lisitngs in Seatle from 2016. It is publically available on Kaggle at the following link:
https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset/data?select=Tableau+Full+Project.xlsx

The dataset as a whole comprises of three tables 'Calendar', 'Listings' and 'Reviews'.

The 'Calendar' table comprises of 4 columns and about 1.05 million rows. 

It gives details about certain properties such as their unique ID (lisitng_id), the date on which it was listed on Airbnb, a flag to indicate whether it's still available or not and finally its price.

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/7063b1e5-b8d5-41ac-b394-f18835a31332)

The 'Listings' table is quite extensive comprising of 3818 rows and abut 92 columns .

It details the unique ID, URL, description, zipcode and a whole bunch of differetn attributes regarding a particular property .

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/c64d0e04-e01e-4c46-842a-ee9f243556ab)

Finally the 'Reviews' table consists of about 84,800 rows and 6 columns. 

As the name suggests, it provides details regarding a review given by a past occupant of a particular property. So, the table includes the unique ID of a particular property, the reviewer's ID, name as well as a description of the remark that they gave regarding the property.

![image](https://github.com/Sha95544/Seatle-AIrbnb-Listings/assets/62758405/5338f411-38f4-45d8-bdee-31179d6d7d58)

## The data analysis process
The initial step in the process pertained to cleaning the tables in the dataset by removing missing avlues and columns attributes which were irrelevant for the analysis.

Different joins such as 'left joins' were perfromed between the tables to prepare the dataset for visualization.

Finally, the cleaned dataset was observed using different visuals and a fully-fledged dashboard was then created within Tableau.

## Conclusion
The dataset used for this project dates back to 2016 and thus might not provide an accurate representation the Airbnb market trends within Seatle. 

The dashboard can be updated to include data from more recent years to give a more detailed insight on how the market for Airbnb listings within Seatle has shifted within recent years owing to different economical factors as well the outbreak of COVID in late 2019 and 2020.

