
# Mobile Games In App Purchases Dashboard

## [Dataset](https://www.kaggle.com/datasets/pratyushpuri/mobile-game-in-app-purchases-dataset-2025)

## Introduction

This dataset contains detailed information about mobile game players and their purchase behaviour. The dataset focuses on the classic "whales vs minnows" segmentation model, providing insights into different player spending categories and their gaming habits. 
The mobile gaming industry is different from other video game industry due to the fact that it's heavily focused on microtransactions. Based on the amount of money invested on the game, a player can be considered:
	- Free to Play Player: As it's name says, the player doesn't invest any money on the game.
	- Minnow: The player eventually invest a small amount of money.
	- Dolphin: The player usually invests money on the game.
	- Whale: The player invests a large amount of money to gain access to all the latest game content.
	
The dataset contains information about players which once invested money on the game, which means that free to play players won't appear on the dashboard.

## Column Names

Each entry of the dataset displays information about the next features:

| Column Name                     | Description                          |
| ------------------------------- | ------------------------------------ |
| `UserID`                        | Unique identifier for each user.     |
| `Age`                           | User's age in years.                 |
| `Gender`                        | User's gender identity.              |
| `Country`                       | User's country of origin.            |
| `Device`                        | Mobile platform used.                |
| `GameGenre`                     | Primary game genre played.           |
| `SessionCount`                  | Number of gaming sessions.           |
| `AverageSessionLength`          | Average session duration in minutes. |
| `SpendingSegment`               | Player spending classification.      |
| `InAppPurchaseAmount`           | Total purchase amount in USD.        |
| `FirstPurchaseDaysAfterInstall` | Days until first purchase.           |
| `PaymentMethod`                 | Preferred payment gateway.           |
| `LastPurchaseDate`              | Most recent purchase timestamp.      |

## Dashboard

### Executive Summary

<image src="images\d1.png" alt="Summary">

### Revenue Analysis

<image src="images\d2.png" alt="Revenue">

### User Behaviour

<image src="images\d3.png" alt="User">

### Game Performance

<image src="images\d4.png" alt="Game">

### Geographic & Demographic

<image src="images\d5.png" alt="Geographic">

### Engagement

<image src="images\d6.png" alt="Engagement">

## Conclusions

Interesting dataset focused on a concrete sector like mobile games. This dashboard shows plenty of curious information. 

First, the Gen X (35-44 years) is the age group which more money invests on mobile games. It could be due to the fact that younger groups usually have less money. The gender distribution its 65% male, 35% females, approximately. 

Most people play in Android devices, with a 58%/42% distribution. It's reasonable, because Android is an operating system used by different companies products. On the other hand, IOS is only used by Apple devices, which says a lot about Apple. Most people use debit card to pay, followed by PayPal, which uses the debit card too. 

The country that spends the most money in mobile games is clearly India. After India, the countries that follow spend roughly the same amount of money. The months with highest revenue for mobile games companies are April and July. The game genre that generates the most revenue is battle royales. Unlike this genre, the one with less revenue is sandbox. 

The main point of this dataset is to compare whales vs minnows/dolphins in mobile games. Only 2,6% of the players are whales, most of them are men over 35 years (Gen X & Boomers). Even if this is the case, the spending segment that generates more revenue on mobile games companies are whales.  They account for almost 60% of mobile gaming companies' revenues. Whales are not the segment that plays the most to mobile games, Dolphins are. 

Very interesting dataset about a type of market that people do not normally pay attention to. It has been very fun dataset to work to.