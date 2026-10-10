# Fake Job Posting Detection Using Machine Learning

## Overview

This project investigates machine learning methods for detecting fraudulent job postings and evaluates their robustness against adversarial manipulation.

The experiments use the Employment Scam Aegean Dataset (EMSCAD), containing 17,880 job postings.

## Objectives

* Build a text-based fraud detection model.
* Evaluate how AI-generated paraphrasing affects model performance.
* Compare text-based classification with metadata-only classification.
* Investigate the impact of metadata manipulation on fraud detection.

## Methods and Technologies

* **Language:** Python
* **Data processing:** Pandas, NumPy
* **Text representation:** TF-IDF
* **Machine learning:** Logistic Regression, Random Forest, LightGBM, CatBoost
* **Evaluation:** Precision, Recall, F1-score, ROC-AUC, McNemar's test

## Key Experimental Findings

* The baseline TF-IDF and Logistic Regression model achieved **85.55% fraud recall** on clean test data.
* AI-generated text paraphrasing reduced fraud recall to **60.69%**.
* A metadata-only LightGBM model achieved **84.97% fraud recall** on clean metadata.
* Manipulating metadata features reduced LightGBM fraud recall to **30.06%**.

These results illustrate the limitations of relying on a single type of signal for fraud detection.

## Dataset

The experiments use the publicly available EMSCAD dataset.

Dataset source: [Employment Scam Aegean Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)

## Repository Contents

Source code, experiment configurations, evaluation results, and visualizations will be organized here as they are added.

## Reproducibility

Installation instructions, dependencies, and execution steps will be documented after the source code and project environment are added.

## Research Scope

This repository is intended to share the implementation and experimental workflow. The research paper and abstract are not included.

---

**Author:** Sanjeev Singh

