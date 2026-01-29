# CEBE Tracker

**Common Equity Bitcoin Exposure** - A methodology for measuring what shareholders actually own in Bitcoin Treasury Companies.

🌐 **Live:** [cebetracker.io](https://cebetracker.io)

## What is CEBE?

BTC-per-share (BPS) is misleading. It ignores debt, preferred stock, and other senior claims that get paid before common shareholders.

**CEBE answers:** *If this company liquidated its Bitcoin today, how many sats would each share actually receive?*

### The 5-Step Calculation

1. **Net Senior Claims (USD)** = Debt + Preferred Stock − Cash
2. **Claims in BTC** = Net Senior Claims ÷ BTC Price
3. **Common Equity BTC** = Total BTC Holdings − Claims in BTC
4. **CEBE** = (Common Equity BTC ÷ Shares Outstanding) × 100,000,000
5. **Drag** = Claims in BTC ÷ Total BTC Holdings

## Why It Matters

| Metric | What It Tells You |
|--------|-------------------|
| BPS | Gross exposure (ignores debt) |
| CEBE | Net exposure (what you actually own) |
| Drag | % of BTC eaten by senior claims |

As BTC price rises, drag compresses and CEBE grows faster than BPS.

## Features

- 📊 Live data from company filings
- 🔢 Step-by-step calculation breakdowns
- 📈 Historical CEBE tracking
- 🎚️ Drag compression simulator
- 📱 PWA - installable on mobile

## Currently Tracking

- Strategy (MSTR)
- Metaplanet (MTPLF)
- Strive (ASST)
- The Smarter Web Company (TSWCF)

## Methodology

CEBE was developed by [@chcbearsfan](https://x.com/chcbearsfan) in January 2026 as a more accurate way to evaluate Bitcoin Treasury Companies.

Full methodology: [cebetracker.io/methodology](https://cebetracker.io/methodology)

## Data Sources

- Company 8-K/10-Q/10-K filings (SEC EDGAR)
- Quarterly earnings reports
- Official company announcements

## License

© 2026 CEBE Tracker. All rights reserved.

The CEBE methodology is freely available for educational and analytical purposes.

---

*Not financial advice. Do your own research.*
