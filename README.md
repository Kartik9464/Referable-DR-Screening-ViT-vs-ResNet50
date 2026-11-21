# Automated Referable Diabetic Retinopathy Screening using Vision Transformers vs. ResNet-50

**Institution:** School of Engineering & Technology, Sushant University  
**Authors:** Kartik Sharma (230btccse303), Lakshay (241btccse002), Sumit Yadav (230btccse065)  
**Supervisor:** Dr. Nitin Malik  

## Overview
This repository contains the official PyTorch implementation comparing **ViT-Base/16** against **ResNet-50** for binary clinical screening of Referable Diabetic Retinopathy (Grades 2–4) vs. Non-Referable DR (Grades 0–1) on the **Messidor-2** fundus dataset (1,744 images).

## Experimental Results
| Model | Validation Accuracy | ROC-AUC | Sensitivity | Specificity | False Positives |
| :--- | :---: | :---: | :---: | :---: | :---: |
| **ResNet-50 (Baseline)** | 85.67% | 0.8761 | 68.13% | 91.86% | 21 / 258 |
| **ViT-Base/16 (Proposed)** | **89.40%** | **0.9275** | **70.33%** | **96.12%** | **10 / 258** |

## Repository Structure
- `Referable_DR_ResNet_vs_ViT.ipynb` — Complete Google Colab training & evaluation notebook
- `Referable_DR_ResNet_vs_ViT.py` — Standalone Python script
- `publication_evaluation_results.png` — ROC curves & Confusion Matrices
- `final_accuracy_loss_curves.png` — Training & Validation convergence plots
