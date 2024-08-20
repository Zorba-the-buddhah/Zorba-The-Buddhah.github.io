---
layout: default
title: Variable Index Dynamic Average (VIDYA)
---

# Variable Index Dynamic Average (VIDYA)

![VIDYA](../assets/image/vidya-large.png){: width="800" height="450"}

## Description

The Variable Index Dynamic Average (VIDYA) is an adaptive moving average that adjusts its sensitivity based on market volatility. This makes it more responsive to price changes in volatile markets and less reactive in stable markets, providing traders with a more accurate representation of the current trend.

## Key Features

- Adapts to market volatility
- Combines EMA and Chande Momentum Oscillator
- More responsive in volatile markets, smoother in stable markets
- Colored direction option for easy trend identification

## How it Works

VIDYA uses two main components:

1. An Exponential Moving Average (EMA)
2. The Chande Momentum Oscillator (CMO)

The CMO is used to determine the volatility of the market, which then adjusts the smoothing factor of the EMA. In volatile markets, VIDYA will react more quickly to price changes, while in stable markets, it will behave more like a standard moving average.

## How to Use

1. Trend Identification: When the price is above the VIDYA line, it suggests an uptrend. When below, it suggests a downtrend.
2. Support and Resistance: The VIDYA line can act as dynamic support in uptrends and resistance in downtrends.
3. Crossovers: Price or faster moving average crossovers with VIDYA can signal potential trend changes.
4. Volatility Analysis: The slope and behavior of the VIDYA line can give insights into market volatility.

## Parameters

- EMA Period: Default is 14, determines the base responsiveness of the indicator
- CMO Period: Default is 14, determines how volatility is measured
- Colored Direction: Option to color the line based on its slope
- Bullish Color: Color for upward slope (default: Green)
- Bearish Color: Color for downward slope (default: Red)

## Download

[Download VIDYA Indicator](../downloads/vidya.dll){: .button}

## Installation Instructions

1. Download the VIDYA indicator file (.dll)
2. Place the .dll file into the `Documents/ATAS/Indicators` folder on your computer.
3. After adding the file, a blue button will appear on the bottom right panel of the ATAS platform, indicating that the list of indicators has been updated.
4. Click the blue button to refresh the indicator list.
5. The VIDYA indicator will now appear in the list of indicators under the "Zorba the Buddhah" section.

To report bugs, comment, or for any questions, please [contact us](mailto:zorba.the.buddhah@gmail.com).
