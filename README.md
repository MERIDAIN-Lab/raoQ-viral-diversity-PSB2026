# Benchmarking Rao’s Q for Evolution-Aware Viral α-Diversity  
**Pacific Symposium on Biocomputing (PSB) 2026 – Poster Repository**  

**Authors**  
Florencia Martino, Kakhangchung Panmei, Dylan Duchen, David L. Thomas, Abraham J. Kandathil, Steven J. Clipman  

**Affiliations**  
1. Division of Infectious Diseases, Johns Hopkins University School of Medicine, Baltimore, Maryland, United States of America  
2. Department of Pathology, Yale School of Medicine, New Haven, Connecticut, United States of America  

---

## Overview
This repository contains the analysis code, and reproducible workflows associated with the PSB 2026 poster titled:

> **“Benchmarking Rao’s Q as a Reproducible, Quantitative, Evolution-Aware Metric of Viral α-Diversity for Metagenomic Data.”**

Rao’s quadratic entropy (Rao’s Q) is used here as a distance-based, evolution-aware α-diversity metric that integrates both phylogenetic structure and relative abundance. The framework quantifies the behavior, reproducibility, and interpretability of Rao’s Q in controlled dilution series and clinical plasma viromes.

---

## Repository structure
The repository is organized as follows:

- `src/`  
  Core analysis scripts (R and/or Python) for:
  - computing Rao’s Q from abundance tables and distance matrices or phylogenetic trees  
  - running dilution-series benchmarking  
  - robustness analyses (tree perturbations, cross-mapping, tree collapsing)

- `notebooks/`  
  Jupyter or RMarkdown notebooks reproducing the main analyses and figures shown in the poster.

- `figures/`  
  Exported figures used in the poster (PDF/PNG/SVG).

- `poster/`  
  PDF version and abstract file of the PSB 2026 poster.

---

## Contact

For questions about the analysis, data, or reproducibility framework, please contact:

**Florencia Martino**
Division of Infectious Diseases, Johns Hopkins University School of Medicine
Email: **[fmarti34@jh.edu](mailto:fmarti34@jh.edu)**

**Steven J. Clipman**
Division of Infectious Diseases, Johns Hopkins University School of Medicine
Email: **[sclipma1@jhmi.edu](mailto:sclipma1@jhmi.edu)**

---

## Copy the repository

Clone the repository:

```bash
git clone https://github.com/<your-username>/raoQ-viral-diversity-PSB2026.git
cd raoQ-viral-diversity-PSB2026

