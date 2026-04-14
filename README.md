# AICoRe-  An Extensible Auditing Tool for High-Risk AI

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
│   └── AICoRe_Compliance_Dashboard.html
│
└── datasets/                    ← Benchmark datasets used for evaluation
    ├── README.md
    ├── healthcare
    ├── education
```

---

## Overview of capabilities

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
| FERPA  | Education and child data | Binding · US sectoral |

## License

This project is released under the [MIT License](LICENSE). Regulatory framework documents included in the knowledge base are used for research purposes only and remain the property of their respective issuing bodies.

