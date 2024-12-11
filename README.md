# Fib-Nachos: Full Spectrum

**Fib-Nachos: Full Spectrum** is a fun, busy, TradingView Pine Script indicator that integrates a complete set of Fibonacci retracements and a full range of EMAs (5 to 233) into one comprehensive pinescript. It helps quickly identify potential support/resistance levels, crucial retracement zones, and trend shifts across multiple time horizons.

## Key Features

1. **Full Fibonacci Spectrum (5–233)**  
   - Automatically calculates standard Fibonacci retracement levels based on a user-defined lookback period.  
   - Offers clear visual guides for spotting potential price reversals, pullbacks, and continuation levels.

2. **Golden Pocket Highlighting (0.618–0.786)**  
   - Highlights candles that close within the high-probability “Golden Pocket” zone.  
   - Helps identify areas where price may stage a reversal or strengthen a continuation move.

3. **EMA Full Range (5, 8, 13, 21, 34, 55, 89, 144, 233)**  
   - Stacks multiple EMAs on the chart to analyze market momentum over short, medium, and long-term horizons.  
   - Allows traders to quickly gauge overall trend direction and strength at a glance.

4. **Trend Change Labels**  
   - Displays small labels (S, M, L) on the chart to mark emerging short-term, medium-term, and long-term bullish or bearish trends.  
   - Makes it easy to detect shifts in market structure without manual analysis.

5. **Background Highlighting**  
   - Applies a subtle background color when short-term EMAs align fully bullish or bearish.  
   - A quick visual cue to the underlying market sentiment.

## Inputs & Parameters

- **Show Full Fibonacci Spectrum (5–233)**: Toggle the visibility of horizontal Fibonacci levels.
- **Highlight Golden Pocket Candles**: Enable/disable highlighting of candles that close within the 0.618–0.786 retracement zone.
- **Show Trend Change Labels**: Choose to display or hide short, medium, and long-term trend labels.
- **Show EMAs**: Turn on/off the display of all EMAs (5 through 233).
- **Lookback Period for High/Low**: Define the number of bars to look back to determine pivot highs/lows used for Fibonacci calculation.

## How It Works

1. **Fibonacci Analysis**  
   - The script identifies the highest and lowest points over the chosen lookback period.
   - Calculates key Fibonacci retracement levels and plots them as horizontal lines on the chart.

2. **Golden Pocket Detection**  
   - Any candle closing within the 0.618–0.786 retracement levels is highlighted.
   - This zone is often considered prime for potential market turnarounds.

3. **EMA-Based Trend Identification**  
   - Short-Term Trend: Determined by EMA 8 crossing EMA 21.  
   - Medium-Term Trend: Determined by EMA 21 crossing EMA 55.  
   - Long-Term Trend: Determined by EMA 55 crossing EMA 233.

   When these crossovers occur, the script labels the chart accordingly. If all short-term EMAs line up bullishly or bearishly, the chart’s background color shifts, providing an immediate visual confirmation of the trend.

## Use Cases

- **Swing Traders**: Identify Fibonacci retracements during pullbacks in ongoing trends, optimizing entry/exit points.
- **Trend Traders**: Confirm trend alignment across multiple EMAs to validate the broader market direction.
- **Reversal Seekers**: Use the Golden Pocket highlight to pinpoint areas where price may stage a reversal.

## Installation Guide

1. Open [TradingView](https://www.tradingview.com/).
2. Access the Pine Editor at the bottom of the chart.
3. Copy and paste the entire script into the Pine Editor.
4. Click "Add to chart" to load the indicator onto your current chart.

Adjust settings as desired under the indicator’s settings menu.

## Disclaimer

This indicator is intended for fun educational and informational purposes only and does not constitute financial advice. Always perform your own due diligence and consider consulting a qualified financial professional before making any trading decisions. Past performance is not indicative of future results.

---

By combining the power of full-spectrum Fibonacci retracements with a stochastics and your other favorites can help deliver a versatile, visually intuitive framework for enhanced technical analysis and more confident trading decisions.
