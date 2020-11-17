# Analysis of Paris Airbnb market
medium blog link : https://medium.com/@mathieurella.mr/little-secrets-about-airbnb-paris-listings-6369400dbc93
## Table of Contents

 - The Libraries That I Have Used
 - My Project Motivation
 
- File Descriptions
- Summary Of The Results
 - Acknowledgements

## The Libraries That I Have Used
The project was implemented using Anaconda, I've used the following python libraries:

- NumPy
- Pandas
- Sklearn
- Plotly
- textblob
## My Project Motivation

I was interested in exploring the Paris AirBnB dataset . I wanted to better understand the pricing trends, review sentiments and pricing prediction. here a the question I've tried to answer :

- Where is it good to rent on airbnb in paris ?
- Which season is the more profitable for the host ?
- What do really believe the guest of paris listing ?
- Can we predict the price of a listing ?
## File Descriptions
The Jupyter notebook showcases the analysis done in order to explore the dataset, the data prepartion and wrangling as well as the building of prediction models in order to answer the questions above. The notebook contains markdown cells to help with documentation of the steps as well as to communicate findings based on each analysis.

3 files has been analyzed :

- calendar.csv: calendar availability of listings and price
- listings.csv: information about all the available listings
- reviews.csv: listing reviews by the users

## Summary Of The Results

The following key findings from the analysis are summarized below:

Thanks to this analysis, we were able to assess the environment of the Paris Airbnb . We found that some neighbourhoods are more popular on airbnb than others and that this follows a logic adopted long before the creation of airbnb itself where the center will be more exclusive than the surrounding neighbourhoods.
As far as the host are concerned, due to legislation and availability, it was more profitable for them to rent during spring and summer season and to reserve the winter months to carry out all the maintenance necessary for the listings.
Finally, it was noted that the 1st district,Hotel de Ville, was the most appreciated district by tourists, no doubt because of its proximity to many of the cultural and historical places that make Paris.
Finally, I tried unsuccessfully to create a model to predict the price but it seems that a simple linear regression is not enough.

## Acknowledgements
Credit to the AirBnB dataset published by AirBnB here : http://insideairbnb.com/get-the-data.html
