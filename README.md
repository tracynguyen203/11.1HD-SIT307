# Early Heart Attack Prediction: Paper Reproduction and Improved Stacking Pipeline

This repository contains the source code, datasets, and technical documentation for reproducing the paper "An efficient stacking-based ensemble technique for early heart attack prediction" (Bhagat et al., 2024) and evaluating a leak-free, improved machine learning solution.

## Prerequisites & Environment Setup
### 1. Requirements
Python: 3.9+
Package Manager: pip

### 2. Installation Steps
Open Git Bash at a folder in your computer where you want to clone my repository and run these:

git clone https://github.com/tracynguyen203/11.1HD-SIT307.git

Paste these prompts in your Command Prompt or PowerShell to clone, install necessay Python libraries:
pip install -r requirements.txt

Then you can open my ipynb files in VSCode or JupyterLab via Anaconda to view, reproduce my code

In my repository contains 2 ipynb files:
1. Part 1 (Paper baseline):
Open: SIT307_11_1HD_part1.ipynb
Run all cells

2. Part 2 (Leak-free proposed pipeline):
Open: 11_1HD_part2.ipynb
Run all cells

## Dataset Overview
Source: Public Health Heart Disease Dataset (Kaggle).
https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/data
Raw Dataset: 1,025 rows across 14 features.
Processed Dataset: 302 unique records after dropping duplicate samples to prevent data leakage.