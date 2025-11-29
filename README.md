# zero-shot-rare-events
Zero-Shot Classifiers for Rare Clinical Events

This project demonstrates an industry-ready workflow for detecting rare clinical events using a zero-shot LLM-to-ML pipeline. Because rare outcomes often lack labeled data, we use a large language model to generate initial labels from raw clinical notes and train a lightweight machine learning model for scalable deployment.

## Project Summary

**LLM Zero-Shot Labeling:
The LLM evaluates each clinical note and assigns “rare event” or “non-event” labels with no task-specific training.

**Synthetic Dataset Creation:
LLM-generated labels are paired with synthetic clinical notes to form a training dataset.

**ML Model Training:
A compact classifier (e.g., logistic regression or XGBoost) learns from LLLM labels to deliver fast, cost-efficient inference.

**Evaluation:
Models are assessed using precision, recall, F1-score, and ROC-AUC to ensure reliable rare-event detection.

This workflow provides a practical solution for organizations that require high-quality predictions in environments where annotated data is limited or costly to obtain.

## Included in This Repository

- Synthetic clinical notes

- Zero-shot prompt templates

- LLM labeling script

- ML training and evaluation pipelines

- Reproducible Jupyter notebooks
