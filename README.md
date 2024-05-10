# Hotel Booking Data - Exploratory Data Analysis

In the hospitality industry, understanding customer booking behavior is crucial for operational and strategic planning. Hotels need to identify the optimal times of year to adjust room rates, the most effective length of stay for promotions, and the likelihood of special requests to enhance guest experiences. This project seeks to analyze a comprehensive dataset of hotel bookings to uncover insights that will help in predicting booking trends, customer preferences, and potential cancellation patterns. The goal is to provide actionable recommendations that hotels can implement to increase bookings, reduce cancellations, and personalize guest experiences, thereby improving overall profitability and customer satisfaction.

The primary objective of this project is to analyze hotel booking data to optimize hotel management and marketing strategies by identifying patterns and key factors that influence booking behaviors. Understanding booking trends, hotels can help optimize hotel operations, pricing strategies, and customer satisfaction. By analyzing the dataset, we aim to uncover patterns that can assist in decision-making processes related to booking management.

## Data Understanding: 
The hotel bookings dataset contains various attributes regarding hotel bookings made by the customers.
The above dataset has 119,391 rows and 32 columns.
Hotel : City hotel and Resort hotel
is_cancelled : if the booking was cancelled (1) or not (0)
lead_time : Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
arrival_date_year : Year of the arrival date
arrival_date_month : Month of the arrival date
arrival_date_week_number : Week number for arrival date
arrival_dat_day : Day of arrival date
stays_in_weekend_nights : Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
stays_week_nights : Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
adults : Number of adults
children : Number of children
babies : Number of babies
meal : Kind of meal opted for
country : Country Code
market_segment : Which segment the customer belonged to
is_repeated_guest : Guest coming for first time or not
previous_cancellation : Was there a cancellation before
previous_bookings : Count of previous bookings
reserved_room_type : Type of room reserved
assigned_room_type : Type of room assigned
booking_changes : Count of changes made to booking
deposit_type : Type of deposit
agent : Booked through agent (code or NULL)
days_in_waiting_list : Number of days in waiting list
customer_type : Type of customer
required_car_parking : If car parking is required
total_of_special_req : Number of additional special requirements
reservation_status : Status of the reservation
reservation_status_date : Date of specific status
