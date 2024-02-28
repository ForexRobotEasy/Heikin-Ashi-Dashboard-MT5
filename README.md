# Heikin Ashi Dashboard MT5

Developer: Forex Robot Easy Team
Website: forexroboteasy.com

[Backlink to detailed reviews and trading results of this product](https://forexroboteasy.com/forex-robot-review/heikin-ashi-dashboard-mt5-review-multicurrency-market-indicator/)

## Description

This code is a sample implementation of the Heikin Ashi Dashboard MT5 indicator. The indicator allows traders to monitor multiple currencies and timeframes simultaneously to identify trend changes, reversal candles, and consolidation candles.

The indicator takes the following parameters:

- Currencies: A string specifying the desired currencies to monitor (e.g. 'EURUSD,GBPUSD,USDJPY').
- Periods: An enumeration specifying the desired timeframes to monitor (e.g. PERIOD_M15).

The indicator initializes by executing the `OnInit` function, where any necessary initialization code can be added.

The main calculation of the indicator occurs in the `OnCalculate` function, which receives the necessary data for each candle, such as open, high, low, and close prices. In this function, you can add your own code for performing calculations based on the received data.

The indicator also provides three additional functions:

- `IsTrendChange`: This function checks for a trend change based on a specific logic. It returns `true` if a trend change is detected, otherwise `false`.
- `IsReversalCandle`: This function checks for a reversal candle based on a specific logic. It returns `true` if a reversal candle is detected, otherwise `false`.
- `IsConsolidationCandle`: This function checks for a consolidation candle based on a specific logic. It returns `true` if a consolidation candle is detected, otherwise `false`.

When a trend change or a reversal/consolidation candle is detected, the indicator sends a notification using the `SendNotification` function. You can add your own logic for sending notifications in this function.

Please note that Forex Robot Easy Team is not the official developer of this product. We are only providing a sample code that can work as described in the product. To find the official developer of this product, please refer to MQL5.
