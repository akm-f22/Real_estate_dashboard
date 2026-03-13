Dataset description

The dataset contains the following attributes
1)Square feet – property area in square feet (numeric datatype)
2)Bedrooms – number of bedrooms (numeric datatype)
3)Bathrooms – number of bathrooms (numeric datatype)
4)Neighborhood – Divides the dataset into Rural, Suburb and Urban (alphanumeric datatype)
5)Year Built – Year the property was built (numeric datatype)
6)Price – Cost of the property (numeric datatype)

Data Cleaning/Wrangling

1.Opened power query editor and selected Transform
2.Removed duplicate rows
3.Converted the Price column to Fixed decimal number (AED)
4.Removed the negative values from Price column
5.Added new columns Price per sqft (price / sqft) and Property age (2025 – year built)
6.Added a conditional column Listing Category
Price < 200000 = Budget,
200000 < Price < 300000 = Mid Range,
300000 < Price = High End

Business Insights

1)44.6% of properties is falls under midrange, 38% of properties falls under Budget and 17.4% of properties falls under High end.
2)If we compare the average price of properties with respect to square feet area, we find that Urban area have the costliest property(keeping the square feet area constant).
3)When we compare the average price of properties with number of bedrooms, we find that the price of property in a listing category doesn’t differ much.
4)If we compare the average price of properties in a neighborhood, more the number of bedrooms, more is its price.
5)The market is continuously fluctuating throughout the history. In the recent history the price drop happened in 2017 and its rising upwards since then. Based on this observation, there may be a drop in prices in the near future. The present price has already reached a ceiling as compared to historical data.
6)In the scatter plot, we find that more the square feet area, costlier the price starts to get. We have a greater number of houses with low square feet area that are priced low. In the same manner, we have a greater number of houses with high square feet area that are priced high.
