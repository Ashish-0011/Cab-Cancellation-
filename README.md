# Cab-Cancellation
Cab Cancellation ML Prediction Problem

The business problem tackled here is trying to improve customer service for YourCabs.com, a cab company in Bangalore.
The problem of interest is booking cancellations by the company due to unavailability of a car. The challenge is that cancellations 
can occur very close to the trip start time, thereby causing passengers inconvenience.

## Goal
The goal of the competition is to create a predictive model for classifying new bookings as to whether they will eventually gets cancelled due to car unavailability.

## Parameters
<ul>
<li>id - booking ID
<li>user_id - the ID of the customer (based on mobile number)
<li>vehicle_model_id - vehicle model type.
<li>package_id - type of package (1=4hrs & 40kms, 2=8hrs & 80kms, 3=6hrs & 60kms, 4= 10hrs & 100kms, 5=5hrs & 50kms, 6=3hrs
& 30kms, 7=12hrs & 120kms)
<li>travel_type_id - type of travel (1=long distance, 2= point to point, 3= hourly rental).
<li>from_area_id - unique identifier of area. Applicable only for point-to-point travel and packages
<li>to_area_id - unique identifier of area. Applicable only for point-to-point travel
<li>from_city_id - unique identifier of city
<li>to_city_id - unique identifier of city (only for intercity)
<li>from_date - time stamp of requested trip start
<li>to_date - time stamp of trip end
<li>online_booking - if booking was done on desktop website
<li>mobile_site_booking - if booking was done on mobile website
<li>booking_created - time stamp of booking
<li>from_lat - latitude of from area
<li>from_long - longitude of from area
<li>to_lat - latitude of to area
<li>to_long - longitude of to area
<li>Car_Cancellation (available only in training data) - whether the booking was cancelled (1) or not (0) due to unavailability of a car.

