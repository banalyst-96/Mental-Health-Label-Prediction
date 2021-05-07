# Data-Science-Projects

Welcome to my repository! This repository contains the codes and documentations for my data science projects.

## Project Overview:

Capstone 1 and 2 are variations of one overarching project, which is to build a multiclass classifier capable of distinguishing mental health diagnoses from text excerpts.

## Data Source:

Since a dataset containing text excerpts from individuals living with a mental health condition does not exist, I had to build my own. I did this by extracting data from subreddits on the six classes I chose:
- r/depression
- r/ptsd
- r/cptsd
- r/bpd
- r/bipolar
- r/dissociation

Then, I web scraped for additional data from mentalhealthforum.com which luckily had forum sections for those classes.

## Tools Used:
- Standard machine learning classifiers (SGD, KNN, Log Regression, Random Forest, Decision Trees, and etc.)
- BERT's run_classifier.py
- Huggingface bert-base-uncased <-- best results! End section of Capstone II final report.

## Metrics:
- ROC AUC Curve
- Sklearn Classification_Report (f1 score, precision, recall, and accuracy)
- Matthew's Correlation Coefficient
- Hamming Loss

## I am constantly developing the codes & documentations so please bear with me if there is a disconnect -- the project has evolved beyond what I had originally planned.

