---
title: "Repository:BioNumera"
author: "lzd2005"
date: "2025-06-12"
output: html_document 
---
# BioNumera 

Repository for Bioinformatics and Numerical Analysis in Biological Research

Welcome to BioNumera! This repository is dedicated to the integration of bioinformatics and numerical analysis in biological research. It contains code, data, and documentation for projects focused on analyzing and interpreting biological data through quantitative methods.
Key Features

*Bioinformatics Analysis:* Tools and scripts for processing and analyzing biological datasets.

*Data Visualization:* Scripts for creating visual representations of complex biological data.

*Reproducibility:* Detailed documentation and workflows to ensure results can be replicated.

# Frist project: Water Quality Analysis Project

## 📌 Project Overview
This report presents a comprehensive analysis of water quality in a major river system, utilizing multivariate statistical techniques to examine seasonal and spatial variations. The study covers 14 monitoring sites across urban, industrial, and tributary zones, analyzing 19 physicochemical parameters over a 12-month period.The goal is to provide insights into seasonal and spatial variations in water quality and guide future environmental management efforts.

[Original Paper: Liu, Junzhao, et al. "Water quality assessment and source identification of the Shuangji River (China) using multivariate statistical methods." PloS one 16.1 (2021): e0245525.](URL "https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0245525")

[](@replace=1)

## 🔍 Key Findings
### Temporal Patterns
- Identified 3 seasonal clusters with 70.8% classification accuracy:  
  ​**Low-flow** (Nov-Jan), ​**Medium-flow** (Mar-May/Sep-Oct), ​**High-flow** (Jun-Aug)
- Key discriminant parameters: VP, COD, Cu, TP, CN, S, CODMn



[](@replace=2)


### Spatial Patterns
- 3 pollution zones identified with 84.5% accuracy:  
  ​**Urban** (high pollution), ​**Industrial** (moderate), ​**Tributary** (low)
- Dominant pollution sources: Domestic (42%) > Industrial (35%) > Agricultural (23%)



[](@replace=3)


## 📊 Data & Methodology
### Analyzed Parameters
| Category       | Key Parameters                |
|----------------|-------------------------------|
| Basic          | pH, DO, COD                   |
| Nutrients      | NH3-N, TP                     |
| Heavy Metals   | Cu, As, Cd                    |

### Statistical Techniques
1. ​**Factor Analysis** (7 principal components explaining 72.5% variance)
2. ​**Hierarchical Clustering** (Ward's method)
3. ​**Linear Discriminant Analysis** (LDA)



[](@replace=4)


## 🛠️ Usage
### Data Access
```bash
# data structure
├── data/
│   ├── processed_data/
│   └── raw_data/
├── docs/
│   ├── figures
│   └── reports
└── src/
     └── r
```
## Conclusion
This project provides a comprehensive analysis of water quality variations and pollution sources in the river system. The findings highlight the importance of targeted monitoring and management strategies to address pollution effectively.

ContactFor inquiries or collaboration, feel free to reach out: lzd2005@sohu.com
