# Salary Range Prediction

This project focuses on predicting the salary ranges for job postings in New York City using various machine learning algorithms. The analysis involves data preprocessing, exploratory data analysis, and model training and evaluation.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
  - [Data Preprocessing](#data-preprocessing)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Feature Engineering](#feature-engineering)
  - [Model Training and Evaluation](#model-training-and-evaluation)
  - [Cross-Validation](#cross-validation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we aim to build a predictive model to estimate the salary ranges (`Salary Range From` and `Salary Range To`) for different job postings. We utilize various machine learning techniques to achieve accurate predictions and provide actionable insights.

## Dataset

The dataset used in this project is `Jobs_NYC_Postings.csv`, which contains job postings data in New York City. The dataset includes various features such as job title, agency, salary range, and job requirements.

## Installation

To run this project, you need to install the following dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost imbalanced-learn
