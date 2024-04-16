# Real and Fake News Classification

## Overview
This Python Colab Notebook is designed to distinguish between genuine and false information in dynamic news sourced from web and social media platforms. The model is trained on a pre-labeled dataset, where each news item is classified as either real or fake. Natural Language processing is applied to preprocess the dataset, focusing on extracting relevant keywords. To enhance adaptability, the model integrates Online Learning, allowing it to dynamically retrieve news for real-time classification. The project outputs include the binary classification of dynamic news and the corresponding prediction accuracy.

## Features
- *Input Data*: A dataset is in csv file format is used to train the model which has news headlines and it's classification (Real or Fake)
- *Preprocessing*: Performs data preprocessing steps such as cleaning and  tokenization. Stemming, which is the process of reducing words to their root or base form, stripping away prefixes, suffixes, and inflections, is also performed.
- *Machine Learning Models*: Implements machine learning models including logistic regression and Passive Agressive Classifier, which is an online learning algorithm for binary classification, is also implemented as it's useful in scenarios, such as this, where continuous learning occurs.
- *Evaluation Metrics*: Evaluates the performance of each model using metrics such as accuracy and confusion matrixes.


## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage
The collab script already has the required code and output. However, the individual code blocks can be run for better and further understanding if necessary.
The Training.csv dataset has to be downloaded before running the program

## Demo video
There's a demonstration video with voice-over that explains the working of the code
