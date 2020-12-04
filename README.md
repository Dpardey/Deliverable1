# ¿What determines the renting price of an Airbnb property?

Imagine the following situation: You have been saving money for a while in a hedgefund. One day you realized that in order to maximize the long-term profitability of your savings, it's better to invest in the real estate market, specifically in the Airbnb rental business. Subsequently, one of the many question you may ask yourself is ¿Which property should I buy? ¿How high can I set the price?. This analysis is right for you. The goal of this pithy project is to show you which variables derive the over-night renting price.
The project doesn't have netiher a soffisticated algorithm nor ML algorithms, thus it can be read by anyone!

## Data

The data used was a Boston Airbnb Open Data that can be found in [Kaggle](https://www.kaggle.com/airbnb/boston). Dataset consists of over 90 columns and 3.5k of records. The information can be summarized in the following categories:
- Propeties information: Number of beds, property type, Number of bathrooms, etc.
- Location: Neighbourhood, latitude, longitude. 
- Customer reviews: Customer score for location, cleanliness, etc.

## Packages
#### Data manipulization
numpy
pandas
datetime
regex

### Visualizations 
matplotlib
seaborn 
folium
HeatMap
msno
Image

## Summary of the conclusions

- Some proper correlations were found between the target variable (price) and the independent variables.
- Especial caution is needed due to Sympson's paradox across the variables.
- Customer perception is an influential set of features that derives the price


## Resources
  1. [This notebook was useful for extracting functions to clean the data and organize the graphs](https://www.kaggle.com/residentmario/exploring-prices)
  2. [Loft image](https://www.airbnb.com.co/rooms/14105971?_set_bev_on_new_domain=1606424896_ZGViNGRiYzUyNTc1&source_impression_id=p3_1606751143_xl6H09vLcBYyc0J8&guests=1&adults=1)
