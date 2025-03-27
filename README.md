# Asset Flow Comparator

**A portfolio audit and reconciliation tool** that compares financial data from multiple sources — such as Morningstar, Bloomberg, and internal records — to detect discrepancies in reported asset values and fund flows.

This project simulates a realistic asset management pipeline and highlights data accuracy issues using reproducible mock data, statistical metrics, and clear visualizations. Inspired by real-world financial workflows, it's designed to demonstrate core data engineering and analysis skills while preserving confidentiality.


# Project Goals

- Simulate datasets from multiple financial data sources
- Join and reconcile data for asset flows and prices
- Detect discrepancies in reported vs internal data
- Generate metrics to assess data accuracy
- Visualize asset trends and reporting issues


## 🗂️ Data Sources (Mocked)

- **Morningstar** — External provider with asset & flow records
- **Bloomberg** — Alternative price and flow data source
- **Internal** — Simulated firm-side record of assets under management (AUM) and transactions


Each dataset contains overlapping but sometimes inconsistent information on:
- Asset Identifiers (IDs, names, tickers)
- Asset Class (Equity, Fixed Income, etc.)
- Net Asset Value (NAV)
- Flows over time (monthly/weekly)
- Total AUM