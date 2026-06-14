# Delhivery Feature Engineering

## About Delhivery
Delhivery is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.

The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

## Business Problem
The company wants to understand and process the data coming out of data engineering pipelines:

• Clean, sanitize and manipulate data to get useful features out of raw fields

• Make sense out of the raw data and help the data science team to build forecasting models on it

## Insights
1. The data is given from the period '2018-09-12 00:00:16' to '2018-10-08 03:00:24'.

2. There are about 14817 unique trip IDs, 1508 unique source centers, 1481 unique destination_centers, 690 unique source cities, 806 unique destination cities.

3. Most of the data is for testing than for training.

4. Most common route type is Carting.

5. The names of 14 unique location ids are missing in the data.

6. The number of trips start increasing after the noon, becomes maximum at 10 P.M and then start decreasing.

7. Maximum trips are created in the 38th week.

8. Most orders come mid-month. That means customers usually make more orders in the mid of the month.

9. Most orders are sourced from the states like Maharashtra, Karnataka, Haryana, Tamil Nadu, Telangana

10. Maximum number of trips originated from Mumbai city followed by Gurgaon Delhi, Bengaluru and Bhiwandi. That means that the seller base is strong in these cities.

11. Maximum number of trips ended in Maharashtra state followed by Karnataka, Haryana, Tamil Nadu and Uttar Pradesh. That means that the number of orders placed in these states is significantly high.

12. Maximum number of trips ended in Mumbai city followed by Bengaluru, Gurgaon, Delhi and Chennai. That means that the number of orders placed in these cities is significantly high.

13. Most orders in terms of destination are coming from cities like bengaluru, mumbai, gurgaon, bangalore, Delhi.

14. Features start_scan_to_end_scan and od_total_time(created feature) are statistically similar.

15. Features actual_time & osrm_time are statitically different.

16. Features start_scan_to_end_scan and segment_actual_time are statistically similar.

17. Features osrm_distance and segment_osrm_distance are statistically different from each other.

18. Both the osrm_time & segment_osrm_time are not statistically same.

## Recommendations
1. The osrm trip planning system needs to be improved. Discrepancies need to be catered for transporters, if the routing engine is configured for optimum results.

2. The osrm_time and actual_time are different. Team needs to make sure this difference is reduced, so that better delivery time prediction can be made and it becomes convenient for the customer to expect an accurate delivery time.

3. The osrm distance and actual distance covered are also not same i.e. maybe the delivery person is not following the predefined route which may lead to late deliveries or the osrm devices is not properly predicting the route based on distance, traffic and other factors. Team needs to look into it.

4. Most of the orders are coming from/reaching to states like Maharashtra, Karnataka, Haryana and Tamil Nadu. The existing corridors can be further enhanced to improve the penetration in these areas.

5. Customer profiling of the customers belonging to the states Maharashtra, Karnataka, Haryana, Tamil Nadu and Uttar Pradesh has to be done to get to know why major orders are coming from these atates and to improve customers' buying and delivery experience.

6. From state point of view, we might have very heavy traffic in certain states and bad terrain conditions in certain states. This will be a good indicator to plan and cater to demand during peak festival seasons.

7. Improving accuracy in estimated delivery times and distances can contribute to increased customer satisfaction.

8. Collaborate with relevant stakeholders, including government authorities, transportation companies, and local communities, to develop and implement comprehensive strategies for managing and optimizing transportation in the identified busy corridors and cities.

9. Fine-tuning logistics planning based on more accurate measurements can lead to better resource allocation and potentially reduce operational costs.

10. Overall, the analysis hints at potential areas for operational improvement. Businesses could focus on refining their route planning algorithms, addressing discrepancies in estimated times and distances, and streamlining processes between different stages of delivery to enhance overall operational efficiency.
