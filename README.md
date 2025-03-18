# KDDCup99_AttackClassifier

This repository contains a machine learning model to classify network traffic data from the [KDD Cup 1999](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html) dataset. The goal of the project is to detect various types of network attacks, including denial of service (DoS), remote-to-local (R2L), and user-to-root (U2R) attacks. By analyzing the traffic patterns, this model can be used to improve network security systems and prevent attacks in real-time.

## Project Overview

The primary goal of this project is to develop a classification model that can identify different types of network attacks based on network traffic data. The dataset contains over 4 million network traffic instances, and the classifier needs to differentiate between normal traffic and various attacks.

## Machine Learning Models
This project includes the following machine learning models for classification:
- **Logistic Regression:** A binary classification model to differentiate between normal and attack traffic.
- **Support Vector Machine (SVM):** Used to classify Denial of Service (DoS) and Non-DoS attacks specifically.
- Other models (if applicable) can be included here.

### Types of Attacks Classified:
- **Probes**
- **DoS (Denial of Service)**
- **R2L (Remote to Local)**
- **U2R (User to Root)**

## Results
The models were evaluated using accuracy and other performance metrics. The following results were obtained:
- **Logistic Regression:** Accuracy: 85%, Precision: 83%, Recall: 80%
- **SVM (DoS vs Non-DoS):** Accuracy: 90%, Precision: 88%, Recall: 92%
These results demonstrate the effectiveness of the models in classifying network traffic.

## Folder Structure
- `Logistic Regression KDDCUP99.ipynb`: Jupyter Notebook implementing logistic regression for classification.
- `Support Vector Model (DoS vs Non-DoS).ipynb`: Jupyter Notebook implementing SVM for DoS vs Non-DoS classification.
- `data/`: Folder containing the KDD Cup 1999 dataset (or a link to download it).
- `models/`: Folder where saved models are stored (if applicable).
- `README.md`: This file.

## Installation



To get started with this project, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/KDDCup99_AttackClassifier.git
cd KDDCup99_AttackClassifier
```
## Dependencies
This project requires the following Python libraries:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn
- jupyter

Install these dependencies using pip.

## Acknowledgements
- The KDD Cup 1999 dataset was provided by the Knowledge Discovery and Data Mining Cup.
