# Sinophobia Sentiment Analysis during COVID-19

This repository contains the code and data used for sentiment analysis of Sinophobia on social media platforms during the COVID-19 pandemic. The project leverages large language models (LLMs) to analyze tweets and track the rise of Sinophobia.

## Repository Structure

The repository is organized into several directories and files, each containing code, data, and visualizations related to the sentiment analysis project:

### Directories:

- **BERT_model/**  
  This directory contains the Jupyter notebook used for the BERT model in sentiment classification. It includes:
  - `BERT.ipynb`: Jupyter notebook that handles training and fine-tuning the BERT model for sentiment analysis tasks.
 
- **Results/**  
  This folder contains CSV files with the results of the sentiment analysis for the selected six countries. Including original tweet, text after preprocessing, and sentiment labels.

- **Sample_OriginalDataset/**  
  This directory contains the sample dataset of the six countries, each contain the first 100 rows of the dataset.

- **Visualisation/**  
  This directory contains Jupyter notebooks dedicated to generating visualizations for the analysis, such as polarity scores and n-grams:
  - `Polarity score.ipynb`: Jupyter notebook for calculating and visualizing polarity scores over time.
  - `visualisation.ipynb`: Jupyter notebook containing additional visualizations, such as n-grams and trends by country.

- **Sentiment_labelling/**  
  This notebook contains code which preprocesses and filters the data for the sample dataset of Australia, and label the sentiments to each tweets.

## Dataset

Lande, Janhavi and Chandra, Rohitash, Global COVID-19 X (Twitter) Dataset (July 01, 2024). Available at SSRN: https://ssrn.com/abstract=4895603 or http://dx.doi.org/10.2139/ssrn.4895603

## Our related paper

Wang, C., & Chandra, R. (2024). A longitudinal sentiment analysis of Sinophobia during COVID-19 using large language models. arXiv preprint arXiv:2408.16942. https://arxiv.org/abs/2408.16942