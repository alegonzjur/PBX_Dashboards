# PBX_Dashboards

Uploading personal PowerBI dashboards. These dashboards are made to improve my PowerBI abilities and analytical skills.

## US Houses Sales [Dataset]()

### Introduction

Classic dataset for the begginers in data analysis and predictive models. It contains 3000 entries about sales from houses in the United States.

### Features

- **Price:** Selling price of the house ($). Float type.
- **Address:** House address. String type.
- **City:** House location. String type.
- **Zipcode:** Zipcode of the city. Integer type.
- **State:** State of the US where the city is located. String type.
- **Bedrooms:** Number of bedrooms of the house. Integer type.
- **Bathrooms:** Number of bathrooms of the house. Integer type.
- **Area (Sqft):** Covered area by the house in Sqft. Integer type.
- **Lot Size (Sqft):** Covered area non built in the house (Sqft). Integer type.
- **Year Built:** Construction year. Integer type.
- **Days on Market:** Number of days the house has been on the market.
- **Property Type:** Type of house. String type.
- **MLS ID:** Agent ID. String type.
- **Listing Agent:** Agent name. String type.
- **Status:** Indicate if the house has been sold or not. String type.
- **Listing URL:** Link to the house on internet. String type.

### Conclusions

It's a good dataset to start in data analysis thanks to all the different features that it has and it's easy understanding of the concept. Some conclusions that i've taken from the dashboard are that average price doesn't vary greatly according to the different values of certain variables, such as bathroom number, bedroom number, property type, state... The SQFT Price is almost similar in every city, and construction year does not follow a pattern in the final price. It's difficult to extract key information, but for getting started into data anaylsis, it is an acceptable dataset.


## Netflix Stock Price History [Dataset](https://www.kaggle.com/datasets/adilshamim8/netflix-stock-price-history/data)

### Introduction

This dataset offers a comprehensive historical record of Netflix's stock price movementes, capturing the company's finantial journey from it's early days to its position as a global streaming giant.

### Features

- **Date** – The trading day (from 2002 onward)
- **Open** – Stock price when the market opened
- **High** – Highest trading price of the day
- **Low** – Lowest trading price of the day
- **Close** – Final price at market close
- **Adj Close** – Closing price adjusted for splits and dividends
- **Volume** – Number of shares traded that day

### Conclusions

This kind of datasets need more administrative or stock experience to take away significant findings. You can see clearly in charts how much the company has grown, and it's ups and downs, which can be related to actions taken by the company, such as shared accounts block, or worldwide moments, like COVID lockdown. The dataset is focused on the stock value, therefore there aren't much conclusions to rescue.

## Mobile Games In-App Purchases [Dataset](https://www.kaggle.com/datasets/pratyushpuri/mobile-game-in-app-purchases-dataset-2025)

### Introduction

This dataset contains detailed information about mobile game players and their purchase behaviour. The dataset focuses on the classic "whales vs minnows" segmentation model, providing insights into differente player spending categories and their gaming habits. 
The mobile gaming industry is different from other video game industry due to the fact that it's heavily focused on microtransactions. Based on the amount of money invested on the game, a player can be considered:
	- Free to Play Player: As it's name says, the player doesn't invest any money on the game.
	- Minnow: The player eventually invest a small amount of money.
	- Dolphin: The player usually invests money on the game.
	- Whale: The player invests a large amount of money to gain access to all the latest game content.
	
The dataset contains information about players which once invested money on the game, which means that free to play players won't appear on the dashboard.

### Features

13 columns covering user demographics, gaming behavior, and transaction data:
*UserID, Age, Gender, Country, Device, GameGenre, SessionCount, AverageSessionLength, SpendingSegment, InAppPurchaseAmount, FirstPurchaseDayAfterInstall, PaymentMethod, LastPurchaseDate*.

### Conclusions

Interesting dataset focused on a concrete sector like mobile games. This dashboard shows plenty of curious information. 

First, the Gen X (35-44 years) is the age group which more money invests on mobile games. It could be due to the fact that younger groups usually have less money. The gender distribution its 65% male, 35% females, approximately. 

Most people play in Android devices, with a 58%/42% distribution. It's reasonable, because Android is an operating system used by different companies products. On the other hand, IOS is only used by Apple devices, which says a lot about Apple. Most people use debit card to pay, followed by PayPal, which uses the debit card too. 

The country that spends the most money in mobile games is clearly India. After India, the countries that follow spend roughly the same amount of money. The months with highest revenue for mobile games companies are April and July. The game genre that generates the most revenue is battle royales. Unlike this genre, the one with less revenue is sandbox. 

The main point of this dataset is to compare whales vs minnows/dolphins in mobile games. Only 2,6% of the players are whales, most of them are men over 35 years (Gen X & Boomers). Even if this is the case, the spending segment that generates more revenue on mobile games companies are whales.  They account for almost 60% of mobile gaming companies' revenues. Whales are not the segment that plays the most to mobile games, Dolphins are. 

Very interesting dataset about a type of market that people do not normally pay attention to. It has been very fun dataset to work to.

## Uber Data Analytics [Dataset](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard?select=ncr_ride_bookings.csv)


### Introduction

This comprehensive dataset contains detailed ride-sharing data from Uber operations for the year 2024, providing rich insights into booking patterns, vehicle performance, revenue streams, cancellation behaviors, and customer satisfaction metrics.

### Features 

The dataset contains the following columns:

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


### Conclusions

Excellent dataset with plenty of different information to find conclusions. In this case, the information must be processed properly, because even if a field is null, it's doesn't always mean that value is null or 0. For example, if a customer doesn't rate the driver, the driver isn't a good or bad driver. If the reason for cancelling the ride is null, it means that the ride wasn't cancelled. Null values should be interpreted carefully.

Among some financial data shown by the dataset, it is found that the average income per km driven is 0.23 $. Consequently, the average income for ride is 508 $. Majority of the observations are made in India, which appears to be very different from my perspective on Spain. The rides on India tend to be much longer, increasing it's price.

Most people use Uber on afternoon or night, and they pay mostly with UPI (Unified Payments Interface). Almost 69% of the rides are completed, and cancelling reasons are either customer demand or vehicle breakdown. The number of bookings per month fluctuates between 11k & 13k.

Great dataset to analyse Uber services. Deeper research can be done. Very important to make a good interpretation of the data, or the information taken will be far from reality.