# surfs_up
Analyzing weather data in jupyter notebook and making an app 

# Overview of analysis
This assignment showed the temperature statistics for June and December to see if running a surf shop is sustainable year around. We ran two seperate queries to get the temperature data, one for June and the other for December. Once we run the queries we stored the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:


# Results

 -- In June we had a total count of 1700, mean of 74.9, min of 64.0 and max of 85.0

<img width="338" alt="june_temps" src="https://user-images.githubusercontent.com/67278193/93652589-8b689200-f9e3-11ea-97a2-c3ea53e2da1e.png">
 
 -- In December we had a total count of 1517, mean of 71.0, min of 56.0 and max of 83.0
 
 <img width="397" alt="Screen Shot 2020-09-18 at 7 16 24 PM" src="https://user-images.githubusercontent.com/67278193/93652592-8d325580-f9e3-11ea-8c20-e3b1fe9c0393.png">
 
 -- Standard deviation is 3.25 in June and 3.75 -- making a .5 difference in the two different seasons

# Summary 

From the data we can tell what the temperatures are but since there are other attributes to the weather such as precipitation it can run additional queries to let us know whether or not people can come and visit the shop. If we are able to gain more data for the area we can run even more queries! From there we can decide how we would like to build the shop and what areas would make this a more prominent location for visitors to come.
