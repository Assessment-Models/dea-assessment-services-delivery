# Services Delivery Assessment

Assess services delivery capability — time-to-market, quality, customer outcomes, flow efficiency, and team health.

---

## Overview

This repository contains one assessment instrument for the **services-delivery** domain. It is part of the [DEA Assessment Tools catalog](https://github.com/Assessment-Models/dea-catalog-assessment-tools).

| Item | Value |
|------|-------|
| **Domain** | `services-delivery` |
| **Dimensions** | 5 |
| **Total questions** | 18 |
| **Typical duration** | ~70 minutes |
| **Facilitator required** | No |
| **Maturity target** | `dea:maturity-services-delivery` |
| **Owner** | Head of Delivery / VP Engineering |
| **Version** | 1.0.0-alpha |

---

## Dimensions

| # | Dimension | Weight |
|---|-----------|--------|
| 1 | Delivery Predictability | 0.25 |
| 2 | Flow Metrics & Efficiency | 0.20 |
| 3 | Quality & Defect Management | 0.20 |
| 4 | Customer Outcomes & Value | 0.20 |
| 5 | Team Health & Practices | 0.15 |

---

## How to use

1. **Self-assessment** — open `assessments/v1-alpha/instrument.yaml`, score each question 0–3, cite evidence
2. **Facilitated workshop** — see `assessments/v1-alpha/facilitator-guide.md`
3. **Map score to maturity** — use [dea-catalog-maturity-models](https://github.com/Assessment-Models/dea-catalog-maturity-models) to interpret the result

---

## Contents

```
dea-assessment-services-delivery/
├── README.md                          This file
├── LICENSE                            MIT
├── VERSION                            1.0.0-alpha
├── CHANGELOG.md                       Version history
├── CONTRIBUTING.md                    How to add questions
├── assessments/
│   └── v1-alpha/
│       ├── instrument.yaml            The actual questions (18 across 5 dimensions)
│       ├── gap-analysis-template.md   Output deliverable
│       ├── target-state-template.md   Output deliverable
│       ├── facilitator-guide.md       How to run a workshop
│       └── self-assessment-guide.md   How to self-administer
└── .github/
    ├── workflows/ci.yml               Validates instrument.yaml
    └── CODEOWNERS                     Ownership
```

---

## Scoring

Each question uses a 4-point scale:
- **0** — Not started / no awareness
- **1** — Partially addressed / informal practice
- **2** — Formally defined / documented
- **3** — Fully implemented / consistently practiced

Total score = `sum / max_possible × 100` — see [scoring rubric](https://github.com/Assessment-Models/dea-catalog-assessment-tools/blob/main/assessments/scoring-rubric.md).

---

## Related Repositories

| Domain | Repository |
|--------|-----------|
| Architecture Modernization | [dea-assessment-modernization](https://github.com/Assessment-Models/dea-assessment-modernization) |
| Technology | [dea-assessment-technology](https://github.com/Assessment-Models/dea-assessment-technology) |
| Operations | [dea-assessment-operations](https://github.com/Assessment-Models/dea-assessment-operations) |
| Services Delivery | (this repo) |

---

## License

MIT — see `LICENSE`.