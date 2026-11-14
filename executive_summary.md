---
title: "MicroFinCo ISO 27001 Executive Summary"
date: "14 November 2026"
---

## Purpose

This summary reports the results of the ISO/IEC 27001 Annex A gap analysis and risk assessment for MicroFinCo (a fictional company) and sets out the priority actions for the board. All data is fictional and prepared for training.

## Key Findings

35 Annex A controls were evaluated against MicroFinCo's sample policies, configuration files and records.

| Status | Controls | Share |
|---|---|---|
| Implemented | 14 | 40% |
| Partial | 14 | 40% |
| Not implemented | 7 | 20% |

Only 40% of evaluated controls are fully in place. The seven missing controls include incident response, access reviews, information classification and independent review. Strong areas are policy governance, physical access, malware protection and network controls.

## Risk Scores

The 21 gaps produced 12 risks in the risk register. Each is scored as impact (1 to 5) multiplied by likelihood (1 to 5), for a maximum of 25. Five risks score 15 or above.

| Risk | Description | Score |
|---|---|---|
| R-001 | No MFA for privileged accounts | 20 |
| R-002 | No incident response plan | 20 |
| R-003 | No periodic review of user access rights | 16 |
| R-004 | Open vulnerabilities not tracked to closure | 16 |
| R-005 | Backups never restore-tested | 15 |

The remaining seven risks score between 8 and 12.

## Top 3 Remediation Actions

1. **Enforce MFA for all privileged users** (R-001, target 15 December 2026). This removes the highest-scoring risk and reduces the chance of account takeover.
2. **Approve and test an incident response plan** (R-002, target 20 December 2026). Named roles and a tested plan let MicroFinCo contain breaches quickly.
3. **Run quarterly access reviews** (R-003, target 15 January 2027). Regular reviews remove stale and excessive access.

## Next Steps

The full list of 21 gaps, with owners, target dates and status, is in the Remediation Roadmap. Progress should be reviewed monthly and the gap analysis repeated after the first round of fixes. The live dashboard shows current control coverage and the risk heat map.