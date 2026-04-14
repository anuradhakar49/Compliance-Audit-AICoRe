# AICoRe-  AnExtensible Auditing Tool for High-Risk AI

AICoRe is a web-based compliance auditing platform that integrates multi-framework model compliance assessment, SHAP-based explainability, and automated regulatory report generation in a single reproducible pipeline. 

---
*Authors*: Nafissatou Ndiaye, Johanna Fokui, Julie Abouem, Diarra Gningue, Mounina Toure, Anuradha Kar

*Affiliation*: aivancity School of AI & Data for Business & Society, Paris Campus, Villejuif, 94800, France

*Corresponding author email*: kar@aivancity.ai

## Repository structure

```
AICoRe/
│
├── README.md                    ← You are here
│
├── Reports/               ← Per-domain full compliance audit reports made with AICoRe
│   ├── README.md
│   ├── Healthcare_compliance_FullReport
│   ├── Education_Compliance_FullReport
│
├── dashboard/                   ← Interactive compliance dashboard
│   ├── README.md
│   └── Compliance_Dashboard.html
│
└── datasets/                    ← Benchmark datasets used for evaluation
    ├── README.md
    ├── healthcare
    ├── education
```

---

## Overview

The tool addresses a critical gap in the existing AI compliance landscape: no open-source tool integrates all of the following in a single pipeline.

| Capability | TrustworthyAudit | IBM AIF360 | MS Fairlearn | Credo AI |
|---|---|---|---|---|
| GDPR pre-training gate | ✓ | — | — | — |
| EU AI Act mapping | ✓ | — | — | ~ |
| NIST RMF mapping | ✓ | — | — | ~ |
| SHAP proxy detection | ✓ | — | ~ | — |
| Multi-framework simultaneous | ✓ | — | — | ~ |
| Structured report export | ✓ | — | ~ | ✓ |
| Open-source | ✓ | ✓ | ✓ | — |
| Cross-domain validation | ✓ | — | — | — |

## Regulatory frameworks supported in current version

| Framework | Scope | Type |
|---|---|---|
| EU AI Act (2024/1689) | Risk classification · Annex III · Arts 9–16 | Binding · EU |
| GDPR | Arts 5, 6, 9, 22, 25, 35 | Binding · EU |
| NIST AI RMF | Govern · Map · Measure · Manage | Voluntary · US |
| FERPA / COPPA | Education and child data | Binding · US sectoral |

## Requirements

```bash
Python >= 3.9
scikit-learn >= 1.3
pandas >= 1.5
numpy >= 1.23
shap >= 0.42
matplotlib >= 3.6
seaborn >= 0.12
```

## License

This project is released under the [MIT License](LICENSE). Regulatory framework documents included in the knowledge base are used for research purposes only and remain the property of their respective issuing bodies.

