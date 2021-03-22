# PyBer_Analysis

## Project Overview
I am a data analyst at a ride-sharing startup named PyBer. Given my technical background, the CEO has asked me to run analysis on our internal 2019 ride data. The goal is to split the data into three categories - Urban, Suburban, and Rural. To run a comparative analysis across these three categories, I studied key variables such as ride fare, driver count, and total number of rides completed.

## Results
Below is a summary dataframe from the analysis:

![fig8](https://github.com/asliwinski23/PyBer_Analysis/blob/main/Resources/fig8.png)

Our results were as expected. For example, in urban areas we expect to see a higher count of rides in a year than rural. In fact, urban areas had more than 10x the ride volume compared to rural cities. However, the difference in driver counts between urban, suburban, and rural areas was much higher than expected. There are 7x more drivers in urban areas than suburban. The difference is even larger for rural vs urban driver count with there being 110x more drivers in urban areas. Fares are the highest in rural areas, which makes sense as there is such limited supply of drivers. However, it would be interesting to look at $/mi. In terms of fare, because people in rural and suburban areas are likely traveling much farther in a PyBer than those in urban areas, to make up for the mileage and resources used such as gas, rural and suburban drivers tend to make more per ride than drivers in urban areas, where driver count is much higher.

Below is a graph representing ride fare over time for urban, suburban, and rural cities:

![Fig9](https://github.com/asliwinski23/PyBer_Analysis/blob/main/Resources/Fig9.png)

This graph highlights the fact that rural areas contribute significantly less in revenue, followed by suburban, and with urban cities making up for the highest fare total. This is likely due to high demand and population density. It would be interesting to view the results for the entire 2019 year, but this graphs seems to show that suburban ride fare begins to tick up towards the end of April. As a result, I hypothesize that those who live in suburban areas tend to take more trips to their near cities as the waether begins to get warmer.

## Recommendations
After this analysis I have three main recommendations to address any disparities among the city types:
1. Review urban demand dynamics to optimize average fare. Currently, urban cities experience the highest volume of ride requests. And while the distance traveled in urban cities vs suburban and rural is mostly likely fewer miles, it would be interesting to review ride demand in urban areas, as there may be enough demand to justify raising the average cost per ride.
2. Run a driver satisfaction survey and compare the results across urban, suburban, and rural cities. Drivers in urban areas make under $1 per ride, which could lead to unsatisfied drivers who chose to may either switch to another rideshare company for compensation purposes or service suburban and rural areas more often because their profit can be significantly improved.
3. Review marketing strategies in order to identify times of year when fare is lowest and push discounted fare promotions to encourage users to go out and use our app.
