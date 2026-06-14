# Power BI Progress Dashboard Case Study

Portfolio-safe Power BI case study showing how API-fed operational data can be transformed into reusable progress dashboards with Power Query, DAX, and repeatable report logic.

## Project Summary

This repository showcases my contribution to a reporting workflow used for construction-style progress tracking. The public version intentionally removes client-identifying details, branded visuals, and sensitive source data while preserving the technical approach, report structure, and transformation logic.

## What I Built

- reusable Power BI dashboard structure for project progress reporting
- Power Query logic for API-based `units` and `unit_status` ingestion
- incremental refresh pattern for status history datasets
- current-status derivation from raw event history
- DAX measures and dynamic project labeling
- parameterized report setup for multi-project reuse
- helper automation to update project parameter values

## Portfolio Framing

This public version is presented as a technical case study rather than a client delivery. It focuses on:

- report architecture
- transformation logic
- refresh strategy
- KPI design
- reusable project parameterization

## Key Features

- reusable dashboard template structure
- API-driven data transformation using Power Query
- incremental refresh with `RangeStart` and `RangeEnd`
- status-history to current-status modeling
- dynamic filtering and report labeling with DAX
- helper automation for project switching

## Technologies Used

- Power BI
- Power Query (M)
- DAX
- Excel
- Python
- REST API
- JSON

## Repository Structure

```text
README.md
reports/
  final/
queries/
  current-units-query.txt
  unit-status-incremental-refresh.txt
  units-api-query.txt
  unit-status-api-query.txt
dax/
  dynamic-project-title.txt
scripts/
  update-project-parameter.py
screenshots/
docs/
  kpis.md
  data-model.png
```

## Key Repository Files

- `queries/current-units-query.txt` - current unit-state transformation logic
- `queries/unit-status-incremental-refresh.txt` - incremental-refresh-ready status query
- `dax/dynamic-project-title.txt` - dynamic project title logic
- `scripts/update-project-parameter.py` - helper automation for parameter updates
- `docs/kpis.md` - KPI definitions and reporting focus

## Screenshots And Data

Client-branded dashboards, project names, and internal reporting visuals should not be shared publicly unless they have been recreated or explicitly approved for release.

For a public portfolio version, the safest options are:

- replace screenshots with recreated mock dashboards
- blur or crop branded headers and project names
- keep only sanitized diagrams showing report layout and KPI categories

## Outcome

This project demonstrates my ability to build reusable Power BI reporting solutions that convert API-driven operational data into stakeholder-friendly dashboards with structured transformation logic, incremental refresh support, and maintainable multi-project setup.
