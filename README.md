# airbnb-santaclara-analysis
In this repo, I am going to host all the code related to analysis of Airbnb data for Santa Clara county, California and answer some interesting questions using the data.

I have detailed my findings in a blog post which can seen here: https://premys.medium.com/a-look-into-santa-clara-county-airbnb-data-fc8117ad7339

# Installations
I used Google Colab to run this analysis. It is a Jupyter notebook hosted on Google Cloud, ensuring that there is no need to run anything on a local machine, since everything is stored and run in the cloud. One can proceed to https://colab.sandbox.google.com/ to get started.

As a part of the analysis in Python, I used pandas, numpy, seaborn and pandasql to do the data wrangling. I also uploaded the csv files onto Google Drive first and loaded files into my Jupyter notebook from Google Drive.

# Project motivation
I wanted to look at Airbnb data as it has interesting real world implications related to tourism, travel and housing availability. I wanted to look at 5 interesting business questions about the data and understand what it would mean.
# 1: Which city in Santa Clara county has the most Airbnb listings? Which city has the least number of listings? What type of listings are they? (% of private room listings vs % of entire home listings vs % of shared room listings)
# 2:Which city has received the most number of reviews from visitors? Which city has received the least? Which city has the most reviews on average per listing?
# 3:In which month do we see a spike in reviews during the year?
# 4:Which city has the highest average price and lowest average price? Does it change if we look at median prices?
# 5:How many hosts have only 1 listing, how many have more than 1 listing?

# File descriptions
There are 2 files used for the analysis here. I have included them in the repo.
listings.csv contains all the metadata related to listings on Airbnb for Santa Clara county.
reviews.csv contains all the listing ids along with the review timestamp.

# Acknowledgements & licensing
The dataset used for this analysis is available here: http://insideairbnb.com/about.html and are authorised to use by the owner of the dataset.

