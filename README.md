# Twin Range Filter MT4 Indicator
This is the readme file for the Twin Range Filter MT4 indicator developed by colinmck. The code provided here is a sample code that can be used to understand how the indicator works. Please note that ForexRobotEasy is not the official developer of this product. For detailed reviews and trading results of the official product, please visit the [official website](https://forexroboteasy.com/forex-robot-review/twin-range-filter-mt4-review-efficient-non-repaint-forex-software/).

## Indicator Description
The Twin Range Filter MT4 indicator is designed to calculate the range of price movements and display upper and lower bands based on the calculated range. It can be used to identify potential support and resistance levels in the market. The indicator has the following customizable inputs:

- RangePeriod: Period for calculating the range.
- RangeMultiplier: Multiplier for the range.
- PriceType: Price type for range calculation.

## Indicator Buffers
The indicator uses two buffers to store the upper and lower range values:

- ExtUpperBuffer: Buffer for storing the upper range values.
- ExtLowerBuffer: Buffer for storing the lower range values.

## Indicator Initialization
During initialization, the indicator sets up the necessary buffers and labels for displaying the range values. It also sets a short name for the indicator.

## Indicator Calculation
The indicator calculates the range for each bar in the chart by considering the previous RangePeriod bars. It then calculates the upper and lower range values based on the current bar's high and low prices, along with the range multiplier. The calculated values are stored in the respective buffers.

## Usage
To use this indicator, simply copy the provided code and compile it in MetaEditor. Once compiled, the indicator can be applied to any chart in MetaTrader 4. The indicator will then display the upper and lower range bands on the chart, which can be used to identify potential support and resistance levels.

For detailed reviews and trading results of the official Twin Range Filter MT4 indicator, please visit the [official website](https://forexroboteasy.com/forex-robot-review/twin-range-filter-mt4-review-efficient-non-repaint-forex-software/).

Please note that ForexRobotEasy is not the official developer of this product. We only provide this sample code to demonstrate how the indicator works. To find the official developer of this product and obtain the official version, please use MQL5.

For any inquiries or support regarding the official Twin Range Filter MT4 indicator, please contact the official developer through their official website.
