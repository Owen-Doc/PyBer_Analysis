# PyBer_Analysis
# Analysis Overview
The purpose of this analysis is to provide insights to the PyBer team on understand their customers needs, drivers needs, and utilization rates of their ride sharing app. The data source was shown with ride data for the city, date, total fare, a unique ride id number, as well as the number of drivers in each city. I used this data to calculate total ride volume for each type of city, average fare per ride, number of drivers per type of city, and the average fare per driver.  PyBer has segmented their data into rides in urban, suburban, and rural cities. I show a basic summary of the fare and ride breakdown into a dataframe, displayed below. The PyBer team can use this analysis to accurately allocate funding, investment, and resources into higher volume types of cities. 

# Results
Below is the summary data frame that I created to summarize the ride data by type of city.

<img width="603" alt="fare_summary_df" src="https://user-images.githubusercontent.com/76958825/111841844-f59bba00-88d4-11eb-87b2-07197224b0e3.png">

In my analysis, I find a vast difference in ride and fare total volume in each of these segments. Urban cities, as expected, made up the vast share of the total rides, and produced the highest revenue. However, since these rides are typically shorter in length and distance, urban rides also on average had the lowest fare per rider at $24.54 per ride. Suburban rides generated $19,346 in the period, $20,000 less than their urban counterparts. Additionally, since urban cities also had the highest number of drivers, the average fare per driver for urban cities is $16.57, significantly lower than in rural or suburban. I also note that urban cities have significantly more drivers than they did rides. This means that a considerable number of drivers did not give any rides in this period. Rural drivers, despite their relatively low count, enjoyed the highest average fare per driver of the cohort, at $55.49 average fare per driver. 

In the second part of my analysis, I investigate trends from January to April in each of the three city types. That chart is shown below.

img width="603" alt="pyber_fare_summary" src="https://user-images.githubusercontent.com/76958825/111844049-a35c9800-88d8-11eb-8de8-199b0bf9f33c.png">


As we see in the chart, business in all types of cities tended to trend together. Each saw a healthy increase in business coming into March, then a decline, and a correction towards the end of April. This may be attributed to the weather changing and increased community activity that people needed rides to get to. Additionally, this chart is illustrative of the relative size of each business unit. Even at suburban cities' highest peak, these fares never even reached the lowest value of urban fares. Weekly suburban fares peaked at late February at approximately $1400. Urban fares peaked at $2500 the same week. Rural fares also increased that week, but saw their peak at just over $500 in April week 1. I also note that Urban and Suburban cities had their worst performing months in January week 1. Clearly, in terms of demand for rides, there is some relationship between suburban and urban cities that requires further investigation.

# Recommendations
I outline 3 business recommendations for the PyBer team to act on based on this data. 
1. Onboarding and recruiting drivers is an expensive process. In urban cities, it appears that there are a considerable number of inactive drivers. I advise that you take a look at individual driver metrics in this group to reward the drivers that are carrying the most rides, and incentivize or terminate drivers with low ride counts. 
2. Urban fares account for a lot of your revenue compared to other city types. I advise that you invest more resources in marketing, support, and infrastructure, to further capitalize on this strong market. The results from this market are a clear indication that the business is viable in urban communities.
3. Rural communities are more likely to own a car as simple errands and commutes require car travel. As of now, rural cities are not driving a large part of the business, and we want to be sure that our cost structure reflects this. If it is still considered a growing market for PyBer, look at both rider and driver promotional materials and marketing campaigns to establish reach in these communities. Resources may generate more return if invested in urban and suburban markets as those have demonstrated strong performance. 
