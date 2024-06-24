# Real_Estate_price_prediction

## The dataset includes seven columns, each providing specific information about real estate transactions. Here is a detailed overview of the columns:

Transaction Date: The date when the real estate transaction took place.
House Age: The age of the house, measured in years.
Distance to the Nearest MRT Station: The distance from the property to the nearest Mass Rapid Transit (MRT) station, measured in meters.
Number of Convenience Stores: The count of convenience stores in the vicinity of the property.
Latitude: The latitude coordinate of the property’s location.
Longitude: The longitude coordinate of the property’s location.
House Price of Unit Area: The price per unit area of the house.


## The histograms provide valuable insights into the distribution of each variable:

House Age: The distribution is relatively uniform, with a slight increase in the number of newer properties (lower age).

Distance to the Nearest MRT Station: Most properties are located near an MRT station, indicated by the high frequency of shorter distances. A long tail extends towards higher distances, suggesting that some properties are quite far from MRT stations.

Number of Convenience Stores: This variable displays a wide range, with noticeable peaks at specific counts such as 0, 5, and 10, indicating common configurations in the availability of convenience stores.

Latitude and Longitude: Both variables show relatively concentrated distributions, suggesting that the properties are situated within a geographically limited area.

House Price of Unit Area: The distribution is right-skewed, with a concentration of properties in the lower price range and fewer properties as prices increase.


## The scatter plots revealed intriguing relationships between various factors and house prices:

House Age vs. House Price: There doesn't appear to be a strong linear relationship between house age and price. However, it seems that both very new and very old houses might command higher prices.

Distance to the Nearest MRT Station vs. House Price: There is a noticeable trend indicating that as the distance to the nearest MRT station increases, house prices tend to decrease. This suggests a strong negative relationship between these two variables.

Number of Convenience Stores vs. House Price: There appears to be a positive relationship between the number of convenience stores and house prices. Properties with more convenience stores nearby tend to have higher prices.

Latitude vs. House Price: Although not a strong linear relationship, there seems to be a pattern where certain latitudes correspond to higher or lower house prices, possibly indicating that specific neighborhoods are more desirable.


## The correlation matrix provides quantified insights into how each variable is related to the others, especially with respect to the house price:

House Age: This shows a very weak negative correlation with house price (-0.012), implying that age is not a strong predictor of price in this dataset.
Distance to Nearest MRT Station: Has a strong negative correlation with house price (-0.637). It indicates that properties closer to MRT stations tend to have higher prices, which is a significant factor in property valuation.
Number of Convenience Stores: Displays a moderate positive correlation with house price (0.281). More convenience stores in the vicinity seem to positively affect property prices.
Latitude and Longitude: Both show a weak correlation with house prices. Latitude has a slight positive correlation (0.081), while longitude has a slight negative correlation (-0.099).

