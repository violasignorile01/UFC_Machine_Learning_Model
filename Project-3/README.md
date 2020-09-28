# Project-3
Project 3 was our final group project, we chose to create a machine learning model which would predict UFC fights. 
An important part of this project was choosing multiple features to include, in order for our model to be the most successful it could. Our group decided that each member come up with their own feature to add to the model - I chose tracking attendance levels of each event. This came from the thought of whether a more full or more empty arena has a greater effect on the fights, we further used this to test the accuracy of our model. 

In UFC, an event is where multiple fights occur, on the same date, in one arena. 
Since our data showed multiple fights on the same date, I knew I needed to solely search for the attendance of each date, not for each individual fight, since I only needed the attendance of that event as a whole
Thankfully, UFC’s website keeps track of the attendance counts of each event date, from here i manually entered in over 400 attendance counts, by date, into Excel, i then saved that data as a csv and we used it to add to our model, and create this chart you can see below which shows the average attendance levels for the top 15 most frequent locations
There were some dates where the attendance was not recorded, or there were multiple events were held on the same date - we dropped both of these types in order to have a more accurate dataset for our model 
