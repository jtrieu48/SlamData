# SlamData
![NBA Logo](https://seuladogeek.com.br/wp-content/uploads/2022/02/NBA-logo-download-800x450.png)


## Description
SlamData is a web based data analytics application presenting the Kaggle Dataset: NBA Players by Justinas Cirtautas. 

## Prerequisites

Frameworks Used: Flask, Bootstrap

Server: Web Server Gateway Interface(WSGI) to host Python Server

Languages Used: HTML, CSS for web page structure, Python

## Functions

![Demo Screenshot](https://lh3.googleusercontent.com/keep-bbsk/AAAetVI_-7DBcjZU7T3eP00nRb9kveIKvYUCiyEelMLaupnpQrQAHSbuS7Gk-uiVMFZ2olj-Ova9mzIL8-dLcIflWGDZuL0MPxFE7UtbPI7LIyrHBgSM=s1690)
<img src="https://lh3.googleusercontent.com/keep-bbsk/AAAetVI_-7DBcjZU7T3eP00nRb9kveIKvYUCiyEelMLaupnpQrQAHSbuS7Gk-uiVMFZ2olj-Ova9mzIL8-dLcIflWGDZuL0MPxFE7UtbPI7LIyrHBgSM=s1690" width="200" height="100">

### Search By Player Name
Searches and retrieves data from CSV file based on player name, including all played seasons in player's career 

### Search by Draft Year
Search and retrieves data based on player's draft year

### Search by Season
Search and retrieves data based on game season

### Add Player
Allows for new entries of existing and new players.
User is prompted to fill in all of player's information: Name, Season, Draft, etc.

## Additional Complexities

### Net Rating
This is a custom metric made to compare relative skill of players. Calculated using a player's total points, rebounds, and assists in the dataset. A new CSV file is created and filled to store these comparisons.

### Sequential Search
Sequential Search was implemented to cut down on search-time including by player name, draft year, or season.
