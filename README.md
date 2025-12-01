# ANN_USING_PYTORCH
#  ANN Model (v1, v2, v3…) — Training, Hyperparameter Tuning & Fine-Tuning

This repository contains multiple versions of an Artificial Neural Network (ANN) built using PyTorch. Each version (v1, v2, v3, ...) introduces improvements in architecture, hyperparameter settings, training stability, and overall performance. The project provides a clean pipeline for building models, running experiments, and fine-tuning updated versions.

---

##  Project Description

The project includes:

- Multiple ANN versions (v1, v2, v3…) with incremental enhancements  
- Custom dataset creation and DataLoader integration  
- Complete training loop with forward pass, loss, and optimization  
- Hyperparameter tuning across versions  
- Final fine-tuning using best-performing version configs  
- Evaluation pipeline for comparing all ANN versions  

---

##  Features

- Versioned ANN architecture (v1 baseline → v2 improved → v3 optimized)  
- Custom `Dataset` class for efficient data management  
- Model training workflow with loss, optimizer updates, and evaluation  
- Hyperparameter search across versions (LR, batch size, layers, units, optimizers)  
- Fine-tuning stage for the highest-performing ANN version  
- Fully consistent dtype handling and error-free execution  

---

##  Tech Stack

- Python  
- PyTorch  
- NumPy  
- Pandas  
- Matplotlib (optional for plots)
- Optuna
- Jupyter Notebook / Google Colab  

---

##  Objective

The objective of this repository is to build multiple evolving versions of an ANN model and optimize each version through structured hyperparameter tuning and fine-tuning. The versioned structure makes it easy to track improvements and compare performance across iterations.

---

##  Repository Contents

- `ann_v1` – Baseline ANN version  
- `ann_v2` – Improved model with better architecture/hyperparameters  
- `ann_v3` – Optimized version after tuning  
- Custom dataset setup  
- Training & evaluation scripts  
- Hyperparameter tuning notebook  
- Fine-tuning workflow  

---

##  Future Enhancements

- Add more ANN versions (v4, v5…)  
- Introduce new activation functions & regularization  
- Add automated tuning scripts  
- Add performance visualizations  

---
