# Databricks Assistant – Workspace Instructions

These apply to everyone in this workspace.  
Keep them concise, business-relevant, and aligned with data governance.

---

## Coding Conventions
- Always use **snake_case** for variable names.
- Use 4 spaces for indentation (no tabs).

## Data Sources
- Sales data must always come from: `catalog.schema.gold_sales`.
- Do not use deprecated `silver_sales` table.

## Visualization
- Default to **matplotlib** for charts unless explicitly overridden.

## Presentation
- Dates must be formatted as `YYYY-MM`.
- Monetary values rounded to 2 decimals, prefixed with currency `USD`.

---
