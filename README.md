This repository contains the Hotel Bookings Dataset, a comprehensive collection of real-world hotel reservation records that can be used for data analysis, visualization, and machine learning projects related to the hospitality industry.

📄 Dataset Overview
The dataset contains 119,390 rows and 32 columns, including detailed information about:

Booking status (canceled or not)

Guest demographics

Reservation changes

Special requests

Room types

Lead time and arrival dates

Pricing (Average Daily Rate)

Customer behavior patterns

📁 File
hotel_bookings.csv: Main dataset file in CSV format.

🧾 Column Descriptions
Column Name	Description
hotel	Hotel type: City Hotel or Resort Hotel
is_canceled	Whether the booking was canceled (1) or not (0)
lead_time	Number of days between booking and arrival
arrival_date_year	Year of arrival
arrival_date_month	Month of arrival
arrival_date_week_number	Week number of arrival
arrival_date_day_of_month	Day of arrival
stays_in_weekend_nights	Weekend nights stayed
stays_in_week_nights	Weekday nights stayed
adults, children, babies	Number of guests
meal	Type of meal booked (e.g., BB, HB, SC)
country	Country of guest origin
market_segment	Market segment (e.g., Online TA, Direct)
distribution_channel	Booking channel (e.g., TA/TO, Direct)
is_repeated_guest	Whether the guest booked previously
previous_cancellations	Past cancellations by the guest
previous_bookings_not_canceled	Past successful bookings
reserved_room_type	Reserved room type
assigned_room_type	Room type assigned at check-in
booking_changes	Number of changes to the reservation
deposit_type	Type of deposit (e.g., No Deposit, Non Refund)
agent, company	IDs for booking agent and company (if any)
days_in_waiting_list	Time spent on the waiting list
customer_type	Type of customer (Transient, Contract, Group)
adr	Average Daily Rate (revenue per room)
required_car_parking_spaces	Number of parking spaces requested
total_of_special_requests	Number of special requests (e.g., extra bed)
reservation_status	Final reservation status (Check-Out, Canceled, No-Show)
reservation_status_date	Date the status was set

📊 Potential Use Cases
Cancellation prediction models

Revenue forecasting

Guest behavior analysis

Seasonal trend analysis

Visualization and dashboard projects
