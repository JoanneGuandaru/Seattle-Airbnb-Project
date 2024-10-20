# Seattle-Airbnb-Project
Analytics Projects- Tableau

 Seattle Airbnb Project - Project Overview
The goal of this project was to analyze Seattle's Airbnb market in order to help a client determine the best location for starting a new Airbnb business. The analysis focused on several factors, including competition, average price charged per bedroom, zip code, property type, and seasonal revenue trends.

Airbnb, founded in 2008, is a global online marketplace for lodging, primarily homestays for vacation rentals and tourism activities. The company connects hosts offering short-term lodging with guests, allowing for flexible, often more affordable accommodations compared to traditional hotels.

In Seattle, a major U.S. city known for its vibrant tech industry and tourism, the Airbnb market is competitive but offers potential opportunities for hosts. The aim of this analysis was to identify locations and property characteristics that yield the highest profitability, guiding the client on where to invest for the best returns.

 Dataset Structure
The dataset used in this analysis was the Seattle Airbnb Open Data from Kaggle, which included two main tables: `listings` and `calendar`. These tables were joined using an inner join to consolidate information on property features (e.g., number of bedrooms, zip codes) and booking trends (e.g., revenue fluctuations, property availability).

 Insights Summary
 Average Price Charged per Bedroom
The analysis revealed that properties with more bedrooms command higher average prices. The breakdown of average prices charged per bedroom is as follows:
- 6-bedroom properties: $661.4
- 5-bedroom properties: $562.7
- 4-bedroom properties: $334.8
- 3-bedroom properties: $291.5
- 2-bedroom properties: $200.7
- 1-bedroom properties: $102.4

 ![Average Price Per Bedroom Visualization on Tableau](https://github.com/JoanneGuandaru/Seattle-Airbnb-Project/blob/main/Avg%20Price.PNG?raw=true)

This shows a clear trend where larger properties, particularly those with 5 or 6 bedrooms, have significantly higher average nightly rates compared to smaller properties, which may appeal to families or groups.

 Average Price Charged per Zipcode
The zip code analysis identified several areas with varying price points. The highest average prices were found in zip codes:
- 98101, 98109, 98104 (central and highly sought-after areas).

In contrast, the lowest prices were found in zip codes:
- 9833, 98106, 98117 (further from the city center and less competitive).

Moderately priced zip codes included:
- 98122, 98107, 98144 (mixed residential and commercial areas).

This insight suggests that central locations or those closer to major attractions can command higher prices, but there are also opportunities in less competitive areas for budget-conscious travelers.

 Count of Listings Based on Bedrooms
The distribution of listings based on the number of bedrooms showed a clear preference for smaller properties, with 1-bedroom listings dominating the market:
- 1-bedroom: 1,811 listings
- 2-bedroom: 483 listings
- 3-bedroom: 206 listings
- 4-bedroom: 55 listings
- 5-bedroom: 20 listings
- 6-bedroom: 5 listings

This indicates that there is a greater supply of smaller properties, and competition might be stiffer in this segment, while larger properties (4+ bedrooms) could offer unique opportunities with lower competition.

 Revenues Based on Time of Year
Revenues fluctuate across the year, with some months showing stronger performance than others. The start and end of month revenue trends in millions (USD) were as follows:
- January: $1.012M - $1.568M
- February: $1.670M - $1.805M
- March: $1.857M - $1.906M
- April: $1.819M - $1.844M
- May: $1.908M - $2.013M
- June: $1.991M - $2.039M
- July: $1.927M - $1.940M
- August: $1.968M - $2.009M
- September: $1.958M - $1.959M
- October: $1.930M - $1.933M
- November: $1.943M - $1.979M
- December: $2.004M - $2.110M

Revenue peaks during the summer months (June-August), and December also experiences high revenue, likely due to the holiday season. This indicates strong seasonality in the Seattle Airbnb market, with higher demand during peak travel times.

 Impact of Property Type on Occupancy
The type of property also played a role in occupancy rates, though this analysis needs to be cross-referenced with deeper insights. From similar markets, larger homes and unique properties (such as luxury homes or properties with distinct architectural styles) often have higher occupancy during peak seasons, while smaller or more generic apartments may see steadier but lower occupancy year-round.

 Recommendations
1. Focus on Larger Properties: Given that 5- and 6-bedroom properties command the highest prices but have the lowest number of listings, investing in larger properties could yield higher profits due to less competition and premium pricing.
2. Target High-Demand Zip Codes: Zip codes 98101, 98109, and 98104 should be prioritized for new Airbnb investments as they have the highest average nightly rates and are likely closer to tourist attractions and business hubs.
3. Capitalize on Seasonality: Revenues are highest during the summer and holiday seasons. Consider pricing strategies to maximize earnings during these peak periods while offering discounts or promotions during the slower months to maintain steady occupancy.
4. Explore Niche Property Types: Unique properties or luxury homes could capture higher occupancy rates and pricing, especially during high-demand months. Emphasizing distinct offerings could help in differentiating from the large supply of smaller, standard listings.

 Dashboard
The Tableau dashboard created for this analysis provides detailed visualizations of average price trends by bedroom and zip code, listing distributions, and revenue patterns across the year. The dashboard allows users to filter by property type, number of bedrooms, and location for a more granular analysis.
