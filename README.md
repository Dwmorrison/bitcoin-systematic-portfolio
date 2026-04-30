# crypto-systematic-portfolio
# BTC/USD Systematic Trading Portfolio

Quantitative post-mortem of a self-built systematic trading strategy
run live on Kraken BTC/USD from December 2, 2024 to January 21, 2025.
336,644 fills. $16.6M total notional. 99.99% passive maker.

## Documents

[**practitioner_portfolio_v4.pdf**](practitioner_portfolio_v4.pdf) — Start here. What I built, what happened, what the data showed, and what I am working on next. Written for any reader.

[**strategy_extension_memo_v4.pdf**](strategy_extension_memo_v4.pdf) — Deep dive. Capital sizing analysis, perp hedge backtest, ATRP-based dynamic sizing design, multi-bot parallel testing methodology. Written for a technical reader.

## Supporting Charts

[equity_drawdown_inventory.png](equity_drawdown_inventory.png) — Equity, PnL, drawdown, and BTC inventory over the full run.

[counterfactual_vs_price.png](counterfactual_vs_price.png) — Actual vs counterfactual equity mapped against BTC price action.

[markouts.png](markouts.png) — Round-trip PnL by holding horizon. Shows the engine worked as designed.

[activity_profile.png](activity_profile.png) — Daily notional, lot size, fee rate, and rolling tier qualification.

[monte_carlo_capital.png](monte_carlo_capital.png) — Capital sizing analysis across historical drawdown distribution.

[delta_fill_rate.png](delta_fill_rate.png) — Fill rate degradation by delta setting. Shows fill rate stays above 95% to $100 delta.

[delta_returns.png](delta_returns.png) — Expected return on capital by delta setting net of carry cost.

## About

Will Morrison. Five years M&A research at a boutique advisory firm.
Prior careers in the US Army National Guard and construction
project management. Currently building toward systematic crypto trading.

LinkedIn URL(https://www.linkedin.com/in/david-william-will-morrison-b79727220/) | emial: wktc.com@gmail.com
