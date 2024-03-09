# Explainable Sexual Harassment Categorization

## Overview
This project introduces a model designed to categorize various forms of sexual harassment reported on online forums, enhancing the reporting and processing efficiency. Using the SafeCity dataset, the model leverages Word2Vec for vectorization and Multiclass Logistic Regression for classification, alongside Explainable AI (XAI) techniques such as SHAP or LIME for decision transparency. This tool aims to accelerate the response from authorities and organizations, contributing to a safer community.

## Installation

### Prerequisites
- Python 3.8+
- pip

### Libraries
- NumPy
- Pandas
- scikit-learn
- gensim (for Word2Vec)
- SHAP/LIME for model explanation

### Setup
Clone the repository and install the required Python packages:
bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt


## Methodology
The model development includes the following steps:
1. *Data Preprocessing*: Clean and prepare the SafeCity dataset.
2. *Feature Engineering*: Use Word2Vec to convert textual reports into meaningful vectors.
3. *Model Training*: Train a Multiclass Logistic Regression model using the vectorized data.
4. *Model Explanation*: Apply SHAP/LIME to provide insights into the factors influencing the categorization decisions.

## Evaluation
The model is evaluated on:
- *Hamming Score*: For the multi-classification model accuracy.
- *XAI Metrics*: Assessing the Explainable AI components through Identity, Separability, Similarity, and Stability.


   
![avg_impact](https://github.com/YashBodke005/TRINIT_JapaniJamesbond_ML02/assets/98110257/9c4bb2fb-adfa-436f-991a-8c0bc1591604)
![feature_count](https://github.com/YashBodke005/TRINIT_JapaniJamesbond_ML02/assets/98110257/80e8793d-46d6-4743-97e7-1fb845d6b621)
![Freq_words](https://github.com/YashBodke005/TRINIT_JapaniJamesbond_ML02/assets/98110257/a6623c0a-f0f2-480c-877c-bad0974f279e)
![feature_exp](https://github.com/YashBodke005/TRINIT_JapaniJamesbond_ML02/assets/98110257/c242cbbf-01fc-4ab0-8547-674ee840f78b)

