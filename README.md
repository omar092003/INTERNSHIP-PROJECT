# Multi-Label Classification and Sentiment Analysis on Hospital Feedback Data

This project focuses on analyzing customer feedback data from a hospital using Natural Language Processing (NLP). It employs two state-of-the-art pre-trained models from Hugging Face: **RoBERTa** for sentiment analysis and **BART** for multi-label classification.

## Project Overview

The goal is to process and classify textual feedback to:
1. Determine the sentiment (positive, negative, neutral) using **RoBERTa**.
2. Categorize feedback into multiple relevant labels (e.g., "Service Quality," "Staff Behavior," "Cleanliness") using **BART**.

By leveraging these models, the project aims to provide actionable insights to improve hospital services.

---

## Features

- **Sentiment Analysis**: Classifies feedback into sentiments like positive, negative, or neutral.
- **Multi-Label Classification**: Identifies multiple categories or themes within a single feedback instance.
- **Pre-Trained Models**: Uses **RoBERTa** and **BART** from Hugging Face for high accuracy.
- **Scalable Pipeline**: Easily adaptable to new data and categories.

---

## Technologies Used

- **Python**
- **Hugging Face Transformers**
  - [RoBERTa](https://huggingface.co/transformers/model_doc/roberta.html) for sentiment analysis.
  - [BART](https://huggingface.co/transformers/model_doc/bart.html) for multi-label classification.
- **Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: Evaluation metrics for classification tasks.
- **Jupyter Notebook**: Experimentation and visualization.

---

## Dataset

The dataset consists of anonymized hospital feedback containing:
- **Text**: The actual feedback given by patients or visitors.
- **Labels**: Multiple tags indicating the categories relevant to the feedback.
- **Sentiment**: Manually labeled or inferred sentiment of the feedback.

> Note: Due to confidentiality, the dataset is not included in this repository.

