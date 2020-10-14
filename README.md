# UFC Machine Learning Model 

## Overview
Used UFC data pulled through Kaggle to create a machine learning model which would predict UFC fights.
** An important aspect was choosing multiple features to include, in order for our model to be the most successful it could ** 

## My Chosen Feature
The feature I chose to add to the model was tracking attendance levels of each event - this came from the thought of whether a more full or more empty arena has a greater effect on the fights, this was further used to test the accuracy of our model.

## Background
In UFC, an event is where multiple fights occur, on the same date, in one arena. Since the data showed multiple fights on the same date, I knew I needed to solely search for the attendance of each date, not for each individual fight, since I only needed the attendance of that event as a whole.

Thankfully, UFC’s website keeps track of the attendance counts of each event date, from here I manually entered in over 400 attendance counts, by date, into Excel.
I then saved that data as a csv and used it to add to our model, and create this chart you can see below which shows the average attendance levels for the top 15 most frequent locations. There were some dates where the attendance was not recorded, or there were multiple events held on the same date - I dropped both of these types in order to have a more accurate dataset for the model.
