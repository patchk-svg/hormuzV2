# Hormuz Disruption ETF Screener

Quantitative scoring model for identifying stocks most likely to benefit from the Strait of Hormuz closure (March 2026).

**Live Site:** [View the Screener →](https://yourusername.github.io/hormuz-screener/)

## What It Does

Scores 30 stock candidates across 9 sectors on 5 supply-disruption dimensions:

| Dimension | Weight | What It Measures |
|-----------|--------|-----------------|
| Supply Disruption | 30% | % of global supply transiting Hormuz or under force majeure |
| Insulation Advantage | 25% | Operates outside disruption zone, sells into shortage |
| Demand Urgency | 20% | Seasonal/critical demand pressure right now |
| Duration Leverage | 15% | Compounds the longer the strait stays closed |
| Essential Goods Premium | 10% | Must-buy regardless of price |

All weights are adjustable via sliders. Sector filters let you focus on specific themes.

## Sectors Covered

- **Energy** — E&Ps, Majors, Refiners, LNG, Services
- **Shipping** — Crude tankers, LNG carriers
- **Defense** — Prime contractors
- **Fertilizer** — Nitrogen, potash
- **Industrial Gas** — Helium/specialty gas distributors
- **Copper** — Miners and ETFs
- **Rare Earth** — Metallization and processing
- **Gold** — Miners, streamers, ETFs (DXY-conditional thesis)
- **Materials** — Aluminum

## Deployment

This is a single `index.html` file — no build step, no dependencies, no server required.

To run locally: open `index.html` in any browser.

Hosted via GitHub Pages.

## Disclaimer

This is a research scoring framework, NOT financial advice. All data is approximate and based on publicly available reporting as of late March 2026. Validate with your own due diligence.

---

*Built by The Wealth Society*
