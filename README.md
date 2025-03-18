# KDDCup99_AttackClassifier

This repository contains a machine learning model to classify network traffic data from the [KDD Cup 1999](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html) dataset. The model aims to detect different types of network attacks, such as probes, denial of service, and remote-to-local attacks, by training a classifier using various machine learning techniques.

## Project Overview

The primary goal of this project is to develop a classification model that can identify different types of network attacks based on network traffic data. The dataset contains over 4 million network traffic instances, and the classifier needs to differentiate between normal traffic and various attacks.

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
