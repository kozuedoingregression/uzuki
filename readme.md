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

MIT License

Copyright (c) 2025 [kozue]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

