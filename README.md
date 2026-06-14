# Power BI Facade Progress Dashboard

Power BI reporting project built to track facade and building progress data across construction projects using XANO API data, Power Query transformations, DAX measures, and reusable report templates.

## Project Summary

This project demonstrates how operational construction data can be transformed into stakeholder-facing Power BI dashboards for project monitoring. The reports track unit-level progress, status movement, and project-level KPIs using data sourced from XANO and shaped through Power Query and DAX.

## What I Built

- Power BI dashboards for multiple facade and construction projects
- Power Query logic for API-based `units` and `unit_status` ingestion
- incremental refresh logic for status history datasets
- current-status derivation from raw unit history
- DAX measures and dynamic report titles
- reusable parameterized report structure for multiple projects
- helper automation to update project parameter values

## Business Use Case

The dashboards were designed to help project stakeholders monitor live construction progress, review current unit status, and track project-level KPI movement across facade projects.

## Key Features

- multi-project dashboard structure
- reusable report templates
- API-driven data transformation using Power Query
- incremental refresh with `RangeStart` and `RangeEnd`
- status-history to current-status logic
- dynamic filtering and report labeling with DAX
- parameter update automation for project switching

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
    bridgend-college-b02-b01-progress-dashboard.pbix
    bridgend-college-b02-progress-dashboard.pbix
    quorum-b-progress-dashboard.pbix
    upper-one-progress-dashboard.pbix
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

- `reports/final/bridgend-college-b02-b01-progress-dashboard.pbix` - combined Bridgend College dashboard
- `reports/final/bridgend-college-b02-progress-dashboard.pbix` - Bridgend College B02 dashboard
- `reports/final/quorum-b-progress-dashboard.pbix` - Quorum B dashboard
- `reports/final/upper-one-progress-dashboard.pbix` - Upper One dashboard
- `queries/current-units-query.txt` - current unit-state transformation logic
- `queries/unit-status-incremental-refresh.txt` - incremental-refresh-ready status query
- `dax/dynamic-project-title.txt` - dynamic project title logic
- `scripts/update-project-parameter.py` - automation for updating project parameter values

## Dashboard Focus Areas

- current unit progress by project
- status distribution and movement
- construction type filtering
- project-level KPI summaries
- reusable report structure across multiple projects

## Outcome

This project shows how to build reusable Power BI dashboards that turn API-driven construction data into stakeholder-friendly progress reporting with structured transformation logic, incremental refresh support, and practical reporting automation.

## Notes On Screenshots

The repository includes representative screenshots for the dashboard style and reporting layout. True page screenshots for each `.pbix` file are best exported directly from Power BI Desktop, because `.pbix` files do not reliably include normal page preview images that can be extracted as portfolio screenshots.
