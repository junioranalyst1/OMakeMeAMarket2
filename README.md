# OMakeMeAMarket

OMakeMeAMarket is a market making game (https://en.wikipedia.org/wiki/Market_maker).  In this game, you act as the market maker for three traders, each with their own trading strategy.  The market maker and each trader roll one standard six-sided dice.  The Market Maker must provide continuous bid/ask quotes on the sum of all dice.  There are ten rounds of trading, and at the end, the sum of the dice is revealed, and the market maker's profit is calculated.  As usual, the objective of the game is to maximize profit. 



## Installation
Requires OCaml.

Clone this repository
```
git clone https://github.com/sameerlal/OMakeMeAMarket
cd OMakeMeAMarket
```

To play, run the following
```
make clean && make build && make play
```



## Credit

@Sameerlal, CS 3110 Final Project, Spring 2019.  
Libraries used developed by @JaneStreet