# BerlinAirbnb
Analysis of Berlin Airbnb Data

## Project Motivation
Airbnb is changing the way we travel.
The idea behind Airbnb was to create a sharing-economy where people rent out their appartements when they are away for the weekend for example.
Today people made a business out of Airbnb and rent out appartements all year around.
I want to create a model that predicts the price of the appartements based on the information that is available.

## File Descriptions
insideairbnb.com is an Airbnb-critical website and is not associated with or endorsed by Airbnb.
The data provided utilizez public information compiled from the Airbnb-website.
The data is provided individually for different cities.
For the Analysis of Airbnb listings of Berlin I used following files:
* **BerlinAirbnb.zip** contains the archived data.
  * **berlinlistings.csv** contains detailed information about the listings (Host, Ratings, Property Type, etc.).
  * **berlincalendar.csv** contains different prices for different dates for each property.
* **BerlinAirbnb.ipynb** contains the code of this analysis.

The dataset can be found [here](http://insideairbnb.com/get-the-data.html).

## Results
I analyzed the coefficients of the trained model to find out the impact of different listing-properties on the price of the listing.

### Neighbourhood
The neighbourhoods **"Mitte"**, **"Friedrichshain-Kreuzberg"** and **"Pankow"** have the highest positive impact on the price.
The neighbourhoods **"Reinickendorf"**, **"Spandau"** and **"Lichtenberg"** have the highest negative impact on the price.

### Amenities
The amenities **"Firm mattress"**, **"Amazon Echo"** and **"Gas oven"** have the highest positive impact on the price.

### Property Type
The property types **"Casa particular"**, **"Houseboat"** and **"Boat"** have the highest positive impact on the price.
The property types **"Treehouse"**, **"Barn"** and **"Hostel"** have the highest negative impact on the price.

### Month
The months **"July"**, **"June"** and **"May"** have the highest positive impact on the price.
The months **"February"**, **"November"** and **"January"** have the highest negative impact on the price.

### Day of Week
The days **"Saturday"** and **"Friday"** have a positive impact on the price.
The days **"Sunday"**, **"Monday"** and **"Tuesday"** have the highest negative impact on the price.

### Room Type
The room types **"Hotel room"** and **"Entire home/apt"** have a positive impact on the price.
The room types **"Shared room"** and **"Private room"** have a negative impact on the price.

## Licensing, Authors, Acknowledgements
This project would not have been possible without the data provided by Inside Airbnb.
Check out their website for more [information](http://insideairbnb.com/behind.html).
