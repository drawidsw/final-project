# Overview

The following insights are obtained by analyzing the Montgomery County, MD home sales data from Q3 2020 to Q3 2021.

# A Map of Home Sales by Prices

https://public.tableau.com/app/profile/swapna.drawid/viz/Final_Project-Home_Price_Geo/price_geo

As seen from the map above, high priced homes are in the South bordering DC.

## Visualising House Prices Correlation with High School Ratings

https://public.tableau.com/app/profile/swapna.drawid/viz/Final_Project-school_assignment_prices/school_assignment_prices

The above map shows color-coded home prices along with pinned locations for high schools and their ratings. This visually gives a quick confirmation that house sale prices are high when school ratings are high and vice versa.

# Where are The Homes Sold

Sale prices and counts are aggregated based on zip codes and plotted in Tableau. 

## Sale Price by Zip Code

https://public.tableau.com/app/profile/swapna.drawid/viz/Final_Project-Price_By_Zip/price_by_zip_code

As seen above, sale prices are the highest in the following zip codes:

| Zip code | Average Sale Price |
| -------- | ------------------ |
| 20815 | $1.33M |
| 20816 | $1.31M |
| 20817 | $1.21M |
| 20854 | $1.16M |
| 20818 | $1.14M |

All of these zip codes comprise Bethesda and North Potomac area with the highest real estate prices in the county.

Consequently, the zip code 20886 (Montgomery Village) had the lowest average sale price at $371K. As we have discussed in the ML model results [here](README_ML.md), school ratings play a large part in determining these prices.

## Number of Sales by Zip Code

https://public.tableau.com/app/profile/swapna.drawid/viz/Final_Project-Sales_By_Zip/sales_by_zip_code

The graph above shows where the most popular houses in the county are. They are in zip codes 20878 and 20874. Here, the schools are relatively good, houses are smaller, somewhat older and thus, more affordable. One exception is the zip code 20854, which remains popular despite very high prices.

# Sale Price of Popular Homes

The following graph shows the sale price histogram. Houses between $400-500K are the most popular, and the collective band of $300-700K constitutes a majority of the houses sold in the county.

https://public.tableau.com/app/profile/swapna.drawid/viz/Final_Project-Price_Histogram/price_count_histogram

# Housing Trend in the Last Year

In the last year, both the volume and the sale price of homes have substantially increased. The following graphs demonstrate this.

https://public.tableau.com/app/profile/swapna.drawid/viz/Final_Project-Sales_Trend/sale_count_trend

The graph above shows the volume of sold homes increased from a low of 822 to a high of 1579 (almost double) between Jan 2021 and June 2021.

https://public.tableau.com/app/profile/swapna.drawid/viz/Final_Project-Price_Trend/price_trend

Correspondingly, the average sale price jumped from $607K in Feb 2021 to $684K in March 2021, and has been staying steady at that level since then.
