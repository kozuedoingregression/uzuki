# Uzuki
> weaving the fabric of time complexity

I've been trying to solve this problem for a while now, but I haven't made any progress so far. I derived this algorithm from a concept given to me by a friend. I implemented the idea, ran it on the machine, and fine-tuned it to handle edge cases efficiently.

## psudo code 
1. INPUT (current price)
2. check for the presence of a fair value gap [FVG]
3. determine if price breaks the FVG,indicating a break of structure [BOS]
4. enter a position when the price re-enters the FVG.
5. manage position by appling risk management.

## Extra Features
### Before placing a trade
    1. Define Key Levels like support, resistance, or pivot points that might impact price movement.
    2. Confirm Trend using moving averages, RSI or another method to confirm the overall market trend (bullish, bearish, or neutral).
    3. Analyze volume data to ensure strong momentum supports the potential trade.
    4. Specify Risk-to-Reward Ratio to ensure the trade meets a predefined risk-to-reward ratio, e.g., 1:2 or higher.

