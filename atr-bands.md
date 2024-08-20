---
layout: default
title: ATR Bands
---

# ATR Bands

![ATR Bands](../assets/image/atr-bands-large.png){: width="800" height="450"}

## Description

ATR Bands use the Average True Range (ATR) to create dynamic support and resistance levels. These bands adapt to market volatility, providing traders with more precise trading signals and helping to identify potential breakouts or reversals.

## Key Features

- Dynamic support and resistance levels
- Adapts to market volatility using ATR
- Customizable period and multiplier
- Upper and lower bands for clear visual representation

## How it Works

The ATR Bands indicator calculates two bands around the current price:

1. Upper Band: Current Price + (ATR * Multiplier)
2. Lower Band: Current Price - (ATR * Multiplier)

The ATR is calculated using the specified period, and the bands are adjusted based on the multiplier value. This allows the bands to expand during volatile periods and contract during calmer market conditions.

## How to Use

1. Support and Resistance: The upper and lower bands can act as dynamic support and resistance levels.
2. Breakout Trading: A price break above the upper band or below the lower band can signal a potential breakout.
3. Mean Reversion: When price touches or exceeds the bands, it may indicate a potential reversal back towards the mean.
4. Volatility Analysis: The width between the bands provides a visual representation of market volatility.

## Parameters

- Period: Default is 14, determines the lookback period for calculating ATR
- Multiplier: Default is 1.0, adjusts the distance of the bands from the price

## Download

[Download ATR Bands Indicator](../downloads/atr-bands-indicator.dll){: .button}

## Installation Instructions

1. Download the ATR Bands indicator file (.dll)
2. Place the .dll file into the `Documents/ATAS/Indicators` folder on your computer.
3. After adding the file, a blue button will appear on the bottom right panel of the ATAS platform, indicating that the list of indicators has been updated.
4. Click the blue button to refresh the indicator list.
5. The ATR Bands indicator will now appear in the list of indicators under the "Zorba the Buddhah" section.

For any issues or questions regarding installation, please [contact us](mailto:zorba.the.buddhah@gmail.com).
