# Amazon Sentiment Analysis

## Overview

This project is a sentiment analysis tool for analyzing customer reviews on Amazon. It utilizes Natural Language Processing (NLP) techniques to assess the sentiment and opinions expressed in the reviews. The analysis provides insights into customer satisfaction, product feedback, and sentiment trends across a wide range of Amazon products.

## Dataset

The dataset used in this project, named 'Reviews.csv,' has been previously read into the notebook. It originally contained over 500k+ rows of Amazon customer reviews, but for the purpose of this analysis, a subset of the data is being utilized. The dataset is structured with relevant columns such as 'Text' and 'Score,' providing the text of the reviews and the associated star ratings, along with other basic information.

## Project Components

- **Sentiment Analysis Models**: The project incorporates two sentiment analysis models: VADER (Valence Aware Dictionary and sEntiment Reasoner) and RoBERTa, a pre-trained transformer model. These models assess the sentiment of the reviews and provide detailed sentiment scores.

- **Analysis Scripts**: The project includes Python scripts for data preprocessing, sentiment analysis, and visualization. The scripts process the dataset, perform sentiment analysis using the selected models, and generate visualizations for insights.

- **Results and Visualizations**: The project generates visualizations to illustrate sentiment distribution, sentiment trends, and comparisons between the sentiment scores of VADER and RoBERTa.

## Usage

- Modify the analysis scripts to suit your specific analysis requirements.
- Explore the generated visualizations to gain insights into the sentiment of Amazon customer reviews.

## Acknowledgments
- This project was heavily influenced by Rob Mulla's work, particularly their Youtube tutorials on NLP or related topics. I dedicated time to study their work carefully and aimed to provide detailed explanations and descriptions in my Jupyter notebook, linked in this repository. While I based my implementation on their guidance, my priority was to learn and understand the concepts thoroughly while adding original insights where possible.
