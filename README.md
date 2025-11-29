This script turns Bitcoin Dominance (BTC.D) into a clean bottom-pane regime oscillator for the Daily timeframe. Instead of plotting raw dominance, it compresses the most useful dominance behaviors into a single line that swings above/below zero so you can quickly spot when the market is BTC-led versus alt-led.

What it measures (Daily BTC.D only)

Trend spread: the distance between a Fast EMA and Slow EMA of BTC.D (who’s in control).

Trend slope: whether BTC.D’s trend is accelerating or fading.

Level vs mean: whether BTC.D is trading above or below its recent average (regime bias).

Those components are normalized over a lookback window so it adapts across different dominance ranges, then compressed into a stable -100 to +100 style oscillator.

How to read it

Above 0: BTC dominance is in a bullish regime → market tends to be BTC-led and alts often lag as a group.

Below 0: dominance regime is bearish → more favorable backdrop for alt rotation / alt outperformance.

Crosses of 0: simple regime flips (BTC leadership ↔ alt rotation).

+50 / -50 zones: “strong” regimes. These are not magic numbers, just useful markers for momentum/extremes.

Best practice (important)
BTC.D can rise for two very different reasons:

BTC is strong (good for BTC), or

alts are dumping harder (risk-off, not “bullish BTC” in the way people assume).

So use this as a regime filter, and confirm with a market-cap proxy like TOTAL / TOTAL2 (or your preferred risk gauge). The oscillator is most useful for answering: “Should I be emphasizing BTC exposure or alt exposure right now?”

Inputs / customization

Fast EMA / Slow EMA: control responsiveness (smaller = faster signals).

Normalization Length: controls how adaptive the oscillator is to different cycles.

Weights: let you emphasize spread vs slope vs mean-reversion bias.

Signal line: smooths the oscillator for cleaner cross/turn detection.

Notes

Designed for Daily BTC.D and meant to be used in the lower pane.

Not financial advice; use risk management and confirmation tools.
