#Project Overview

This project presents a research-oriented machine learning pipeline for multiclass classification of plant leaves using a relatively small dataset (~182 samples). The study focuses on evaluating the performance of neural networks and ensemble models under constrained data conditions, with an emphasis on generalization, overfitting control, and reproducibility.

#Objectives

Build a fully pipeline-based ML workflow for classification
Evaluate MLP (Multilayer Perceptron) and Random Forest models on different levels of features

#Methodology

🔹 Data Preprocessing

Removing duplicates
Feature scaling using StandardScaler

🔹 Pipeline Design


All models are implemented using scikit-learn pipelines to ensure:

Reproducibility

Clean workflow integration

Prevention of data leakage


#Experimental Design

Fully pipeline-based implementation

Train-test split evaluation

Models:
MLP, Random Forest

#Key Findings

MLP outperformed RF with small data set

Random Forest depends heavily on feature selection
