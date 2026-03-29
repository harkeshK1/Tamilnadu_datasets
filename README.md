# Tamilnadu Healthcare Vulnerability Datasets

This repository contains datasets and code used in the research paper:

**"A Data-Driven Multi-Dimensional Framework for Mapping Healthcare Vulnerability and Predicting Intervention Priorities Across Tamil Nadu Districts"**

---

 Overview

This project presents a data-driven framework to assess healthcare vulnerability across districts in Tamil Nadu, India. It integrates multiple socio-economic, health, and infrastructure indicators to identify vulnerable regions and prioritize intervention strategies.

---

Repository Structure

Raw Data Sources

* `climate vulnerability/` – Climate-related risk indicators
* `family health survey/` – Health and demographic data
* `india gdp houshold/` – Economic indicators
* `india hospitals/` – Healthcare infrastructure data
* `monthly expense/` – Household expenditure data

---

Processed & Integrated Data

* `merged_master.csv` – Master dataset combining all sources
* `tamilnadu_7160_KEYS.csv` – Key indicators dataset
* `tamilnadu_combined_keys_nfhs.csv` – Combined NFHS and key metrics
* `tamilnadu_nhfs.csv` – Health survey dataset

---

Analysis & Results

* `tamilnadu_5_scores.xlsx` – Multi-dimensional vulnerability scores
* `tamilnadu_adjusted_vulnerability.xlsx` – Adjusted vulnerability indices
* `tamilnadu_vulnerability_before_after_validation.xlsx` – Validation results

---

Intervention Planning

* `tamilnadu_food_intervention_plan.xlsx` – Food-related interventions
* `tamilnadu_hospital_intervention_plan.xlsx` – Healthcare interventions
* `tamilnadu_hospital_linear_intervention_plan.xlsx` – Linear model-based planning

---

Policy & Thresholds

* `tamilnadu_policy_thresholds_final.xlsx` – Final policy thresholds
* `tamilnadu_policy_thresholds_mean_sd.xlsx` – Statistical thresholds

---

Data Description

* **Region:** Tamil Nadu, India
* **Data Type:** Multi-dimensional (health, economic, climate, infrastructure)
* **Sources Include:**

  * National Family Health Survey (NFHS)
  * Government datasets
  * Economic and environmental indicators

Processing Includes:

* Data cleaning and normalization
* Integration of multiple datasets
* Feature engineering
* Vulnerability scoring and ranking

---

Methodology

* Multi-dimensional vulnerability index construction
* Data normalization and weighting
* Comparative district-level analysis
* Intervention prioritization using data-driven methods

---

Reproducibility

All datasets and preprocessing steps are provided to reproduce the analysis and results presented in the paper.

---

License

This dataset is licensed under the MIT License.

---


