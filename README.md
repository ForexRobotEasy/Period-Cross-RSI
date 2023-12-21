# Period Cross RSI

This code is a custom indicator developed by the Forex Robot Easy Team. It is designed to calculate and display the Relative Strength Index (RSI) values for two different periods, as well as identify ascending and descending zones. The indicator also checks for crossovers between the two RSI lines to generate trading signals.

## Input Parameters

- RSI_Period1: The period for the first RSI calculation (default: 14)
- RSI_Period2: The period for the second RSI calculation (default: 28)
- AscendingZone: The upper threshold for the ascending zone (default: 70)
- DescendingZone: The lower threshold for the descending zone (default: 30)

## Indicator Initialization

The `OnInit()` function is responsible for initializing the indicator. It sets up the indicator buffers, labels, styles, and colors for the RSI lines, ascending zone, and descending zone.

## Indicator Calculation

The `OnCalculate()` function is called for each new tick and is responsible for calculating the RSI values, determining the ascending and descending zones, and checking for crossovers.

- RSI Calculation: The RSI values for both periods are calculated using the `iRSI()` function.
- Ascending and Descending Zones: The indicator checks if the RSI values for both periods are above the ascending zone threshold or below the descending zone threshold, and sets the corresponding buffer values accordingly.
- Crossover Detection: The indicator compares the previous and current RSI values for both periods to detect crossovers. If the RSI1 line crosses above the RSI2 line, a buy signal is printed. If the RSI1 line crosses below the RSI2 line, a sell signal is printed.

## Product Description

[Period Cross RSI](https://forexroboteasy.com/forex-robot-review/period-cross-rsi-review-new-forex-software-for-trading-zones/) is a custom indicator developed by the Forex Robot Easy Team. It is designed to help traders identify potential trading opportunities based on crossovers between two RSI lines and the presence of ascending or descending zones.

The indicator calculates and displays the RSI values for two different periods, allowing traders to analyze the strength or weakness of a financial instrument. Additionally, it identifies ascending and descending zones, which can be used to determine overbought or oversold conditions.

One of the key features of Period Cross RSI is its ability to generate trading signals based on crossovers between the two RSI lines. When the RSI1 line crosses above the RSI2 line, a buy signal is generated, indicating a potential bullish trend. Conversely, when the RSI1 line crosses below the RSI2 line, a sell signal is generated, indicating a potential bearish trend.

Traders can use this indicator as a standalone tool or in conjunction with other technical analysis techniques to make informed trading decisions. It can be applied to various financial instruments and timeframes.

Please note that Forex Robot Easy is not the official developer of this product. We only provide sample code that demonstrates how the indicator works. To find the official developer and access detailed reviews and trading results of this product, please refer to the [official MQL5 website](https://www.mql5.com/).
