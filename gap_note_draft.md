# Gap Note - Week 0 Day 4/5 (COMPLETED)
**Project:** solubility-ml
**Researcher:** Muhammad Zubair
**Email:** muhammad.zubair@iqraisb.edu.pk
**GitHub:** https://github.com/onlinedrzubair/solubility-ml
**Date completed:** 2026-05-01 13:53

---

## 1. Research Gap Statement (ONE sentence)

> Most aqueous solubility ML models rely on random train/test splits and report performance without applicability domain analysis or feature importance validation, which limits their trustworthiness in early drug discovery; our work addresses this by combining scaffold-based splitting, SHAP-driven interpretability, and dual applicability domain methods on the benchmark ESOL dataset.

---

## 2. Top 3 Competitor Models to Outperform

| # | Paper | RMSE reported | Feature type | How to beat it |
|---|-------|---------------|--------------|----------------|
| 1 | Delaney 2004 — ESOL linear model (J. Chem. Inf. Comput. Sci.) | ~1.01 | 4 physicochemical features | RF/XGBoost with 200 RDKit descriptors beats this easily |
| 2 | Sorkun et al. 2019 — AqSolDB + RF (Scientific Data) | ~0.99 | RDKit descriptors, random split | Scaffold split + AD + SHAP gives more credible result |
| 3 | Francoeur & Koes 2021 — GNN on ESOL (J. Chem. Inf. Model.) | ~0.56 | Graph neural network | Match RMSE while adding full SHAP interpretability — interpretability is our USP |

---

## 3. Fallback Journal Decision

| Field | Value |
|-------|-------|
| Primary journal | AAPS PharmSciTech (no APC) |
| Fallback journal | PLOS ONE |
| Fallback APC | USD 1,695 — Pakistan qualifies for FULL WAIVER (zero cost) |
| Waiver URL | https://plos.org/publish/fees/ |

---

## 4. MDPI Short Communication Downloads (manual)

| File | Save location | Status |
|------|---------------|--------|
| ML_solubility_SHAP_2023.pdf | solubility-ml\literature\ | Manual download from https://www.mdpi.com/1999-4923/15/1/259 |
| GNN_solubility_2022.pdf | solubility-ml\literature\ | Manual download from https://www.mdpi.com/1999-4923/14/10/2240 |
| QSAR_logS_RF_2023.pdf | solubility-ml\literature\ | Manual download from https://www.mdpi.com/1999-4923/15/3/990 |

---

## 5. Remaining Action Items

- [x] Write the ONE-sentence gap statement
- [x] Identify 3 competitor models
- [x] Choose fallback journal (PLOS ONE)
- [ ] Download 3 MDPI PDFs manually (browser — see Section 4)
- [ ] Read all 15 papers using Reading Checklist in papers_metadata.xlsx
- [ ] Copy this gap note into PROJECT_PLAN.md
- [ ] git commit and push (Week 0 complete)

---
*Completed by Week0_Task4_FillGapNote.ps1 on 2026-05-01 13:53*
