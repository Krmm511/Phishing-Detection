# Phishing Detection Using Machine Learning Techniques - Reproduction and Critical Evaluation

## Project Description

This project reproduces and critically evaluates the paper **"Phishing Detection Using Machine Learning Techniques."** The objective is to evaluate the effectiveness of several machine learning algorithms for detecting phishing websites using engineered URL, domain, and webpage features.

The project includes data exploration, preprocessing, feature engineering, model training, evaluation, and a critical discussion of the original paper and its methodology.

---

## Selected Paper

**Phishing Detection Using Machine Learning Techniques**
paper link:- [https://arxiv.org/pdf/2009.11116 ](https://arxiv.org/pdf/2009.11116) 

---

## Original GitHub Repository

[https://github.com/fafal-abnir/phishing_detection](https://github.com/fafal-abnir/phishing_detection)

---

## Dataset Source

The dataset is provided by the authors through the original GitHub repository.

It contains:

- 11,055 website samples
- 30 engineered phishing-related features
- 1 target label (`Result`)

Each sample is classified as either phishing or legitimate.

---

## Repository Structure

```
.
├── dataset.csv
├── phishing_detection_reproductionV2F.ipynb
├── ProjectReportV2.pdf
├── README.md
├── requirements.txt
```

---

## Models Used

The following machine learning models were implemented:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Matthews Correlation Coefficient (MCC)
- ROC-AUC
- Confusion Matrix

---

## Requirements

Python 3.10+

Install the required packages:

```bash
pip install -r xgboost 
```

Main libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

---

## Execution Instructions

1. Clone this repository.

```bash
git clone <repository_link>
```

2. Install the required packages.

```bash
pip install -r xgboost
```

3. Open:
```
phishing_detection_reproduction.ipynb
```

## Results

Four machine learning models were trained and compared on the phishing detection dataset.

The experiments showed that Random Forest achieved the best overall performance, while XGBoost produced very similar results. These findings are consistent with the conclusions presented in the original paper.


## Author

Karam Mahamed - 213029143
