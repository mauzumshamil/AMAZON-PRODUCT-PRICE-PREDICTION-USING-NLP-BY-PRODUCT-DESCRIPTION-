# AMAZON-PRODUCT-PRICE-PREDICTION-USING-NLP-BY-PRODUCT-DESCRIPTION-
Our project, "Text-to-Price: Leveraging NLP for Predicting Amazon Product Prices," aims to revolutionize the way we predict product prices on Amazon. With a dataset comprising over 500,000 product descriptions, we employ cutting-edge Natural Language Processing (NLP) techniques to convert text data into numerical vectors. 
# Text-to-Price: Leveraging NLP for Predicting Amazon Product Prices

## Overview

This repository contains the code for our project aimed at predicting Amazon product prices using Natural Language Processing (NLP) techniques. With a dataset comprising over 500,000 product descriptions, we leverage NLP to vectorize the text data and train machine learning algorithms to predict product prices solely based on their descriptions.

## Dataset

The dataset used in this project consists of more than 500,000 rows of product descriptions extracted from Amazon. Each row contains a product description along with its corresponding price.

## Methodology

### Data Preprocessing

- Text Cleaning: We perform basic text cleaning techniques such as removing punctuation, lowercasing, and tokenization to prepare the text data for vectorization.
- Text Vectorization: Using NLP techniques, we convert the textual data into numerical vectors to enable machine learning model training.

### Model Training

- XGBoost: We employ the XGBoost algorithm, known for its effectiveness in handling large datasets and producing accurate predictions.
- Linear Regression: Additionally, we utilize linear regression as a baseline model for comparison.

### Evaluation

We evaluate the performance of our models using standard regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R^2).

## Usage

To replicate our results, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the `preprocess.py` script to preprocess the dataset and prepare it for training.
4. Execute the `train_model.py` script to train the machine learning models.
5. Evaluate the trained models using the `evaluate_model.py` script.

## Results

Our experiments demonstrate that our approach achieves high accuracy in predicting product prices solely based on their descriptions. The XGBoost model outperforms linear regression, showcasing the effectiveness of advanced machine learning algorithms in handling large-scale textual data.

## Future Work

- Incorporate additional features such as product category or brand information to enhance predictive performance.
- Explore more advanced NLP techniques such as word embeddings or deep learning architectures for text vectorization.
- Deploy the trained models into production for real-time price prediction on Amazon's platform.
