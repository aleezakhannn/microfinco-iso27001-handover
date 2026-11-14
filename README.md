# MicroFinCo ISO 27001 Handover

## Project Overview

A fictional ISO/IEC 27001 compliance project for MicroFinCo. It compares MicroFinCo's sample security processes against the Annex A controls, turns the gaps into a scored risk register, and presents the results in a live dashboard and an executive summary.

**Project snapshot**

| Item | Result |
|---|---|
| Controls evaluated | 35 |
| Implemented / Partial / Not | 14 / 14 / 7 |
| Risks in register | 12 |
| Highest risk score | 20 |
| High risks (score 15+) | 5 |
| Gaps on the roadmap | 21 |

## Deliverables

- [Executive_Summary.pdf](Executive_Summary.pdf): two-page summary of findings, risk scores and top 3 actions
- [Remediation_Roadmap.md](Remediation_Roadmap.md): all control gaps with owner, target date and status
- [iso27001_gap_analysis.csv](iso27001_gap_analysis.csv): control-by-control status and evidence notes
- [risk_register.csv](risk_register.csv): 12 scored risks with mitigations
- [scope.pdf](scope.pdf) and [scope.md](scope.md): test scope and board authorization (authorization date 30 October 2026)
- [index.html](index.html): dashboard source code

## Dashboard URL

**Live dashboard:** https://aleezakhannn.github.io/microfinco-dashboard/

## How to Use

1. Open the dashboard link to see summary cards, the control status bar chart, the risk heat map and the top risks table.
2. The dashboard reads the gap analysis and risk register CSV files from GitHub on every load, so the charts update when those files change (GitHub may cache raw files for a few minutes).
3. Read the executive summary first, then the roadmap for the detailed actions.
4. To update the results, edit the CSV files and reload the dashboard.

## Release Tag

This repository is tagged **v1.0** (first complete handover).

Training exercise only. MicroFinCo and all data are fictional.