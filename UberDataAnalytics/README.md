
# Uber Trips Analytics Dashboard

## [Dataset](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard?select=ncr_ride_bookings.csv)

## Introduction

This comprehensive dataset contains detailed ride-sharing data from Uber operations for the year 2024, providing rich insights into booking patterns, vehicle performance, revenue streams, cancellation behaviors, and customer satisfaction metrics.

## Column Names

This dataset contains the following columns:

| Column Name                         | Description                                                                     |
| ----------------------------------- | ------------------------------------------------------------------------------- |
| `Date`                              | Date of the booking                                                             |
| `Time`                              | Time of the booking                                                             |
| `Booking ID`                        | Unique identifier for each ride booking                                         |
| `Booking Status`                    | Status of booking (Completed, Cancelled by Customer, Cancelled by Driver, etc.) |
| `Customer ID`                       | Unique identifier for customers                                                 |
| `Vehicle Type`                      | Type of vehicle (Go Mini, Go Sedan, Auto, eBike/Bike, UberXL, Premier Sedan)    |
| `Pickup Location`                   | Starting location of the ride                                                   |
| `Drop Location`                     | Destination location of the ride                                                |
| `Avg VTAT`                          | Average time for driver to reach pickup location (in minutes)                   |
| `Avg CTAT`                          | Average trip duration from pickup to destination (in minutes)                   |
| `Cancelled Rides by Customer`       | Customer-initiated cancellation flag                                            |
| `Reason for cancelling by Customer` | Reason for customer cancellation                                                |
| `Cancelled Rides by Driver`         | Driver-initiated cancellation flag                                              |
| `Driver Cancellation Reason`        | Reason for driver cancellation                                                  |
| `Incomplete Rides`                  | Incomplete ride flag                                                            |
| `Incomplete Rides Reason`           | Reason for incomplete rides                                                     |
| `Booking Value`                     | Total fare amount for the ride                                                  |
| `Ride Distance`                     | Distance covered during the ride (in km)                                        |
| `Driver Ratings`                    | Rating given to driver (1-5 scale)                                              |
| `Customer Rating`                   | Rating given by customer (1-5 scale)                                            |
| `Payment Method`                    | Method used for payment (UPI, Cash, Credit Card, Uber Wallet, Debit Card)       |

## Dashboard

### Executive Summary

<image src="images\d1.png" alt="Summary">

### Performance Analysis

<image src="images\d2.png" alt="Performance">

### Financial Analysis

<image src="images\d3.png" alt="Financial">

## Conclusions

Excellent dataset with plenty of different information to find conclusions. In this case, the information must be processed properly, because even if a field is null, it's doesn't always mean that value is null or 0. For example, if a customer doesn't rate the driver, the driver isn't a good or bad driver. If the reason for cancelling the ride is null, it means that the ride wasn't cancelled. Null values should be interpreted carefully.

Among some financial data shown by the dataset, it is found that the average income per km driven is 0.23 $. Consequently, the average income for ride is 508 $. Majority of the observations are made in India, which appears to be very different from my perspective on Spain. The rides on India tend to be much longer, increasing it's price.

Most people use Uber on afternoon or night, and they pay mostly with UPI (Unified Payments Interface). Almost 69% of the rides are completed, and cancelling reasons are either customer demand or vehicle breakdown. The number of bookings per month fluctuates between 11k & 13k.

Great dataset to analyse Uber services. Deeper research can be done. Very important to make a good interpretation of the data, or the information taken will be far from reality.