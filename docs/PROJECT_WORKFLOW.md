# Detailed Project Workflow

## Phase 1 — Data Source
Start with IPL Dashboard Project.xlsx. The primary analytical table is IPL_Matches_2008_2022.

## Phase 2 — Data Understanding
Inspect column names, data types, dates/seasons, team names, venue/city values, toss fields, result fields, player fields and umpire fields.

## Phase 3 — Data Preparation
Recommended checks:
- standardize team names
- standardize date/season formats
- identify blank or inconsistent result values
- remove accidental duplicates when appropriate
- verify that winner values correspond to participating teams
- validate categorical fields such as toss decision and result type

## Phase 4 — Analytical Model
Useful dimensions: Season, Team, Venue, City, Player and Match.

Useful measures: Matches played, Matches won, Win percentage, Toss wins, Toss decision counts, Player of Match counts, Super Over count, and average/total win margin where supported by the source field.

## Phase 5 — Dashboard
Recommended sections:
1. Executive KPI cards
2. Season trend
3. Team performance
4. Toss analysis
5. Venue analysis
6. Player analysis
7. Match/result detail table

## Phase 6 — Validation
Compare dashboard totals with source rows, test filter interactions, inspect blanks, verify season/team totals and confirm slicer behavior.

## Phase 7 — Documentation
Document purpose, source data, transformations, model, measures, dashboard navigation, observations and limitations.

## Phase 8 — Delivery
Deliver the original workbook, analysis-ready CSV, diagrams, Markdown documentation and PDF report together.
