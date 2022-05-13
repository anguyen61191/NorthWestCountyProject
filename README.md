# Housing Data in King County, WA <br>
**Data Scientist:**  Anhduy(Andy) Nguyen, Juliet Day, Xibei(Julian) He <br>
**Date:** May 13, 2022

## **Business Understanding**
A real estate developer has expressed interest in developing real estate in the King County, WA area. They have come to us as a team of trained data scientists to recommend an optimized real estate development strategy on the kind of houses they should build and in what areas. This analysis will use different statistical analysis tools including, but not limited to, multiple linear regression, shuffle split validation, cross-validation and OneHotEncoder to find what attributes of a house contribute the most to the house’s value, therefore yielding the highest revenue for the developers.

## **Key business questions**
1. What are the effects of zip code on the overall pricing of a house?
2. How much does the size of the house affect the pricing of a house?
3. Do the materials built have an overall effect on the pricing of a house?

## **Data Understanding** 
The main data set used was, King County Housing Data, collected from 2014 to 2015. This data includes the unique identifier for the property, date of sale price, sale price, number of bedrooms, number of bathrooms, square footage of living space in the home, square footage of the lot, number of levels in the house, if it is a waterfront property, quality of the view from the house, the overall condition of the house, the grade of the house, the square footage of the house apart from the basement, square footage of the basement, year it was built, year it was renovated if it was renovated, zip code, the coordinates of the house in latitude and longitude, the square footage of interior house living space for the nearest 15 neighbors, and the square footage lot space of the nearest 15 neighbors. The data set was then cleaned before analysis was run on it.

The second data set, Zipcodes for King County and Surrounding Area, includes location data for King County. This data set was used for mapping purposes.


## **Conclusions**
1. **Square foot** living has a good correlation with pricing.  Data shows that a good size ranges between 1600 - 3300 square feet.  Where each square foot increases value by $90.

2. Build homes with **Grades between 7 to 10** because the data shows that they have the highest growth range in house value.

3. **Zipcode/location** is a very important factor in house value according to our data.  Building in a high value zipcode can increase your house value by **$100,000**.

## **Next Steps**
1. **View/Waterfront** seems correlate highly with price by looking at the zipcode heatmap it shows waterfront properties have high average prices compared to non waterfront properties.  If we had more time looking into this point would be good.
2. **Cost of building and anymore development information** would help build a better model and add a cost - profit analysis.
3. More **Data** would be very important.  The data set given was only for 2 years and while it built a decent model it could be better if the data was over a longer period of time.

## **Keynotes**
* Some important notes I found while doing this was if more time given a better model would have been able to be developed.  Some categories weren't included into the model because of time constraints that I would have loved to get into.  I would have also liked to add more data sets into the data we have to create a more robust model.  Some interesting factors I thought of were school districts, local parks, and areas where events are hosted occur.  This would be fun to look into if more time was alloted.