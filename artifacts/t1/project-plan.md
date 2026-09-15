# T1 Project Plan

## Project Goal

Develop a clear and reproducible research workflow for comparing three familiar asset classes using illustrative ETFs: `SPY` (US equities), `TLT` (long-term US Treasury bonds), and `GLD` (gold). This repository is the shared project for three Finance × AI tutorials, so the goal is to build project versioning, AI-assisted work, verification, and agent collaboration skills. The project begins with a written plan in T1; later tutorials are expected to design a bounded analysis task and organize a verifiable agent workflow.

## Available Data

- `data/etf_snapshot.csv` — one row per illustrative ETF with columns: `ticker`, `asset_class`, `expected_return_pct`, `volatility_pct`, `max_drawdown_pct`, and `expense_ratio_pct`.
- `data/data_dictionary.md` — documents the meaning and units of each column.

The dataset is deliberately small and fixed, so no download or data-cleaning step is required. The dataset is **synthetic teaching data**; the values are illustrative inputs, not live or historical market observations.

## Expected Final Deliverable

A concise written project plan (`artifacts/t1/project-plan.md`) that records the goal, available data, milestones, a data limitation, and the next action. Later tutorials are planned to build on this repository to produce a bounded analysis task and a verifiable agent workflow.

## Three Project Milestones

1. **Project setup (T1)** — Create this initial plan and review it with Git versioning.
2. **Analysis design** — Define a bounded analysis task based on the fixed ETF snapshot.
3. **Verifiable agent workflow** — Organize an agent-assisted workflow with clear verification steps.

## One Data Limitation

All numeric values in the dataset are synthetic teaching assumptions, not current quotations, verified historical estimates, or forecasts. The dataset also omits correlations, taxes, transaction costs, liquidity, currency exposure, and investor-specific constraints, so any later analysis is planned to be illustrative only and must not be used as investment advice or the basis for a real investment decision.

## Next Action

Review this plan, then save it with Git (per the tutorial, the agent does not commit or push during T1). After that, proceed to the next tutorial to design the bounded analysis task.
