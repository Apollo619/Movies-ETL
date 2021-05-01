# Movies ETL

## Overview of Project:
*Amazing Prime*, an online platform that allows people to watch movies and television series, is hosting a *“Hackathon”* that will provide a clean set of movie data for the coding community to “predict the popular picture”. 

### Purpose: 
By doing this *Amazing Prime* is hoping to gain the ability to determine which low budget movies being release will become popular so they can buy the streaming rights at a bargain.
## Results:
First, we must provide the clean data set the coding community will be working with.
-	This is done by web scraping from Kaggle.com and Wikipedia and downloading a list of movies and the ratings from various users. 
Next, we transform the data from different data sets into easy to interpret and useful tables. 
-	by removing empty or arbitrary columns we can help slim down the table size and editing the column names so coders have an easier time determining what is useful to increase the algorithms accuracy.  See below for snippet of code used for this process. 
![](https://github.com/Apollo619/Movies-ETL/blob/main/Resources/clean%20movie%20code.PNG)
After all of this has been the data sets needed to be pushed to an SQL database with movie and ratings tables. See below image for snippet of code used to accomplish this. 
![](https://github.com/Apollo619/Movies-ETL/blob/main/Resources/to%20sql%20code.PNG)

## Summary:
Over 6,000 movies and 26 million reviews were transformed and organized into a clean dataset ready for the *Amazing Prime* sponsored hackathon. 
