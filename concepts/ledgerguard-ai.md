# LedgerGuard AI

**Status: Proposed portfolio project — not implemented yet**

## Problem and solution

A proposed transaction-reconciliation engine that imports sample bank and mobile-money records, matches transfers against invoices, and flags mismatches for human review.

## Portfolio focus

Financial reconciliation and anomaly detection. This brief defines an implementation target; it is **not** evidence of a completed application.

## Proposed technology stack

Python, pandas, FastAPI, SQLite, Streamlit

## MVP scope

- Synthetic transaction fixtures
- deterministic matching rules
- discrepancy dashboard
- anomaly scoring
- CSV export

## Acceptance criteria

- A runnable local demo using synthetic or openly licensed data.
- Documented installation steps and reproducible sample output.
- Tests for core business rules and edge cases.
- Screenshots and a short demonstration video.
- Clear explanation of limitations, security considerations and next steps.

## Responsible demonstration

Use only synthetic or appropriately licensed data. Never expose credentials or real customer financial or operational records.
