# KPI Summary

## Purpose

These dashboards were built to monitor facade and construction progress at unit level and project level using API-driven operational data.

## Main Reporting Goals

- track current unit status across projects
- monitor progress by construction stage
- compare project progress visually
- provide quick summaries for stakeholder review
- support repeatable reporting across multiple projects

## Core KPIs

### 1. Total Units

Total number of units included in the selected project or filter context.

### 2. Current Status by Unit

Latest completed status assigned to each unit based on status history.

### 3. Units by Stage

Breakdown of units across stages such as:

- Prepared
- Assembled
- Glazed
- Packed
- Produced
- In Stock
- Out Stock
- Delivered
- Installed
- Accepted

### 4. Project Progress Distribution

Share of units in each current stage for the selected project.

### 5. Construction Type View

Filtered view of progress by construction type where applicable.

### 6. Status Timeline Context

Date and datetime fields derived from Unix timestamps to support time-aware analysis and refresh logic.

## Technical Reporting Features

- Power Query logic for nested JSON expansion
- incremental refresh using `RangeStart` and `RangeEnd`
- current-status derivation from completed history
- dynamic DAX-based report labels
- reusable project parameter structure

## Intended Audience

These dashboards are suited for:

- project stakeholders
- construction progress reviewers
- internal reporting users
- teams monitoring operational status movement
