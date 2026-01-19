
**Delta** in trading (specifically in **order flow** and **volume analysis**, often seen on footprint charts, volume profiles, or indicators like Cumulative Delta) is a powerful metric that reveals the **aggressive buying vs. selling pressure** behind price movements.

It measures the **difference** between **aggressive buys** and **aggressive sells** in the market.

### How Delta Is Calculated
- Aggressive buys = trades executed by hitting the **ask/offer** price (buyers taking liquidity immediately).
- Aggressive sells = trades executed by hitting the **bid** price (sellers taking liquidity immediately).
- **Delta = Volume at Ask (buys) - Volume at Bid (sells)**

This is **not** the same as total volume — it ignores passive limit orders waiting in the book and focuses only on who was more **urgent/aggressive** to get filled.

### Positive Delta
- **Positive Delta** (usually shown in **green** bars/numbers) = More aggressive buying than selling.
- This means **buyers** were more aggressive (lifting offers to push price higher).
- Interpretation: **Bullish pressure** — buyers in control, often supporting upward moves.
- Example: In a footprint chart cell or candle, if buy volume at ask is 500 and sell volume at bid is 200 → Delta = +300 (green). Price tends to rise or hold strong when this dominates.

### Negative Delta
- **Negative Delta** (usually shown in **red** bars/numbers) = More aggressive selling than buying.
- This means **sellers** were more aggressive (hitting bids to push price lower).
- Interpretation: **Bearish pressure** — sellers in control, often driving downward moves.
- Example: Sell volume at bid 600, buy volume at ask 150 → Delta = -450 (red). Price often falls or rejects higher levels.

### Key Concepts and Usage
1. **Per-Candle/Bar Delta** — Shows aggression for a single candle (e.g., on a 5-min chart or footprint). A green candle with positive delta = healthy up move. A red candle with negative delta = strong down pressure.
2. **Delta Divergence** (very powerful signal):
   - Price makes higher highs but delta is negative/declining → Potential weakness (sellers lurking, possible reversal down).
   - Price makes lower lows but delta is positive/rising → Potential strength (buyers absorbing sells, possible reversal up).
3. **Cumulative Delta (CVD)** — Running total of delta over time (e.g., session or day). Starts at zero and accumulates:
   - Rising CVD (positive/green) = Overall buyers dominating the session.
   - Falling CVD (negative/red) = Overall sellers in control.
   - Often plotted as a line or histogram below the price chart.

In your earlier NQ charts (with green/purple delta profiles), you're likely seeing exactly this: **green lines/areas** for positive delta (buying aggression) and **purple/red** for negative (selling aggression). It helps spot when volume backs the move (alignment) or fights it (divergence → traps or reversals).

### Quick Summary Table

| Delta Type       | Color (Typical) | Meaning                              | Market Implication                  | Common Signal                     |
|------------------|-----------------|--------------------------------------|-------------------------------------|-----------------------------------|
| **Positive**     | Green          | More aggressive buys                | Bullish control, upward momentum    | Supports rallies, confirmations   |
| **Negative**     | Red            | More aggressive sells               | Bearish control, downward momentum  | Drives sell-offs, rejections      |
| **Divergence**   | Mismatch       | Price vs. Delta disagree            | Weakening trend, potential reversal | High-probability setups           |

Delta is one of the core tools in order flow trading (used in platforms like Sierra Chart, Bookmap, NinjaTrader, etc.). It's not perfect (limit orders can absorb aggression without moving price much), but combined with price action, profiles, and context, it gives a huge edge in understanding **who's really in control**.

If you're seeing specific delta behavior on your gold or NQ charts (e.g., positive delta on a pullback), drop more details and I can help interpret it! What's your main setup using delta right now?