# TechnoTuners
Project
You are required to construct a trade recommendation system based on Arbitrage opportunity between BSE and NSE (from Nifty stocks),

User logs in to system with a username and a password. (You do not need a registration module – rather you can have a predefined set of users in Database against which authentication is done)
Once logged in, market data should be used to take the Nifty stocks and their prices on the BSE and the NSE. On the basis of the of the difference between the two prices a set of recommendations should be made where arbitrage opportunities exist..
For these stocks, use live market data (like Yahoo Finance API) and as output display key statistics alongside suggestions.
User can select to save any of the recommended arbitrage trades with quantity and current market price. The Data should be persisted in DB so that the data is not lost after the user closes the browser.
When the user logs in again the user should be able to see the saved stocks and stats.
Use an appropriate DB (like Oracle) for persistence, Business logic on application server with a Single Page Web Application (connected using REST API).
