# KDDCup99_AttackClassifier

This repository contains a machine learning model to classify network traffic data from the [KDD Cup 1999](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html) dataset. The goal of the project is to detect various types of network attacks, including denial of service (DoS), remote-to-local (R2L), and user-to-root (U2R) attacks. By analyzing the traffic patterns, this model can be used to improve network security systems and prevent attacks in real-time.

## Project Overview

The primary goal of this project is to develop a classification model that can identify different types of network attacks based on network traffic data. The dataset contains over 4 million network traffic instances, and the classifier needs to differentiate between normal traffic and various attacks.

## Machine Learning Models
This project includes the following machine learning models for classification:
- **Logistic Regression:** A binary classification model to differentiate between normal and attack traffic.
- **Support Vector Machine (SVM):** Used to classify Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks specifically.
- Other models (if applicable) can be included here.

### Types of Attacks Classified:
- **Probes**
- **DoS (Denial of Service)**
- **R2L (Remote to Local)**
- **U2R (User to Root)**

## Dataset

The KDD Cup 1999 dataset consists of network traffic data, where each record represents a connection and is labeled as either normal or belonging to a specific attack category. The dataset includes features like:

- Duration of connection
- Protocol type
- Service type
- Source and destination IP addresses
- Number of bytes sent
- Flags (e.g., connections established, etc.)

## Installation

To get started with this project, clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/KDDCup99_AttackClassifier.git
cd KDDCup99_AttackClassifier
```
