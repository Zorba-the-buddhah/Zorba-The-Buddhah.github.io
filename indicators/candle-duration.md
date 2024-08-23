---
layout: default
title: Candle Duration
---

# Candle Duration

![Candle Duration](../assets/image/candle-duration-large.png)

## Description

The Candle Duration indicator is designed for ATAS’s non-time-based charts, such as those driven by volume, delta, or tick count. This indicator reintroduces a crucial time dimension, enabling traders to see how long each candle takes to form. By coloring candles according to their duration, it provides insights into market dynamics that are not evident from price movements alone. Additionally, users can control the logging of candle durations to the log panel, helping to manage log output during extended trading sessions.

## Key Features

- **Time Dimension for Non-Time-Based Charts**: Reintroduces the time aspect in volume, delta, tick, and other non-time-based charts.
- **Automatic Span Calculation**: Automatically calculates duration thresholds based on the specific conditions of your chart.
- **Intuitive Color Gradient**: Represents different duration spans with a gradient of blue shades, from light blue for the shortest to navy for the longest.
- **Log Control**: Allows you to enable or disable the logging of each candle’s duration to prevent log overload during long trading sessions.

## How it Works

On non-time-based charts, where candles are formed based on criteria like volume or tick count rather than time intervals, the Candle Duration indicator calculates the time difference between the start of each candle and its predecessor. It then assigns a color to each candle based on this duration:

1. **Shortest Durations**: Light Blue - Indicates quick formation, often reflecting high activity.
2. **Moderate Durations**: Sky Blue, Dodger Blue, Royal Blue - Represent varying levels of market activity.
3. **Longest Durations**: Medium Blue, Navy - Highlight candles that took the longest to form, signaling slower market conditions.

The indicator uses percentiles of candle durations from your chart data to automatically determine the color thresholds, ensuring that the visual representation adapts to different market conditions.

## How to Use

1. **Visualize Market Activity**: Quickly identify periods of rapid market activity (lighter colors) and slower periods (darker colors) on your non-time-based charts.
2. **Analyze Trading Sessions**: Detect transitions between trading sessions or significant market events by observing changes in candle duration.
3. **Volatility Insights**: Clusters of short-duration candles may indicate increased volatility or significant market events, offering potential trade signals.
4. **Complementary Analysis**: Use alongside other technical indicators to confirm trade setups or trends, especially during key market periods.
5. **Log Management**: If running the chart for extended periods, disable the logging feature to keep the log panel focused on the most relevant information.

## Parameters

The Candle Duration indicator automatically calculates its parameters based on the historical data of your chart, using the following percentiles to determine the color thresholds:

- **10th percentile**: Light Blue
- **30th percentile**: Sky Blue
- **50th percentile**: Dodger Blue
- **70th percentile**: Royal Blue
- **90th percentile**: Medium Blue
- **Above 90th percentile**: Navy

### Additional Parameter

- **Candle Duration in Logs**: A boolean setting (`EnableLogging`) that allows you to turn off the logging of each candle's duration. By default, this is enabled.

## Download

[Download Candle Duration Indicator](../downloads/candle-duration.dll){: .button}

## Installation Instructions

1. Download the Candle Duration indicator file (.dll).
2. Place the .dll file into the `Documents/ATAS/Indicators` folder on your computer.
3. After adding the file, a blue button will appear on the bottom right panel of the ATAS platform, indicating that the list of indicators has been updated.
4. Click the blue button to refresh the indicator list.
5. The Candle Duration indicator will now appear in the list of indicators under the "Zorba the Buddhah" section.

For any issues or questions related to the indicator, please [contact me](mailto:zorba.the.buddhah@gmail.com).
