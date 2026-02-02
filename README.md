# XAU/USD Trend Reversal Candle Indicator - User Guide

## Overview
This Pine Script indicator identifies key candlestick reversal patterns specifically for gold (XAU/USD) trading.

## Installation
1. Open TradingView and navigate to your XAU/USD chart
2. Click "Pine Editor" at the bottom of the screen
3. Copy and paste the entire script code
4. Click "Add to Chart"

## Pattern Types Detected

### BULLISH REVERSAL PATTERNS (Bottoming Signals)

**1. Bullish Engulfing (BE)**
- Previous candle: Bearish (red)
- Current candle: Bullish (green) that completely engulfs the previous body
- Signal: Strong reversal from downtrend to uptrend
- Label: Green triangle up + "BE" label

**2. Hammer (H)**
- Long lower wick (2x+ body size)
- Small body near the top
- Minimal upper wick
- Signal: Rejection of lower prices, buyers stepping in
- Label: "H" below candle

**3. Morning Star (MS)**
- 3-candle pattern:
  - Day 1: Strong bearish candle
  - Day 2: Small body (indecision)
  - Day 3: Strong bullish candle
- Signal: Very strong reversal confirmation
- Label: "MS" below candle

**4. Doji (D)**
- Very small body (open ≈ close)
- Equal or long wicks on both sides
- Signal: Market indecision, potential reversal
- Label: "D" (lighter color)

### BEARISH REVERSAL PATTERNS (Topping Signals)

**1. Bearish Engulfing (BE)**
- Previous candle: Bullish (green)
- Current candle: Bearish (red) that completely engulfs the previous body
- Signal: Strong reversal from uptrend to downtrend
- Label: Red triangle down + "BE" label

**2. Shooting Star (SS)**
- Long upper wick (2x+ body size)
- Small body near the bottom
- Minimal lower wick
- Signal: Rejection of higher prices, sellers stepping in
- Label: "SS" above candle

**3. Evening Star (ES)**
- 3-candle pattern:
  - Day 1: Strong bullish candle
  - Day 2: Small body (indecision)
  - Day 3: Strong bearish candle
- Signal: Very strong reversal confirmation
- Label: "ES" above candle

**4. Doji (D)**
- Same as bullish, but in uptrend context
- Signal: Potential top formation

## Customization Settings

### Pattern Selection
- Toggle each pattern type on/off individually
- Focus on specific patterns you trust most

### Sensitivity Settings
- **Min Body % for Engulfing**: Default 0.3 (30%)
  - Higher = stricter engulfing requirement
  - Lower = more signals, less strict
  
- **Wick to Body Ratio**: Default 2.0
  - Controls hammer/shooting star detection
  - Higher = requires longer wicks
  
- **Max Body % for Doji**: Default 0.1 (10%)
  - How small the body must be
  - Lower = stricter doji definition

### Visual Settings
- **Colors**: Customize bullish (green) and bearish (red) colors
- **Label Size**: Choose from tiny/small/normal/large
- **Show Labels**: Toggle pattern name labels on/off

## How to Use

### For Day Trading
1. Use on 5m, 15m, or 1H timeframes
2. Look for patterns at key support/resistance levels
3. Wait for confirmation (next candle follows pattern direction)
4. Combine with volume and other indicators

### For Swing Trading
1. Use on 4H or Daily timeframes
2. Engulfing and Morning/Evening Star patterns are most reliable
3. Consider the broader trend context
4. Use as entry/exit signals with proper risk management

### Best Practices
✓ **Confirm with trend**: Bullish patterns work best in downtrends, bearish in uptrends
✓ **Check support/resistance**: Patterns at key levels are more significant
✓ **Wait for confirmation**: Don't trade on the pattern candle alone
✓ **Use stop losses**: Place stops beyond the pattern's high/low
✓ **Consider volume**: Higher volume patterns are more reliable

### Alert Setup
1. Right-click on chart → "Add Alert"
2. Condition: Select the specific pattern (e.g., "Bullish Engulfing")
3. Set your notification preferences
4. Get real-time alerts when patterns form

## Pattern Strength Ranking (Most Reliable)

**Strongest Signals:**
1. Morning Star / Evening Star (3-candle confirmation)
2. Engulfing Patterns (especially with high volume)
3. Hammer / Shooting Star (at key levels)

**Moderate Signals:**
4. Doji (requires additional confirmation)

## Tips for XAU/USD Specifically
- Gold is sensitive to: USD strength, inflation data, geopolitical events
- Best trading during London/New York session overlap
- Patterns work well at psychological levels ($2,400, $2,450, $2,500, etc.)
- Combine with RSI, MACD, or moving averages for best results
- Consider news events (Fed announcements, NFP, CPI) - patterns may fail during high volatility

## Troubleshooting
- **Too many signals**: Increase sensitivity settings
- **Too few signals**: Decrease sensitivity settings  
- **False signals**: Use higher timeframes, confirm with other indicators
- **Patterns not showing**: Check that pattern types are enabled in settings

## Example Trade Setups

**Bullish Setup:**
- Pattern: Hammer or Bullish Engulfing at support
- Confirmation: Next candle closes higher
- Entry: Break above pattern high
- Stop: Below pattern low
- Target: Next resistance level or 2:1 reward/risk

**Bearish Setup:**
- Pattern: Shooting Star or Bearish Engulfing at resistance
- Confirmation: Next candle closes lower
- Entry: Break below pattern low
- Stop: Above pattern high
- Target: Next support level or 2:1 reward/risk

---

**Disclaimer**: This indicator is for educational purposes. Always practice proper risk management and consider multiple factors before trading. Past patterns don't guarantee future results.
