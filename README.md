# Content-Based Recommender System Project

## Introduction
A **Recommender System (RS)** is a system designed to recommend items to users based on their preferences. It is a type of information filtering system that predicts the "rating" or "preference" a user might give to an item. Recommender systems are widely used across various industries such as movies, music, news, books, e-commerce, and more. Notable examples include Amazon, Netflix, and YouTube.

---

## Project Overview
This project implements a **Content-Based Recommender System**. The system uses item descriptions and user profiles to recommend items to users. The algorithm assumes that if a user liked an item in the past, they are likely to enjoy a similar item in the future.

The core component of this system is the **similarity function**, which:
- Measures the similarity between items.
- Finds items that are most similar to those the user liked in the past.
- Recommends those items to the user.

---

## Dataset
The dataset used for this project is from the Amazon Reviews dataset, specifically the **Pet Supplies** category.

To access the dataset, visit:  
[Amazon Reviews Dataset - UCSD](https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews)

Due to its size, the dataset is not included in this repository. Please download the dataset and place it in the `data/` directory.

---

## Instructions

### Running the Notebook in Google Colab
1. Open the Colab notebook directly in your browser by clicking the link below:  
   [Run on Google Colab](https://colab.research.google.com/github/Manami-Hayashi/RecommendationSystemForAmazonPetSupply/blob/main/notebooks/recommender_system.ipynb)

2. Upload the dataset (`meta_Pet_Supplies.jsonl`) to the Colab environment:
   - Go to the Colab menu, click **File > Upload**, and upload the dataset.
   - Alternatively, use Google Drive to load the file by mounting the drive:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```

3. Follow the instructions in the notebook to process the dataset and build the recommendation system.

---
