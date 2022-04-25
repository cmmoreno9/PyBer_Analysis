# PyBer Analysis

## 1) Overview of the analysis 

During this assingment, the goal was to implement both Python, Pandas, and Matplotlib to analyze the ride-sharing data by city type. Additionally, by utlizing Matplotlib, creation of a multiple-line graph that showcases the total weekly fares for each city type. This allows for evaluation of each city type (urban, rural, and suburban) and ability to compare between the three. 

## 2) Results 

![thisisanimage](https://github.com/cmmoreno9/PyBer_Analysis/blob/2ce6470f022db7a7972c5187d970931795835a19/analysis/PyBer_fare_summary.png)

- The highest total fares were in Urban areas, which was to be expected. However, Urban areas also expressed the lowest average fare per ride and average fare per driver. 
- Rural areas had the lowest number of drivers of 78, and hititng the highest fares per driver and ride. Yet, due to lower demand there was less total rides that was represented by the lowest total fare of $4,327.93. 
- Subarban areas met a middle ground between rural and urban PyBer rides. They had a total of 490 drivers and an avg fare per ride of $30.97 and avg fare per driver of $39.50. 
- Urban areas exhibit the lowest avg fare per driver/ride while Rural areas are far more expensive. 

![thisisanimage](https://github.com/cmmoreno9/PyBer_Analysis/blob/1775c942a549fe94f71529094059bd171ed7eeb1/analysis/Screen%20Shot%202022-04-24%20at%208.10.39%20PM.png)

## 3) Recommendations
- One reccomendation is to increase urban area costs dependent on demand changes that day. Although we see changes throughout the months, it may be more beneficial to see it throughout the day, to determine high cost times. Having a set cost the whole day will leave money on the table and it is necessary to optimize. 
- Urban areas are the only city type that has more total drivers than total rides. Thus, some drivers are not as productive or are innactive from the role. If innactive they must be removed from the analysis as the data will become unrepresentative from reality. Additionally, there should be an achievable quota for each driver to maximize number of rides. 
- To offset the extreme finicancial differences from rural areas, it may be beneficial to raise prices (possibly 5%) for Suburban and Urban areas as there is much more demand in these areas. In turn this will help alieviate the disparity in rural areas. Analysis in optimal price raises will need to take place. 
