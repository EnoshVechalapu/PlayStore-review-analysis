# Play Store Review Sentiment Analysis

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Implementation](#implementation)

## Introduction
This project focuses on analyzing Play Store reviews to classify the sentiments expressed in the reviews as positive or negative. Leveraging the power of the Transformers library by Hugging Face, we build a robust sentiment classifier to achieve high accuracy.

Check the **PlayStoreReviewAnalysis.ipynb** file

## Dataset
The dataset used for this project consists of Play Store reviews. The reviews are labeled with sentiments (positive , negative or neutral) which are used to train and evaluate the model.
The dataset is uploaded above as **review.csv**

## Model Architecture
We utilized a pre-trained Transformer model from Hugging Face's Transformers library. The architecture chosen for this task is:
- [BERT] 

## Implementation
### Dependencies
- Python
- Pytorch
- Transformers library by Hugging Face
- Pandas
- Scikit-learn

### Steps
1. **Data Preprocessing:** Tokenization and preparation of the dataset.
2. **Model Training:** Fine-tuning the pre-trained Transformer model on the training data.
3. **Model Evaluation:** Evaluating the model on the test dataset to measure performance.



