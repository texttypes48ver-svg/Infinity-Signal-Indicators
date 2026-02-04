# Infinity Signal Indicators

This repository contains free TradingView (Pine Script v6) indicators created by Jerome Morrow (TradingView: Dinjin).

These tools are designed to visualize **market structure, timing, and volatility context**.  
They are **not trading strategies** and do not generate buy or sell signals.

---

## Download Instructions (Start Here)

If you are here from YouTube:

1. Click the `.pine` file you want (for example: `4MA_Projection_SD_Bands_Table.pine`)
2. Click **Raw**
3. Copy the entire script
4. Paste it into a new TradingView Pine Script editor
5. Save and add to chart

No installation or account linking required.

---

## Featured Indicator

### MA4 Projection with Standard Deviation Bands

A forward-projection indicator built around a minimal moving-average structure:
the 4-period Simple Moving Average (MA4) and its 1-bar lagged value (MA4[1]).

This indicator is designed for **education, validation, and structural insight**, not signal generation.

#### What This Indicator Does

- Projects a prior MA behavior pattern **14 bars forward**
- Visualizes a probable future price corridor using **4 Standard Deviation bands**
- Highlights where an **MA4 vs MA4[1] crossover is expected**
- Allows comparison between **projected vs live crossovers**
- Supports bar-replay validation using manual vertical markers

#### Important Design Notes

- Projection length is **fixed at 14 bars** (by design)
- Historical lookback is **fixed**
- If projections are missing, switch to an exchange with deeper historical data
- This is **not** a strategy and does not place trades

---

## Additional Indicators in This Repository

This repository may also include:

- Target Ladder Pro (MTF ATR-based volatility targets)
- Other experimental or educational structure tools

Each script is self-contained and documented through accompanying videos where applicable.

---

## Platform Notes

All scripts are written for **TradingView (Pine Script v6)**.  
Behavior may vary depending on symbol history and exchange data availability.

---

## License

MIT License — free to study, modify, and experiment with.  
Use at your own risk.
