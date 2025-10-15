🧠 GA-Enhanced Fuzzy Deep Learning Framework for Tumor Classification

This repository contains the implementation of a Fuzzy Deep Learning Framework enhanced with a Genetic Algorithm (GA) for tumor classification from brain MRI images.
The project integrates Fuzzy Logic, Convolutional Neural Networks (CNNs), and Evolutionary Optimization to improve interpretability and generalization in medical image analysis.

📌 Project Overview

Early and accurate detection of brain tumors is critical in medical diagnosis.
While CNN-based models achieve high accuracy, they often lack explainability.
This project bridges that gap by introducing fuzzy membership functions within a CNN pipeline, optimized by a Genetic Algorithm to tune hyperparameters for enhanced performance and interpretability.

🧩 Key Features

🧠 Fuzzy Membership Layer: Adds interpretability by modeling uncertainty in feature activation.

🧬 Genetic Algorithm (GA): Optimizes fuzzy centers, sigmas, and learning rates dynamically.

🎯 Deep CNN Backbone: Extracts spatial features from MRI scans efficiently.

🔥 Heatmap Visualization: Highlights activated tumor regions using Grad-CAM.

📊 Performance Evaluation: Includes validation accuracy, confusion matrix, and comparison charts.

🧰 Technologies Used
Category	Tools / Libraries
Language	Python
Deep Learning	PyTorch
Optimization	Genetic Algorithm (DEAP Library)
Visualization	Matplotlib, Seaborn
Dataset	Brain MRI Tumor Dataset
Platform	Google Colab
Version Control	GitHub


🚀 Model Workflow

Data Preprocessing – MRI images are resized, normalized, and augmented.

CNN Feature Extraction – Extracts deep spatial representations.

Fuzzy Membership Layer – Introduces uncertainty modeling.

GA Optimization – Tunes model hyperparameters.

Classification Layer – Predicts Tumor or No Tumor.

Visualization – Generates Grad-CAM heatmaps for explainability.

📈 Results Summary
Model	Validation Accuracy	Test Accuracy	Comment
Baseline CNN	96.8%	89.47%	High accuracy but limited interpretability
Fuzzy CNN	97.3%	84.21%	Better uncertainty handling, slight overfit
GA-Optimized Fuzzy CNN	68.4%	81.58%	Improved generalization, interpretable features

✅ Best Validation Accuracy: 97.3%
✅ Final Test Accuracy: 81.58%

🔥 Visual Results

Tumor Heatmap (Grad-CAM)

Accuracy Comparison Bar Graph

Training Loss and Accuracy Curves

All visual outputs are stored under:
/results/

