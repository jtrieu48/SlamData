# SlamData

<img src="/imgs/NBA_Logo.png" alt="drawing" width="500" class="center"/>

A Web based data analytics application presenting the Kaggle Dataset: NBA Players by Justinas Cirtautas. 

The front end is built with HTML/CSS, Boostrap for interactive pages. The backend is hosted on a Python WSGI Server using Flask. Middleware was written in Python. 

## Usage

- ``Search`` By Player Name, Draft Year, or Season

- ``Add`` New Players

- ``Update`` Players

- ``Delete`` Players

## Additional Complexities

###Get Average Rating

    - This is a custom metric made to compile average rating of a draft round within a season

###Calculate Net Rating

    - This is a custom metric made to compare relative skill of players. Calculated using a player's total points, rebounds, and assists in the dataset. A new CSV file is created and filled to store these comparisons.

###Sequential Search

    - Sequential Search was implemented to cut down on search-time including by player name, draft year, or season.

## Demo

[SlamData Demo](https://youtu.be/40ZgcllCeBA?si=hCknt76cwsL7Jlt-)
