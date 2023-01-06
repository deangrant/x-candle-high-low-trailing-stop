# X Candle High / X Candle Low Trailing Stop Technique

This technique uses a set amount of closed candles in the direction of the trade to determine where to move the stop loss.

A good number of candles for this technique is 2 or 3. The more candles you use, the more room you give the market to move. The lower number of candles you use, the more closely you are following price action. For this example, let’s use 3 candles.

For a BUY trade, you use the lowest low of the past 3 closed candles as the area to move your stop. In a SELL trade, you use the highest high of the past 3 closed candles as the area to move the stop. Whenever a candle closes there is the potential to move the stop. Only move the stop in the direction of the trade.
