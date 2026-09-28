# ESS Pricing Tracker

Weekly 5MWh battery energy storage (ESS) pack and cell prices — China, India, Europe and any region you add — in the layout of the SMM weekly pricing sheet.

**Live page:** https://eye-am-ashutosh.github.io/ess-dashboard/

## What it does

- **Overview** board: cell pricing and 5MWh ESS export pricing by region and C-rate, with Week %, previous week's price and a trend line for every row
- **One tab per region** (China, India, Europe …) and a **Cells** tab, each with price cards, a comparison chart and the full price history
- Chart with 1W · 1M · 3M · 6M · YTD · 1Y · 5Y · All, drag-to-zoom, an overview strip and full-screen mode
- Week, Month, YTD and Year % change, with the formula shown for every value
- **Manual entry**: add a whole week at once, add a single price, or add a new region / cell / C-rate row
- **Import Excel**: reads the weekly SMM pricing sheet as it is (merged region cells included)
- A **source link** on every row (↗) to its SMM page

## Saving data for everyone

Prices are stored in `data.json` in this repository.

1. Add this week's prices or import the sheet — the header shows **Unsaved changes**.
2. Click **Save to GitHub**. The first time, paste a fine-grained token with **Contents: Read and write** on this repository (it stays in your browser).

Visitors without a token can view and explore everything; their own edits stay in their browser.

## Data source

SMM weekly pricing (metal.com), from 17 Sep 2026. Prices in USD / kWh (SMM quotes USD / Wh — 0.0517 USD / Wh = 51.70 USD / kWh).

Each row links to its SMM page (↗): [China 314Ah LFP ESS battery](https://www.metal.com/battery-cell-and-module/202405100003), [China 5MWh energy storage stack](https://www.metal.com/battery-cell-and-module/202407100001), [ESS & PCS prices](https://www.metal.com/ess). SMM shows prices only to signed-in subscribers and does not allow them to be copied automatically, so prices are entered each week by hand or imported from the weekly sheet.
