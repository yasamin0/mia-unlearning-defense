# MIA-Unlearning-Defense

A practical experimental framework for evaluating **Membership Inference Attacks (MIAs)** before and after **machine unlearning**, with the goal of developing a novel defense strategy.

## 🎯 Objective

This project aims to:

- Implement a CNN model on MNIST
- Evaluate baseline membership inference attacks (MIAs)
- Apply simple unlearning strategies (e.g., fine-tuning, retraining)
- Measure privacy leakage before and after unlearning
- Propose and test an initial idea for a defense mechanism

## 🧪 Project Stages

1. Load and preprocess MNIST dataset
2. Train a baseline CNN model
3. Perform a basic MIA on the trained model
4. Apply an unlearning process by removing selected data points
5. Re-evaluate the MIA after unlearning
6. Propose and implement a defense method to reduce MIA success

## 🗂️ Folder Structure

mia-unlearning-defense/
│
├── data/ # Datasets (MNIST, auto-downloaded)
├── models/ # Trained models
├── experiments/ # Scripts for training, MIA, unlearning
├── defense/ # Experimental defense implementations
├── results/ # Output logs, graphs, evaluation
├── README.md # This file
├── requirements.txt # Dependencies
└── main.ipynb # Notebook to run step-by-step

## 🚀 How to Run

```bash
git clone https://github.com/yasamin0/mia-unlearning-defense.git
cd mia-unlearning-defense
pip install -r requirements.txt
jupyter notebook main.ipynb
```

📚 References
Shokri et al. (2017): Membership Inference Attacks

Zhang et al. (2020): Unlearning & Increased MIA Vulnerability

Guo et al. (2020): Certified Data Removal

Gu et al. (2024): Auditing Privacy Protection

👨‍💻 Author : Yasamin Hosseinzadeh Sani
This project is part of a master's thesis on privacy-preserving machine learning.
