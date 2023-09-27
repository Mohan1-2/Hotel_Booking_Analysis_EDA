# Hotel_Booking_Analysis_EDA

# Problem Statement 
**"Investigating Hotel Booking Analysis: Unveiling Insights from Real-World Data"
Our project delves into a rich dataset of hotel bookings spanning from 2015 to 2017, encompassing both city and resort hotels.Our analysis aims to provide actionable insights for the hotel industry, allowing them to enhance customer experiences, optimize operations, and increase revenue. By addressing these key metrics, hotels can make data-driven decisions to thrive in a competitive market**.

# SUMMARY
**We took a close look at data about people booking hotels, like when they book and where they come from. It's like solving a puzzle. We found interesting things, like when most people book rooms and what types of rooms they like. This helps hotels make smarter choices and make their customers happier. So, by using data, hotels can do better and make more money. This study gives us a clear picture of how people book hotels, helping hotels make good decisions in a changing world**.

# Dataset
**We are given a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.**

- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.

**- Total number of rows in data: 119390**

**- Total number of columns: 32**

# Data cleaning
## Removeing Duplicate rows
All duplicate rows were dropped

# Handling null values
Null values in columns company and agent were replaced by 0.

Null values in column country were replaced by 'others'.

Null values in column children were replaced by the mean of the column.

# Converting columns to appropriate data types
Changed data type of children, company, agent to int type.

# Exploratory Data Analysis
**Performed EDA and tried answering the following questions:**

 Q1) Which agent makes the most no. of bookings?
 
 Q2) Which room type is in most demand and which room type generatesthe  highest adr?
 
 Q3) Which meal type isthe  most preffered meal of customers?
 
 Q4) What isthe  percentage of bookings in each hotel?
 
 Q5) Which is the most common channel for booking hotels?
 
 Q6) Which are the most busy months?
 
 Q7) From which country most of the guests are comin?
 
 Q8) Which hotel seems to make more revenue?
 
 Q9) Which hotel hasa  higher lead time?
 
 Q10) What is preferred stay length in each hotel?
 
 Q11) Which hotel has higher bookings cancellation rate.
 
 Q12) Which significant distribution channel has the highest cancellation percentage?
 
 Q13) What is the trend of bookings within a month?
 
 Q14) Which types of customers mostly make bookings?

**Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:**
**Bar Plot.**

**Scatter Plot.**

**Pie Chart.**

**Line Plot.**

**Heatmap**

**Box Plot**

# Univariate Analysis
**Performed univariate analysis and made following conclusions:**

 1.) Agent no. 9 has made most no. of bookings.
 
 2.) Most popular meal type is BB(Bed and Breakfast).
 
 3.) Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel.
 
 4.) Guests use different channels for making bookings out of which most preferred way is TA/TO.
 
 5.) July- August are the most busier and profitable months for both of hotels.
 
 6.) Most of the guests came from european countries, with highest number of guests from Portugal.
 
 7.) Most common stay length is less than 4 days and generally people prefer City hotel for short stay, but for long stays, Resort Hotel is preferred.

 # Conclusion

 1. The dataset has 119390 row and 32 columns
 
 2. Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.

 3. Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.

 4. Both hotels have significantly higher booking cancellation rates and very few guests less than 3 % return for another booking in City hotel. 5% guests return for stay in Resort hotel.

 5. Most of the guests came from european countries, with most of guests coming from Portugal.

 6. Guests use different channels for making bookings out of which most preferred way is TA/TO.

7. Almost 30% of bookings via TA/TO are cancelled.

8. July- August are the most busier and profitable months for both of hotels.
 

