# Bollinger Bands Example
This repository showcases a method to visualize stock closing data from a Technical Analysis perspective using Bollinger Bands. Bollinger Bands are a popular tool in technical analysis used to identify overbought or oversold conditions in a market. You can find more on the topic here: https://en.wikipedia.org/wiki/Bollinger_Bands

## Purpose
The purpose of this example is to provide a practical demonstration of how Bollinger Bands can be implemented to analyze stock price movements. While Bollinger Bands are often used in conjunction with other technical analysis methods, this example focuses specifically on understanding and visualizing the bands' behavior.

## Calculation of Bollinger Bands
Moving Average (20-Day SMA): Calculated using a rolling window of 20 days on the closing price data.
Standard Deviation: Calculated using a rolling window of 20 days on the closing price data.
Upper Band: Calculated as the sum of the 20-day SMA and twice the standard deviation.
Lower Band: Calculated as the difference between the 20-day SMA and twice the standard deviation.

The script utilizes matplotlib to plot the Upper and Lower Bollinger Bands.
The area between the Upper and Lower Bands is shaded in grey to indicate potential trading ranges.

## Comments
This example provides a static demonstration of Bollinger Bands.
Feel free to customize the script to analyze different stocks or modify parameters such as the window size for moving averages.
