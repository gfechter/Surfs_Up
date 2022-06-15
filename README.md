# Surfs_Up

## Project Overview 
There is a proposal to build and open a surf and ice cream store in Oahu. To launch the store, investors are needed to financially back the store. However, before investors agree to fund the store, they requested an analysis of weather data from Oahu to determine if a surf and ice cream shop is a good investment. After doing the initial analysis and using Flask to display the analysis results on a webpage, the investors decide that they want to make sure that the shop would be sustainable year-round. Therefore, they request temperature data for June and December. 

## Resources
- Data: hawaii.sqlite
- Python 3.7.11, Jupyter Notebook, Flask, SQLAlchemy, and SQLite

## Results

The results of the analysis indicate that the surf and ice cream shop would be sustainable all year. For both June and December, a query was done to retrieve all the temperatures for the month, then those temperatures were converted to a list, a DataFrame was created based on the list, and summary statistics for the DataFrame were generated. 

There are several differences in the weather between June and December:
- The average temperature for June is 74.95° whereas the average temperature for December is 71.04°.
- The lowest temperature in June is 64.00° whereas the lowest temperature in December is 56.00°.
- The highest temperature in June is 85.00° whereas the highest temperature in December is 83.00°.

June Temperatures Summary Statistics

<img width="159" alt="Screen Shot 2022-06-14 at 5 13 12 PM" src="https://user-images.githubusercontent.com/103774401/173710441-55041621-104d-4440-bef1-55ea784e0fd3.png">

December Temperatures Summary

<img width="145" alt="Screen Shot 2022-06-14 at 5 13 49 PM" src="https://user-images.githubusercontent.com/103774401/173710451-a32a3ddb-d491-4e24-b72d-9c4ae38714a8.png">


## Summary

There are differences between the weather in June and in December. June typically has warmer weather than December. However, the average temperature in June is only 4 degrees higher than in December. Given that December is often one of the coldest months, the fact that there is only about a 4-degree difference between the average temperature in June and December shows that the weather stays fairly consistent throughout the year. 

The most common temperature for June is 76.00° whereas the most common temperature for December is 71.00°. Once again, this is not that big of a temperature difference. 

June Temperatures Histogram and Mode

<img width="444" alt="Screen Shot 2022-06-14 at 5 14 16 PM" src="https://user-images.githubusercontent.com/103774401/173710525-769a3211-2651-4ef2-a653-7ba4470d3691.png">

<img width="386" alt="Screen Shot 2022-06-14 at 5 22 54 PM" src="https://user-images.githubusercontent.com/103774401/173710899-75bae7f0-3d8f-456c-bedd-872c99bf9d71.png">


December Temperatures Histogram and Mode

<img width="506" alt="Screen Shot 2022-06-14 at 5 14 39 PM" src="https://user-images.githubusercontent.com/103774401/173710543-b53f0127-af04-40e6-a111-c8cae3f85692.png">

<img width="386" alt="Screen Shot 2022-06-14 at 5 22 33 PM" src="https://user-images.githubusercontent.com/103774401/173710917-8b066fc4-bcc3-4799-bc19-15401186ee66.png">


The lowest temperature in June is 64.00° whereas the lowest temperature in December is 56.00. This is a 9-degree difference which is larger than the difference between the average temperatures and the most common temperatures. However, there is only one date in June when the temperature was 64.00°. For December, there were only two dates where the temperature was 56.00°. Therefore, the lowest recorded temperatures rarely occur. 

June Lowest Temperature (64.00°) Count

<img width="594" alt="Screen Shot 2022-06-14 at 5 15 57 PM" src="https://user-images.githubusercontent.com/103774401/173710584-e5a41c55-ea01-43ac-962f-a45c057909df.png">


December Lowest Temperature (56.00°) Count

<img width="602" alt="Screen Shot 2022-06-14 at 5 15 01 PM" src="https://user-images.githubusercontent.com/103774401/173710572-2d2a4a12-3dc8-4644-9e58-852a4a009aa7.png">


The highest recorded temperatures for June and December are 85.00° and 83.00°, respectively. These temperatures would not hurt the store as people tend to enjoy spending time outside and eating ice cream when it was warm outside. 

Overall, the differences in temperatures between June and December indicate that temperatures in those months do not differ drastically. Therefore, the analysis of June and December temperature data indicates that the surf and ice cream shop would be sustainable throughout the week. 
