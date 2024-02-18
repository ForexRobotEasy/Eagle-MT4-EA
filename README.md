# Eagle MT4 EA ReadMe

This ReadMe file provides a brief overview of the Eagle MT4 EA code and how it works. Please note that ForexRobotEasy is not the official developer of this product. We are only showcasing a sample code that can work as described in this product. For detailed reviews and trading results of the Eagle MT4 EA, please visit [this link](https://forexroboteasy.com/forex-robot-review/eagle-mt4-ea-review-mastering-forex-with-hedging-grid-strategy/).

## Overview
The Eagle MT4 EA is an expert advisor developed by the Forex Robot Easy Team. It is designed to automate trading strategies using a hedging grid strategy. The EA analyzes the market direction and opens buy or sell orders based on user-defined settings.

## Global Variables
- `lotSize`: Specifies the default lot size for the orders.
- `profitTarget`: Specifies the default profit target for the strategy.
- `tradeBoth`: Specifies whether to trade both buy and sell orders or only one direction.
- `profitFromAll`: Specifies the profit setting to take profit from all orders.

## Functions
- `OnInit()`: This function is called when the EA is initialized and returns `INIT_SUCCEEDED`.
- `OnTick()`: This function is called on every tick of the market data. It checks the market direction, profit target, trade option, and executes orders accordingly.
- `AnalyzeMarketDirection()`: This function implements the logic to analyze the market direction and returns `true` if the market is going up, and `false` if the market is going down.
- `OpenBuyOrder()`: This function implements the logic to open a buy order with the lot size specified by the user.
- `OpenSellOrder()`: This function implements the logic to open a sell order with the lot size specified by the user.
- `IsProfitTargetReached()`: This function implements the logic to check if the profit target is reached and returns `true` if the profit target is reached, and `false` otherwise.
- `RestartStrategy()`: This function implements the logic to restart the strategy from the beginning.
- `UpdateAccountBalance()`: This function updates the account balance based on the profit generated.
- `OnDeinit(const int reason)`: This function is called when the EA is removed and can be used to clean up resources.

## Product Description
The Eagle MT4 EA is a powerful expert advisor developed by the Forex Robot Easy Team. It utilizes a hedging grid strategy to automate trading in the forex market. With its advanced market analysis and order execution logic, the EA aims to generate consistent profits for traders.

Key Features:
- Hedging grid strategy: The EA uses a grid-based approach to open buy and sell orders, taking advantage of market fluctuations.
- Customizable settings: Users can adjust the lot size, profit target, trade option, and profit setting according to their trading preferences.
- Market analysis: The EA analyzes the market direction to determine the appropriate type of order to open.
- Profit target tracking: The EA continuously monitors the profit target and restarts the strategy if the target is reached.
- Account balance management: The EA updates the account balance based on the profit generated, ensuring proper risk management.

Please note that this is just a sample code and not the official product. To find the official developer of the Eagle MT4 EA, please use the MQL5 platform.
