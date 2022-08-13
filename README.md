# TriexDev - SuperBuySellTrend (SBST) TradingView Trend Indicator

[TradingView script link](https://www.tradingview.com/script/lz0rpQtQ-TriexDev-SuperBuySellTrend/)

## What is ATR?
The average true range (ATR) is a technical analysis indicator, which measures market volatility by decomposing the entire range of an asset price for that period.

The true range indicator is taken as the greatest of the following:
- current high - the current low;
- the absolute value of the current high - the previous close; 
- and the absolute value of the current low - the previous close. 

The ATR is then a moving average, generally using 10/14 days, of the true ranges.

## What does this indicator do?
Uses the ATR and multipliers to predict ranges and trend direction.

Minimal but powerful.

Have been using this for myself, so thought it would be nice to share publicly. Of course no script is correct 100% of the time, but this is one of if not the best in my basic tools.

Two indicators will appear, the default ATR multipliers are already set for what I believe to be perfect for this particular (double indicator) strategy.
If you want to break it yourself (I couldn't find anything that tested more accurately myself), you can do so in the settings once you have added the indicator.

Basic rundown:
- A single Buy/Sell indicator in the dim colour; may be setting a direction change, or just healthy movement.
- When the brighter Buy/Sell indicator appears; it often means that a change in direction (uptrend or downtrend) is confirmed.

---

[![Chart Snapshot](https://www.tradingview.com/x/z2B45Iaf)](https://www.tradingview.com/x/z2B45Iaf)
You can see here, there was a (brighter) green indicator which flipped down then up into a (brighter) red sell indicator which set the downtrend. At the end it looks like it may be starting to break the downtrend - as the price is hitting the trend line. (Would watch for whether it holds above or drops below at that point)

[![Chart Snapshot 2](https://www.tradingview.com/x/qj1xmOoj)](https://www.tradingview.com/x/qj1xmOoj)
Another example, showing how sometimes it can still be correct but take some time to play out - with some arrow indicators.

Typically I would also look at oscillators, RSI and other things to confirm - but here it held above the trend lines nicely, so it appeared to be rather obvious.

It's worth paying attention to the trend lines and where the candles are sitting.
Once you understand/get a feel for the basics of how it works - it can become a very useful tool in your trading arsenal.

[![Chart Snapshot 3](https://www.tradingview.com/x/7ftnNOuT)](https://www.tradingview.com/x/7ftnNOuT)
Also works for traditional markets & commodities etc in the same way / using the same ATR multipliers, however of course crypto generally has bigger moves.

---

You can use this and other indicators to confirm likeliness of a direction change prior to the brighter/confirmation one appearing - but just going by the 2nd(brighter) indicators, I have found it to be surprisingly accurate.

Tends to work well on virtually all timeframes, but personally prefer to use it on 5min,15min,1hr, 4hr, daily, weekly. Will still work for shorter/other timeframes, but may be more accurate on mid ones.