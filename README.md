# Bluey EURUSD h1

This is the code for the Bluey EURUSD h1 forex robot, created by the Forex Robot Easy Team. This code is an example of how the robot works and can be used as a reference for understanding the product. Please note that ForexRobotEasy is not the official developer of this product. To find the official developer of this product, please use MQL5.

## Input Parameters

- LotSize: The trading lot size for each trade. Default value is 0.01.
- StopLoss: The stop loss level in pips. Default value is 100.
- TakeProfit: The take profit level in pips. Default value is 200.

## Global Variables

- Bid: The current bid price.
- Ask: The current ask price.
- EntryPrice: The price at which a trade is entered.

## Custom Indicator Initialization Function

The `OnInit()` function is called when the indicator is initialized. In this function, the indicator is registered and the index buffers are set for drawing lines on the chart.

## Custom Indicator Iteration Function

The `OnCalculate()` function is called for each new tick. In this function, the current bid and ask prices are calculated. If the market price crosses above the previous high, a buy trade is placed. If the market price crosses below the previous low, a sell trade is placed.

## Custom Trading Class

The `Trade` class contains static functions for executing buy and sell trades. These functions are called from the `OnCalculate()` function when a trade is to be executed. The code for executing the trades is not provided in this example.

For detailed reviews and trading results of this product, please visit [https://forexroboteasy.com/forex-robot-review/bluey-eurusd-h1-review-unbiased-forex-software-examination/](https://forexroboteasy.com/forex-robot-review/bluey-eurusd-h1-review-unbiased-forex-software-examination/). Please note that ForexRobotEasy is not the official developer of this product. We only show sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
