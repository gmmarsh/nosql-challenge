# nosql-challenge
module 12 challenge

The NoSQL_setup_starter.ipynb notebook establishes the non-sql database set up. The actions included the creation of the database and the collection known as 'establishments'. An update to the database was made. The database was cleaned by making several data type conversions that were necessary for the analysis that occured in the NoSQL_analysis_starter.ipynb.

The NoSQL_analysis_starter notebook answers the following questions:
1. Which establishments have a hygiene score equal to 20?
2. Which establishments in London have a RatingValue greater than or equal to 4?
3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"? The geocode.Latitude and geocode.Longitude keys were used to find the nearest locations. The search was conducted within 0.01 degree on either side of the latitude and longitude.
4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.