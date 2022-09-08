# Introduction
Client requested a desktop application, which provided low latency trading with custom features for their needs. To complete this project I had to research encryption methods based on the strict requirements of the API, and provide a constant connection to the server while handling disconnects/errors smoothly as to not disrupt the clients trading experience. Key features that needed to be implemented:

- Limit Orders
  - Be able to buy and sell at a certain price in the market. 
- Market Orders
  - Be able to buy and sell instantly.
- Market Close on position
  - Be able to close their current position instantly.
- Cancel Orders
  - Be able to cancel buy or sell orders instantly.
  - Be able to cancel all active orders. 
- Updating Leverage
  - Be able to update the leverage of their current position.
- Update Stop Loss
  - Be able to update their stop loss on their current position.
- Chase Orders
  - Be able to have the limit order chase the current price of the market by .50 of the mark price, and only allow to hit if going the opposite direction.
  - E.G. If a chase buy is active, only chase the price by .50 upwards until it comes down to hit the chase price.
