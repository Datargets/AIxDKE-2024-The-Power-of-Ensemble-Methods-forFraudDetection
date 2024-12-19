# Financial Fraud Detection with AI

This repository contains resources, methodologies, and findings from an article focused on leveraging AI to tackle financial fraud. It outlines the evolution of fraud detection systems, highlights key advancements, and showcases the performance of machine learning (ML), deep learning (DL), and Large Language Models (LLMs).

---

## Overview

### Importance of the Topic:
Financial fraud undermines market integrity and causes substantial losses. Traditional detection methods often fail to address the growing complexity and volume of fraudulent activities.

### Objectives:
- Assess the effectiveness of ML, DL, and LLMs in fraud detection.
- Demonstrate innovative techniques to enhance detection reliability.

---

## Methodologies and Techniques

### Datasets:
- **Source**: Financial filings from the U.S. Securities and Exchange Commission (SEC).
- **Composition**: Curated financial statements, annotated for fraudulent activity.
- **Goal**: Train and evaluate AI models for fraud detection.

### Models and Architectures:
1. **Voting Classifier Ensemble**:
   - Combines Logistic Regression, Decision Trees, K-Nearest Neighbors, and Naive Bayes.
   - Achieved the highest accuracy of **91.2%**.
2. **Seq2Seq Deep Learning**:
   - Captures sequential patterns in financial data.
   - Test accuracy: **83%**.
3. **FinBERT**:
   - Pre-trained on financial corpora for domain-specific understanding.
   - Test accuracy: **74%**.

---

## Key Findings

- **Ensemble Models**:
  - Excelled due to their ability to combine strengths and mitigate weaknesses of individual algorithms.
- **Seq2Seq**:
  - Promising for understanding sequential patterns in text but slightly weaker in edge cases.
- **FinBERT**:
  - Effective in capturing domain-specific nuances but needs refinement for fraud detection.

---

## Conclusion

- **Voting Classifier** is a robust and adaptable solution for fraud detection.
- Collaboration among diverse models enhances prediction reliability and generalization.
- The results highlight the importance of adopting ensemble techniques in complex domains.

---

## Repository Contents

- **Article**: Detailed findings and methodologies (`article.pdf`).
- **Code**: Implementations of ML, DL, and LLM models.
- **Data**: Pre-processed datasets and annotations for financial fraud detection.

