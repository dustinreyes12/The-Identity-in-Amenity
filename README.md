# The Identity in Amenity: Uncovering the Association Rules of Available Amenities in Different Countries

Well-developed countries have high-end and desirable amenities which translates to high standards of living, in concurrence with the core idea of Spatial Equilibrium. Studies have documented the strong connection between the quality of social infrastructure and the well being of residents, yet evidence on the connection of the existence of decent amenities to economic growth has yet to be developed.

As such, this project intended to identify the association rules among available amenities – both public and commercial ones – in ASEAN countries. Particularly, we answered the question “Will the association rules of amenities reflect the countries’ economic conditions?”. We used the OpenStreetMap dataset from the Registry of Open Data in AWS with more than 300,000 amenities from 10 ASEAN countries.

Through Amazon Athena, the data were queried using the geographic boundaries of the countries and compiled at a 1x1 km resolution based on the Global Soil Partnership of the Food and Agriculture Organization of the United Nations. Frequent itemset mining was employed to retrieve the amenities that were present in a certain country. To uncover the association rules, we compared the confidence and applied minimum support of 1%. Lastly, we performed economic referencing using key indicators like the gross domestic product (GDP) per capita, life expectancy, and ease of doing business.

We found out that Singapore consistently had the highest confidence in the uncovered association rules. We also observed an association between the relative economic indicator standing and the relationship of entertainment amenities to transportation, health, and financial amenities
