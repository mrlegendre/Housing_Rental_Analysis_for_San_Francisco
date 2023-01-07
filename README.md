
# Housing Rental Analysis for San Francisco

![](/Images/SanFran.png)

The objective of this project is to find properties in the San Francisco market that are viable investment opportunities utilizing data visualization skills, including aggregation, interactive visualizations, and geospatial analysis.
The "san_francisco_housing.ipynb" file is a Jupyter notebook file that contains analysis of the housing rental market data for San Francisco.

The data in the resources folder uses census data of San Francisco from the years 2010-2016, and geo coordinates of neighbourhoods in San Francisco.

A visualization will be created using hvPlot and MAPBOX (an API for all maps given geo coordinates of latitude and longtitude)

# PART 1 Calculate and Plot the Average Sale Prices per Square Foot
Group the data by year, and then average the results.

What’s the overall trend in housing units over the period that you’re analyzing?
* The overall trend is that the number of housing units is increasing for the period analyzed.

# PART 2 - Calculate and Plot the Average Sale Prices per Square Foot
Group the data by year, and then average the results.

What is the lowest gross rent reported for the years included in the DataFrame?
* The lowest gross rent reported was $1239 in year 2010

Did any year experience a drop in the average sale price per square foot compared to the previous year?
If so, did the gross rent increase or decrease during that year?
* YES in the year 2011 there was a drop in the average sale price per square foot compared to the previous year, and then experienced an INCREASE that year.

# PART 3 - Compare the Average Sale Prices by Neighborhood
For the Anza Vista neighborhood, is the average sale price per square foot for 2016 more or less than the price that’s listed for 2012?
* The average sale price per square foot for 2016 is LESS than listed for 2012

# PART 4 -Build an Interactive Neighborhood Map
Which neighborhood has the highest gross rent, and which has the highest sale price per square foot?
* The neighbourhood with the highest gross rent was WESTWOOD PARK, and with the highest sale price per square foot was UNION SQUARE DISTRICT

![](/Images/SanFranciso_SQ-ft_and_Gross_rent_mapbox_plot.png)

# DATA STORY
How does the trend in rental income growth compare to the trend in sales prices? 
Does this same trend hold true for all the neighborhoods across San Francisco?
* The trend in rental income growth to trend in sales price are ONLY SOMEWHAT RELATED.  As certain neighbourhodds may have some high square footage value, but low rent (maybe a better place to live longterm, or a newer neighbourhood)  Where as others have low square footage value, but higher rents(maybe better investment, older more bulit up neighbourhoods)

What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? 
Do neighborhoods exist that you would suggest for investment, and why?
* For a potential one-click, buy-and-rent strategy probably the best investments are places in the south, and slightly central due to the fact that they fross the highest rent, and the price per square foot is reasonably average or below average based on the data, and visual map representation.



