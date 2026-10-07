# Antwerp Household Budget

A single-page budget planner for a household in Antwerp, Belgium, focused on paying off debt.

## What it does

- **Spending plan**: splits your safe monthly income into fixed costs, debt payments, an emergency buffer and flexible spending, then gives a monthly and weekly cap per category (groceries, eating out, clothing, leisure, …).
- **Debt payoff**: enter each debt's balance, interest rate and minimum payment, then pick a debt-free date with a slider. It calculates the monthly payment needed, interest saved, and the fastest date that still leaves a lean but livable budget. Supports highest-interest-first (avalanche) and smallest-balance-first (snowball).
- **Variable income**: enter six months of net income per person and plan on the lowest month, the three leanest months, or the average. A "This month" box tells you what to do with a better or worse month (e.g. holiday pay or a slow freelance month).
- **Multiple people**: adults and children (child benefit/Groeipakket counts as income), shared or personal costs and debts, and how much each adult should move to a joint account (split by income or equally).
- **Antwerp comparison**: compares rent and each spending category with a typical Antwerp household of the same size and home type.

The Antwerp reference figures are rounded estimates for 2026 based on public Belgian data (Statbel, Antwerp rent levels, De Lijn fares, VREG energy prices, CEBUD reference budgets). Use them to spot outliers, not as exact targets.

## Running it

It's one self-contained file with no build step. Open `index.html` in a browser, or enable GitHub Pages (Settings → Pages → deploy from the `main` branch) to host it.

## Where data is stored

Outside claude.ai, your budget is saved in your browser's local storage only. It stays on that device and browser, and clearing site data removes it.
