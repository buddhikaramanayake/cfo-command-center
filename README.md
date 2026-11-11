# CFO Command Center

A live, driver-based finance model for **Kestrel Ridge Outfitters**, a fictional US outdoor-gear distributor. All data is simulated.

**Live demo:** https://buddhikaramanayake.github.io/cfo-command-center/

## What it does

- Monthly income statement, balance sheet and cash flow that reconcile every month
- 9 scenario sliders and 4 presets (Budget, Latest estimate, Downside, Upside) that recalculate the whole model in real time
- EBITDA bridge from budget to latest estimate
- 13-week direct-method cash forecast with a $6.0M minimum-cash line
- 1,000 Monte Carlo simulations of cash
- A CFO briefing and action list that rewrite themselves when the numbers change
- 6 integrity checks behind a live badge. Tick **"Type over a cell"** to hard-code a number and watch the badge catch it.

## How it works

Everything runs in the browser as plain JavaScript in a single `index.html`, with no server and no live AI calls. Every figure is calculated from nine drivers plus an opening balance sheet.

## Explainer deck

A 14-slide walkthrough of how the model works:

- [View the slides (PDF)](CFO_Command_Center_Explained.pdf), which opens right on GitHub
- [Download the PowerPoint](CFO_Command_Center_Explained.pptx), which includes speaker notes

Built with Claude as an AI-in-finance demo.
