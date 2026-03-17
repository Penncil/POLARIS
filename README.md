# POLARIS_supplementary_material
This repository provides supplementary materials for the paper:  "Federated target trial emulation for time-to-event outcomes via POLARIS: Pooled-equivalent One-shot Likelihood Aggregation for Real-world Inference in Survival" including additional experiments, implementation details, simulation code, and supporting results that are not included in the main manuscript.

## Abstract
Heterogeneous treatment effects (HTE) are key to precision medicine, but most real-world studies lack the scale and diversity needed to detect them. While multi-site analyses offer a potential solution, data-sharing constraints often prevent access to patient-level information across institutions. We introduce POLARIS, a federated framework for time-to-event target trial emulation. POLARIS converts each site’s weighted Cox risk function into a compact tensor shared once with the coordinating center, enabling lossless reproduction of pooled estimates without sharing patient-level data. We applied POLARIS across five U.S. health systems to study risk of gastrointestinal outcomes after GLP-1 receptor agonist (GLP-1RAs) initiation versus sodium-glucose cotransporter 2 inhibitors (SGLT2is) and dipeptidyl peptidase 4 inhibitors (DPP4is). Results showed that GLP-1RAs were consistently associated with higher risks of nausea and vomiting, particularly among men, individuals with higher baseline HbA1c (≥8.5%), and lipid therapy. POLARIS provides a scalable solution for distributed target trial emulation and fine-grained assessment of HTE across diverse health systems.


## About
Code sets and site-specific comparison results for a multi-site study evaluating GLP-1 receptor agonists (GLP-1RA) versus SGLT2 inhibitors (SGLT2i) and DPP-4 inhibitors (DPP4i).
This repository contains harmonized medical condition definitions, medication exposure classifications, and site-level analytic outputs. No patient-level data are included.

---

## Contents

The following files and folders are included in the repository:
- `cluster_master.csv` – Master file containing curated medical condition code clusters used for baseline covariates and outcome definitions;
- `code_med.csv` – File containing medical condition clusters and medication exposure definitions, including GLP-1RA, SGLT2i, and DPP4i classifications;
