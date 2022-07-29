# Hotel Booking Analysis
Hotel bookings depend on many factors such as type of hotels, seasonality, days of week, meals available, parking spaces, charges etc. Hence analysing the patterns available in the past data is very important to help the hotels plan well accordingly in order to benefit the business. The given data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, the number of adults, children, and/or babies, and the number of available parking spaces etc, we tried to understand the customer’s’ behaviour and useful patterns in the data to help hotel managements improve the business by taking better decisions. The sequence of processes carried out to analyse the data is mentioned below:

## Data Preparation:
It includes basic inspection on the raw data, Data Cleaning by handling missing values. We also treated outliers first by capping method, we defined some thresholds to cap some of the categorical features, then we handled the outliers in remaining features by standard IQR method, after that we did some feature engineering in order to understand the patterns in latent features.

## EDA:
We performed univariate, Hotel Wise comparison, bivariate, multivariate and correlation analysis by plotting some visualizations and data wrangling to find out useful insights and make overall inferences to reach to a conclusion. 

### We encountered following patterns in the given historical data: 

* Top Hotel - City Hotel. Top Agent - Agent No. 9. Top room type - A 
* One out of every three bookings are cancelled.
* People prefer to tour more in August.
* Most preferred meal is BB (Bread and Breakfast.
* Online marketing is the best way to attract customers.
* People do not want to pre-deposit the money for booking.
* Only 10% of people require parking space.
* Most of the visitors are couples.
* The Resort hotel is preferred mostly for longer stays, day time stays. and when the parking space is needed.
* More than 15 days advance bookings have high chances of cancellation.
* Assigning a different room is not a reason for cancellation.
* Direct bookings have very less cancellation%.
* Best time to book a hotel is in January.
* Average days in advance booking: 77 days 
* Average nights spent by visitors: 3.
* Most visitors are from Portugal, Britain, France, Spain and Germany.
* Total Special requests and the revenue depends more on total members arrived. 

### In this project, we also analysed the factors affecting the hotel bookings which may be useful to predict the future bookings, cancellations and number of special requests.
