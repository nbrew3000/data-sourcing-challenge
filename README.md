# data-sourcing-challenge
This Challenge has three parts, and must be completed in order:

Part 1: Access the New York Times API.

Part 2: Access The Movie Database API.

Part 3: Merge and Clean the Data for Export.
 
Overview
Data sourcing solution designed to assist a movie recommendation system. The challenge involved extracting and merging data from two distinct APIs - The New York Times and The Movie Database (TMDb) - to create a comprehensive dataset of movie reviews and related movie details. This data is instrumental for implementing natural language processing techniques in the recommendation system.
Data Extraction and Processing
Part 1: Accessing the New York Times API
•	A query URL to fetch movie reviews, filtering for reviews in the headline.
•	Implemented a loop to paginate through the API response.
•	Stored the fetched data in a DataFrame and extracted movie titles using a custom function.
Part 2: Accessing The Movie Database API
•	Utilized the movie titles obtained from NYT reviews to fetch corresponding movie details from TMDB.
•	Created a mechanism to handle API rate limiting and efficiently processed multiple requests.
•	Parsed the API response to gather details such as genres, spoken languages, and production countries.
Part 3: Merging and Cleaning Data
•	Successfully merged the two datasets on the movie and titles.
•	Performed data cleaning to convert list string into clean, readable strings.
•	Ensured the final DataFrame was free of duplicates and had a reset index for easier analysis.
Final Product
The culmination of this project was a cleanly formatted CSV file, ready to be utilized in a movie recommendation system. This file contains rich details combining critical reviews from NYT and extensive movie metadata from TMDb.
API interaction, data manipulation, and problem-solving in Python. Key challenges included handling API rate limits, extracting and cleaning nested JSON data, and merging datasets with varying structures. github and chatgpt

