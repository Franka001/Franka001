# Zaryn Data Engineering
### Practical Data Solutions for Manufacturing & Wholesale Distribution

Connect your operational data. Reduce manual reporting. Make business metrics easier to trust.

I'm Franka, founder of Zaryn Data Engineering in Anna, Texas. I provide independent, project-based data engineering services for smaller manufacturers and wholesale distributors with limited internal data engineering capacity.

My professional background includes data engineering work in healthcare, aerospace, and body-shop businesses. Zaryn's current service focus is manufacturing and wholesale distribution.

[Discuss a project](mailto:admin@zaryndata.onmicrosoft.com) · [Explore the showcases below](#portfolio-showcases)

## When to Bring Me In

- Your team combines database extracts and spreadsheets to prepare recurring reports.
- Inventory, purchasing, sales, or production reports disagree across departments.
- An existing SQL Server or SSIS process needs investigation, improvement, or documentation.
- You need a defined integration or reporting project without hiring a full-time data engineer.
- Your team needs a practical modernization assessment before committing to a new platform.

## Focused Project Services

| Engagement | Scope we agree together | Typical deliverables |
|---|---|---|
| Data & Reporting Assessment | One operational reporting or integration problem | Source inventory, process map, risks, and a prioritized implementation proposal |
| Integration & Reporting Pilot | A defined set of sources and business questions | Data transformations, validation checks, analytical outputs, and setup documentation |
| SQL Server & SSIS Improvement | A specified workload or failure pattern | Findings, agreed code changes, reconciliation checks, and recovery instructions |
| Operational Workflow Automation | A defined notification, approval, or exception process | Agreed workflow, error-handling approach, and handover documentation |

Each engagement is scoped to solo delivery. Source access, acceptance criteria, schedule, licensing, and support boundaries are agreed before work begins. I work with the existing environment where appropriate; modernization is a decision, not a default requirement.

## Portfolio Showcases

These examples make the code, business rules, and reporting outputs available for inspection without requiring visitors to provision a cloud environment.

### 1. Wholesale Inventory & Fulfillment Analytics

How should partial shipments, cancellations, and promised dates affect fulfillment reporting?

The local Python implementation calculates outstanding quantities and on-time fulfillment measures from synthetic order and shipment data. Tests cover expected results, invalid shipment records, and repeatable output. The broader inventory architecture is documented as a future extension.

![Zaryn wholesale fulfillment reporting preview](https://raw.githubusercontent.com/Franka001/zaryn-distribution-inventory-analytics/main/reports/dashboard.png)

[View code and setup](https://github.com/Franka001/zaryn-distribution-inventory-analytics) · [Read the reporting notes](https://github.com/Franka001/zaryn-distribution-inventory-analytics/tree/main/reports)

### 2. Integration Modernization & Reconciliation

How can a replacement load be checked for correctness and recover safely after a failure?

The Python/SQLite reference implementation demonstrates incremental updates and deletes, checkpointing, full-state reconciliation, and transaction rollback. The assessment checklist connects these engineering controls to a proposed SQL Server and SSIS modernization engagement.

![Zaryn modernization data-state reporting preview](https://raw.githubusercontent.com/Franka001/zaryn-ssis-modernization/main/reports/dashboard.png)

[View code and setup](https://github.com/Franka001/zaryn-ssis-modernization) · [Read the reporting notes](https://github.com/Franka001/zaryn-ssis-modernization/tree/main/reports)

### 3. Manufacturing Operations Analytics

How can operational source data be organized into a documented analytics workflow?

Explore the existing SQL scripts, sample-data assets, project structure, and proposed Fabric analytics architecture. The repository separates available artifacts from implementation and validation work still to be completed.

[Explore the manufacturing project](https://github.com/Franka001/zaryn-manufacturing-analytics)

### Evidence and Scope

Portfolio demonstrations are separate from my professional employment history and are not presented as Zaryn client deployments. The two reporting previews are static Python-generated PNGs based on synthetic snapshots, not Power BI screenshots. The modernization runtime is SQLite, not SSIS or SQL Server. Proposed Microsoft cloud architectures are design work; no deployed ADF/Fabric environment, production scale, or client savings are claimed. Each repository documents its implementation scope and limitations.

## Microsoft Technology Focus

| Area | Technologies |
|---|---|
| Data platforms | Microsoft Fabric, Azure Data Lake Storage, SQL Server |
| Integration | Azure Data Factory, SQL Server Integration Services (SSIS) |
| Transformation | SQL, PySpark, Python |
| Automation | Power Automate, Azure Logic Apps |
| Business reporting | Power BI |

This is my service technology focus, not a claim that every tool is implemented in each showcase.

## How We Work Together

1. Define the problem and the business decisions the output must support.
2. Review source access, data quality, dependencies, and constraints.
3. Agree a bounded scope, deliverables, acceptance checks, and price.
4. Implement, validate, document, and hand over the agreed solution.

## Discuss Your Project

Email [admin@zaryndata.onmicrosoft.com](mailto:admin@zaryndata.onmicrosoft.com) with your business challenge, source systems, and desired timeline.

Please send only a high-level overview initially. Do not send passwords, access tokens, personal information, or confidential datasets.

---
Zaryn Data Engineering | Independent Project Delivery | Manufacturing & Wholesale Distribution
