# QuickBooks Conversion Toolkit

This repository merges the browser tools from `QBD2QBO`, `QBO-To-CSV`, and the standalone QBD reconciler into one app entry point.

## Included tools

- `QBD to QBO Prep`: normalize QuickBooks Desktop CSV exports, generate QBO-ready chart of accounts imports, create bank rules, split monthly CSV files, and build leftover rules.
- `QBD Reconciler`: compare QuickBooks Desktop register data with bank activity, review matched/unmatched transactions, and export reconciliation results.
- `QBO to CSV`: convert QBO/OFX bank files to clean CSV files, with account grouping, deduping, previews, and per-account downloads.

## Files

- `index.html`: unified launcher with tabs for both tools.
- `qbd2qbo.html`: original QBD to QBO workflow tool.
- `qbd-reconciler.html`: standalone QBD reconciliation tool.
- `qbo-to-csv.html`: original QBO/OFX to CSV converter.

Open `index.html` in a browser, or enable GitHub Pages for the repository and use it as the site entry point.
