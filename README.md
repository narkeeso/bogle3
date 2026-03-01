# Bogle3 - 3-Fund Portfolio Calculator

A simple, free calculator for John's 3-fund portfolio paradigm. No accounts, no fees, no tracking - just a tool to help you allocate your investments correctly.

## What It Does

Takes your investment amount and splits it across the classic 3-fund portfolio:
- **Total US Stock Market** (e.g., VTI, VTSAX)
- **Total International Stock Market** (e.g., VXUS, VTIAX)
- **Total Bond Market** (e.g., BND, VBTLX)

**Optional: Advanced Bond Split** - For users who want more control, enable sub-splitting bonds into categories like:
- US Treasuries vs Corporate
- Nominal vs TIPS (inflation-protected)
- US vs International Bonds

Users can adjust the ratios and see exactly how much money goes into each fund.

## Why This Exists

Fidelity and others offer "buckets" but they want your money under management. This is a free alternative - you do the math here, then manually fund your accounts at Vanguard/Fidelity/Schwab yourself.

## Core Principles

- **Pure JavaScript + Alpine.js** - No build step, no dependencies beyond Alpine
- **Single HTML file** - Open it and it works
- **No data collection** - Everything stays in your browser
- **Mobile friendly** - Works on your phone at the brokerage

## Features

- [ ] Input total investment amount
- [ ] Adjust allocation percentages (must total 100%)
- [ ] Display dollar amounts for each fund
- [ ] Show which ETFs/mutual funds to buy
- [ ] Save ratios to localStorage (optional)
- [ ] Show rebalance calculations (if you already have positions)
- [ ] **(Advanced/Optional)** Toggle bond sub-split for finer control (Treasury/Corporate/TIPS/International)

## Tech Stack

- Alpine.js (via CDN)
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- LocalStorage for persistence

## Project Structure

```
index.html    # Everything in one file
```

That's it. Grug brain simple.
