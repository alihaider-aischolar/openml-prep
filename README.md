# OpenML Preparation & Benchmarking  
**European Summer of Code 2025 — Applicant Preparation (OpenML Track)**  
Prepared by: Ali Haider (github.com/alihaider-aischolar)

---

## 🎯 Purpose of This Repository
This repository is my structured preparation for the **AI-on-Demand Platform × OpenML** project under  
**ESoC 2025 + GC.OS (German Center for Open Source AI)**.

It includes:

- Hands-on experiments using **openml-python**
- Benchmarking with scikit-learn & sktime model families
- Small reproducibility studies using OpenML tasks
- Exploration of OpenML dataset metadata
- Preparation for my entrance task PR to `openml-python`

This repo demonstrates my understanding of:
- OpenML pipelines  
- Python ML engineering  
- Reproducible experiments  
- OSS workflows  
- Benchmarking methodology  

---

## 📂 Repository Structure



notebooks/       # Jupyter research notebooks  
scripts/         # Utility scripts (download, benchmarking, helpers)  
reports/         # Experimental notes & results  
requirements.txt # Dependency list  



---

## 📘 Notebooks Overview

Each notebook builds toward real OpenML contribution readiness.

### 01_openml_basics.ipynb
- Connect to OpenML
- Load datasets
- Understand OpenML objects: Dataset, Task, Flow, Run

### 02_dataset_exploration.ipynb
- Dataset metadata analysis
- Feature inspection
- Target distribution analysis

### 03_model_benchmarking.ipynb
- Compare baseline ML models on OpenML tasks
- Track results reproducibly

### 04_reproducibility_experiments.ipynb
- Same model, different environments
- Reproducibility challenges

### 05_integration_sklearn_sktime.ipynb
- How OpenML interacts with common ML libraries
- Prepares me for contributing to `openml-python`

---

## 🧪 Scripts Overview

### download_dataset.py
Utility to fetch datasets from OpenML and save them locally.

### run_benchmark.py
Runs model training, evaluation, and logs results.

### utils.py
Helper functions for preprocessing, evaluation, logging.

---

## 📊 Reports
Experimental results & notes collected during my preparation.

---

## 📦 Requirements

See `requirements.txt` for required libraries.

---

## 🔗 Related Project
This repository supports my contribution to:

**openml/openml-python**  
(ESoC 2025 entrance PR)

---

## 🧑‍💻 Author
Ali Haider  
Email: alihaider.aischolar@gmail.com  
GitHub: github.com/alihaider-aischolar
