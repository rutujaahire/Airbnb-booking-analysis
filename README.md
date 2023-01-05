# Airbnb-booking-analysis
Analyzing  the data from 2008-2019
Airbnb as in ‘Air in Bed and Breakfast’ is an online business where the property owners rent out-
their spaces to people looking for a place to stay. Airbnb offers travellers an easy, relatively stress-
free way to earn some income from their property. 


![image](https://user-images.githubusercontent.com/107872228/210801467-4fa40477-d5af-42f4-8be3-bd39817d10a4.png)


In the Airbnb NYC 2019 dataset we were provided with 16 features i.e., id, name, host_id, host_name, neighbourhood_group, neighbourhood,
latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review,
reviews_per_month, calculated_host_listings_count, availability_365.

In the first step, we imported the required libraries such as pandas, numpy, matplotlib, seaborn etc.
Then we performed the data cleaning process by dropping the non-relevant features from the
dataset such as name and last_review. After that, we replaced all NaN or null values in the dataset
from the features which had them. Once we were sure that the data had no null values we proceed.

The next step was data visualization, which involved plotting the data we had gathered from the
dataset in the form of tables and graphs. The different types of plots included bar graph, pie chart,
scatter plot, box plot etc. We gave our verdicts after each plot as in which were the distinct
characteristics and patterns we could figure out from the plots.

In Exploratory Data Analysis (EDA) we tried to analyze the data according to the problem
statements that we were given. The majority of the analysis revolved around the hosts, different
neighbourhood groups, different neighbourhoods, reviews on the listings etc. We studied all the data
statistically and also tried to make sense out of the data from a geographical point of view
