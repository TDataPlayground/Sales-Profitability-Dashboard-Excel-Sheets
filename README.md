# Sales & Profitability Performance Dashboard

A fully interactive retail dashboard built entirely with Google Sheets formulas — no Apps Script, no Looker Studio, no external BI tool. One dropdown drives every KPI and every chart, live.

## What This Project Does
Turns real, raw retail order data into a board-ready dashboard using formula-based analysis alone — the exact spreadsheet skill most companies test for in a live analyst interview.

## Tools Used
Google Sheets formulas only: XLOOKUP, SUMIFS, AVERAGEIFS, COUNTIFS, INDEX/MATCH, nested IF/IFS, UNIQUE, FILTER

## Dataset
Sample Superstore dataset — real US retail order data, ~9,994 rows, sourced from Kaggle.

## Research Questions
1. Which regions, states, and categories drive the most sales and profit?
2. Which sub-categories generate strong profit per unit, and which lose money?
3. How does discount level affect profit, and where does it turn negative?
4. Does shipping mode relate to profitability?
5. What should a weekly leadership dashboard show?

## Key Insight
At a 21%+ discount, average profit margin drops to -78.45% — the exact point where discounting stops costing less profit and starts actively losing money. Several sub-categories (including Supplies and Tables) are flagged "Review — High Volume, Losing Money," moving real volume while losing money per unit — a signal no single raw column would surface on its own.

## Live Spreadsheet
https://docs.google.com/spreadsheets/d/1JIaKVGmz9McIgA-zlLL_anRtIouj_agUB59RktnPmJY/edit?usp=sharing
