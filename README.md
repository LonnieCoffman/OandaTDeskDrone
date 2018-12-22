# Oanda TDesk Drone

An MT4 Expert Advisor built for [TDesk](http://www.stevehopwoodforex.com/phpBB3/viewtopic.php?f=106&t=5522) and based on [Desky](http://www.stevehopwoodforex.com/phpBB3/viewtopic.php?f=106&t=5545).  This EA reads signals from TDesk and places trades on Oanda's FXtrade platform using the included python script.  Data is passed back and forth from MT4 to Python via reading and writing of files.  The forum thread for this EA is located [here](http://www.stevehopwoodforex.com/phpBB3/viewtopic.php?f=106&t=5588). 

## What are the advantages of this EA?

1. Provides traders the ability to trade any size. Trades can be as small as 1 unit. This would be the equivalent of 0.00001 within Empty4. This allows systems that trade a large number of pairs or trades to be run on a small account.

2. Using 2 accounts, one for short trades and one for long trades, gives U.S. traders the ability to use a form of hedging. Since the accounts would vary in size over time, occasional rebalancing of accounts by transferring funds from one account to the other would be necessary.

3. In the U.S. there are different margin requirements for each pair. This EA has the ability to automatically calculate lot sizes based on this and other variables.

![](https://raw.githubusercontent.com/LonnieCoffman/OandaTDeskDrone/master/Dashboard.png)

## Getting Started

The attached user manual, OandaTDeskDrone-Manual.pdf, has installation instructions and explanations of all of the configuration options within the EA.

## Acknowledgments

* Thank you to Steve Hopwood, Thomas and all the others at [Steve Hopwood Forex] whose code I was inspired by and for the functions that I have borrowed.  All citations of the work of others is documented within the code.
