# Crypto Box Re-entry Alerts using the Darvas Strategy

An alerts-only TradingView script written in Pine Script v6 that assists
with crypto trading using liquidity sweep re-entry logic from the Darvas Box Theory, with potential to scale to trading with other financial instruments

## Features
- User-defined price box (upper/lower bounds)
- Close-out → close-in sweep detection
- Dollar-based position sizing (max spend, max loss, max profit)
- Automatic stop-loss (SL) and take-profit (TP) calculations
- Alert messages with execution instructions
- Cooldown to prevent signal spam

## Why This Project
This project was built to:
- Practice algorithmic thinking in a constrained scripting language
- Explore risk-based position sizing logic
- Practice Git version control and documentation
- Develop a tool that is helpful and can be personally used with the ability to upgrade and scale the project over time

## Usage
1. Add the script to a TradingView chart
2. Set box bounds and dollar risk inputs
3. Enable alerts using "Any alert() function call"
4. Manually execute trades using the provided instructions

## Disclaimer
This tool is for educational and paper trading purposes only. Any use with real trading or other brokers is not advised/will not work.
