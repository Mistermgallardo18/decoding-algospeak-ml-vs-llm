# decoding-algospeak-ml-vs-llm
Final Year Project (BSc Data Science): Comparing classical machine learning models and large language models for detecting algospeak (coded language used to evade moderation) in social-media text.

# Decoding Algospeak: ML vs LLMs for Detecting Coded Language on Social Media

## Project Overview
This project investigates the detection of *algospeak*—coded or euphemistic language used by social-media users to evade automated moderation systems. The study compares the performance of traditional machine learning (ML) models and large language models (LLMs) in identifying algospeak within social-media text.

The project is conducted as a Final Year Project for the BSc (Hons) Data Science and Analytics at the University of Westminster.

## Aims and Objectives
- Compare the performance of traditional ML models (e.g. Logistic Regression, Naive Bayes) with LLMs (e.g. BERT, GPT) for algospeak detection.
- Evaluate the role of semantic context in identifying coded or evasive expressions.
- Develop an NLP pipeline for data collection, preprocessing, feature extraction, and text classification.
- Analyse implications of algorithmic moderation, bias, and fairness in online language evolution.

## Data
Due to access restrictions imposed by platform anti-bot mechanisms, the project adopts a staged data strategy:
- A manually curated exploratory dataset of Reddit comments from moderation-sensitive communities (e.g. sex education and LGBT subreddits).
- Synthetic data augmentation to prototype and validate the NLP pipeline.
- Planned expansion to larger real-world datasets in later project stages.

All data used in this repository has been anonymised and is included for academic purposes only.

## Methodology
The project follows a standard NLP workflow:
1. Text cleaning and preprocessing
2. Feature extraction using TF-IDF
3. Baseline classification using traditional ML models
4. Prompt-based and transformer-based LLM evaluation
5. Comparative analysis of model performance

## Repository Structure
data/
manual_reddit_comments.csv
synthetic_augmented.csv
notebooks/
01_preprocessing_and_baseline_ml.ipynb
02_llm_evaluation.ipynb
README.md
requirements.txt


## Current Status
This repository reflects work completed for the Interim Progress Demonstration (IPD), including:
- Exploratory dataset construction
- Baseline ML implementation
- Initial LLM evaluation
- Documentation of methodological challenges and next steps

## Current Results (IPD stage)

Baseline experiments using TF-IDF features with Logistic Regression and Naive Bayes achieved ~79% accuracy on an exploratory algospeak dataset. Results indicate strong performance on explicit algospeak but reduced effectiveness on neutral and context-dependent cases, motivating further comparison with Large Language Models.


## Ethical Considerations
All data is publicly accessible text. Usernames and identifying information have been removed. The project complies with university ethical guidance for data science research.

## Author
Michael Gallardo  
BSc (Hons) Data Science and Analytics  
University of Westminster
