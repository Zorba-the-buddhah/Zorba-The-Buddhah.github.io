---
layout: default
title: Chandelier Exit
---

# Chandelier Exit

![Chandelier Exit](../assets/image/chandelier-exit-large.png)

## Description

The Chandelier Exit is a robust, volatility-based indicator designed to set a trailing stop-loss that adapts to changing market conditions. It assists traders in protecting profits and managing risk by providing dynamic exit points that respond to market volatility.

## Key Features

- **Volatility-Based Trailing Stop-Loss**: Adjusts dynamically to market conditions.
- **Separate Long and Short Exit Levels**: Provides distinct levels for managing long and short trades.
- **ATR-Driven Volatility Measurement**: Utilizes the Average True Range (ATR) to account for market volatility.
- **Customizable Parameters**: Fine-tune the indicator settings to align with your trading strategy.

## How it Works

The Chandelier Exit calculates two critical stop levels:

1. **Long Stop**: The highest high over the specified period minus (ATR * multiplier).
2. **Short Stop**: The lowest low over the specified period plus (ATR * multiplier).

These levels are dynamically adjusted based on the ATR, which measures market volatility. This approach ensures that the stop-loss levels expand during volatile periods to avoid premature exits and contract during calmer periods to protect gains.

## How to Use

1. **Long Trades**: Enter or stay in a trade when the price is above the Long Stop line. Exit the trade when the price closes below the Long Stop.
2. **Short Trades**: Enter or stay in a trade when the price is below the Short Stop line. Exit the trade when the price closes above the Short Stop.
3. **Trend Following**: Use the Long Stop for trailing stops in uptrends and the Short Stop in downtrends.
4. **Breakout Confirmation**: Combine with other indicators to confirm breakouts and manage positions effectively.

## Parameters

- **ATR Period**: Default is 22. Sets the lookback period for calculating the ATR.
- **ATR Multiplier**: Default is 3.0. Adjusts the distance of the stop from the price based on the ATR.

## Download

[Download Chandelier Exit Indicator](https://github.com/Zorba-the-buddhah/Zorba-The-Buddhah.github.io/releases/download/v1.0.0/Chandelier.exit.8.zip){: .button}

## Installation Instructions

1. Download the Chandelier Exit indicator file (.dll).
2. Place the .dll file into the `Documents/ATAS/Indicators` folder on your computer.
3. After adding the file, a blue button will appear on the bottom right panel of the ATAS platform, indicating that the list of indicators has been updated.
4. Click the blue button to refresh the indicator list.
5. The Chandelier Exit indicator will now appear in the list of indicators under the "Zorba the Buddhah" section.

For any issues or questions related to the indicator, please [contact me](mailto:zorba.the.buddhah@gmail.com).
