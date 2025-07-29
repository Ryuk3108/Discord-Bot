# Discord bot 
This is a discord bot that fetches the live data from the game "Airline Manager 4".
It gives a regular update on the fuel/co2 prices in the discord server that it is added in.

## Features
- Live updates from the game, every 30 minute interval, when the price changes, the server is updated with the new prices. 
- When playing the game, it's difficult to keep checking the price change every 30 mins to determine the lowest price to purchase the fuel/co2.
  This bot gives the regular updates and helps saving in game currency on expenses.

## Tech Stack / Tools Used
- Python
- `discord.py` / `requests` 
- 'Discord bot token' / 'channel ID integration' / 'AM4 cookies and url' / 'beautifulsoup' for webscraping

## How It Works
- Fetches live prices from the AM4 website
- scrapes the website and uses the particular url of fuel and co2 using beautifulsoup
- gives out text based data inside the server based on the threshold described inside the script. 

## Example Use Case
Anyone playing the game and wanting to scale up inside the game, would need to manage their costs on the fuel and co2, two essential in-game items.
So they can use this bot to fetch prices, and decide when they want to fill up their quotas and fuel
Example: Every 30 minutes, when the fuel and co2 prices changes in-game, it gives an update when they fall below the threshold of "Fuel:1200 and CO2:150"
