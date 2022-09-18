# Statistical Arbitrage for Sports Betting Project

<p align="center">
  <img src="https://user-images.githubusercontent.com/113403062/190924275-629eaf18-183c-4781-81a2-fd0337143ba9.jpg" alt="animated"/>
</p>

*Above is an example of what the output Excel file may look like.*

This project was made in March 2022. In this project, I utilize the **Live Sports Odds API** (https://the-odds-api.com/) to find statistical arbitrage opportunities in upcoming sporting events across the world. For sports betting purposes, an arbitrage opportunity is when two books are offering such distinct odds that if a bettor makes a particular bet with one book and another particular bet with the other book, they can hedge their bets in such a way that they will be guaranteed to make a profit. 

The **Live Sports Odds API** is a free, open source API that tracks the current odds of essentially any given sporting event that is offered by books across the United States. With data from the API, the program is able to find all possible artbitrage opportunieis across upcoming sporting events that are offered by books in the United States. Once these calculations have been made, the program outputs all arbitrage opportunities in an Excel file for the bettor to access. This file includes the **ID** and **Sport Key** (both of which are specific metrics to the Live Sports Odds API), along with the **Expected Earnings, Bookmaker, Name, Odds**, and **Amount to Buy** for each respective bet. Each row in the file represents one artbitrage opportunity.

All of the code for this program is included in the **Arbitrage.ipynb** file. Each chunk of code is commented so that the user knows exactly what is happening in each step of the program.
