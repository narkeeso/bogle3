# Bogle3

A simple, free calculator for the Bogleheads 3-fund portfolio.

**Live at: https://narkeeso.github.io/bogle3/**

## What It Does

Enter your investment amount and get exact dollar amounts for the classic 3-fund portfolio:

- **US Total Stock Market** (VTI, VTSAX, SWTSX, FSKAX, ITOT)
- **International Stock Market** (VXUS, VTIAX, SWISX, FTIHX, IXUS)
- **Total Bond Market** (BND, VBTLX, SWAGX, FXNAX, AGG)

Select your broker to see the recommended funds for each category.

## How It Works

1. Enter your investment amount
2. Enter your age to auto-set stocks/bonds (or adjust manually)
3. Set International % of stocks (20-40% recommended)
4. Select your broker to see the recommended funds
5. Purchase shares at your broker to match the dollar amounts

## Features

- **Age-based allocation** - Uses "age in bonds" rule as starting point
- **Broker selection** - Choose from Vanguard, Schwab, Fidelity, or iShares equivalents
- **LocalStorage persistence** - Your preferences are saved automatically
- **Mobile-friendly** - Collapsible info section for small screens
- **Two-layer allocation** - Set stock/bond split, then international % within stocks

## Tech Stack

- Alpine.js (via CDN)
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- LocalStorage for persistence

---

*Not financial advice. Invest at your own risk.*
