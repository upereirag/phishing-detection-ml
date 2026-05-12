# Phishing Detection: ML Classifiers vs Rule-Based Approaches

## Research Question

Can classical machine learning models effectively detect phishing emails,
and how do different algorithms compare in precision and recall?

## Motivation

Phishing attacks are one of the most prevalent cybersecurity threats today.
This project investigates whether simple ML classifiers can outperform
traditional rule-based detection systems, using real-world email datasets.

## Dataset

- **Source:** [Phishing Email Dataset](https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset) — Kaggle
- **Size:** 82,486 emails
- **Balance:** 52% phishing, 48% legitimate

## Models

| Model               | Accuracy | Precision | Recall | F1  |
| ------------------- | -------- | --------- | ------ | --- |
| Logistic Regression | 98%      | 98%       | 98%    | 98% |
| Naive Bayes         | 96%      | 96%       | 96%    | 96% |

## Key Findings

- Logistic Regression outperforms Naive Bayes by 2% across all metrics
- False negative rate (phishing classified as legitimate) is below 2%
- TF-IDF with 5,000 features provides strong text representation

## Tech Stack

- Python 3.14
- scikit-learn
- pandas
- matplotlib / seaborn

## Author

Guilherme U. Pereira  
B.S. Student in Artificial Intelligence & B.S. Student in Blockchain and Digital Cryptography — FMU  
Cisco Cybersecurity Week 2026 — Selected Participant  
Cisco Cyber Education Program 2026— Scholarship Holder
