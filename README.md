# Financial Planner

## Motivation
This homework imitates the working of a simple personal financial planner that can provide users with insight into the value of their individual holdings and aggregate value of their portfolio. The application also runs 500 simulations to forcast the hypothetical future performance of the porfolio over 30, 5, and 10 years to give users insight into the potential growth of their retirement portfolio with a confidence of 95% based on historical data. It is important for users to recognize that market events can cause drastic departures from forecasted performance of their portfolios. 

## API Used
* The Alpaca Markets API was used to pull stocks and bonds information.
* The Alternative Free Crypto API was used to retrieve Bitcoin and Ethereum prices. 

## Noteable Results
* There is a 95% chance that an initial investment of $20000 in the portfolio over the next 30 years will end within in the range of $68168.65 and $724105.96.
* There is a 95% chance that an initial investment of $60000 in the portfolio over the next 5 years will end within in the range of $56304.57 and $154259.89.
* There is a 95% chance that an initial investment of $60000 in the portfolio over the next 10 years will end within in the range of $68932.18 and $253760.68.

## Future Works
This financial planner will be improved to not only run more simulations but also analyze custom portfolios that account for periodic rebalancing and optimization based on Sharpe ratios. 
