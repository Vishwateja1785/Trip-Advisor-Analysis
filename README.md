# TripAdvisor Review Analysis

This project analyzes TripAdvisor hotel reviews to determine review sentiment and assess the similarity between reviews and responses.

## Objectives

1. Understand reviewer emotions and build a model to determine review criticality
2. Compare reviews and responses to evaluate if reviews were addressed appropriately

## Data

- Source: TripAdvisor.com
- Scope: 225 major global hotel chains, reviews from 2018-2021
- Size: 1,467,919 reviews, 123,194 with both reviews and responses used for modeling
- Features: Hotel name/chain, quality level, travel type, service quality, review text, response text, etc.

## Key Components

- Web scraping using Beautiful Soup
- Exploratory data analysis 
- Emotion detection using pre-trained T5 model
- Review criticality classification using BERT
- Semantic similarity analysis of reviews and responses

## Models

- BERT base uncased model for review criticality classification
- Pre-trained T5 model fine-tuned on emotion dataset
- BERT model for vectorizing reviews and responses


## Key Features

- Sentiment analysis of TripAdvisor reviews using a fine-tuned BERT model
- Calculation of semantic similarity between review-response pairs
- Data preprocessing and exploratory data analysis of TripAdvisor dataset
- Web scraping functionality to collect additional TripAdvisor data


## Results

- Achieved 0.51 accuracy and 0.59 F1-score on review criticality classification
- Identified trends in hotel response rates over time and by travel type
- Developed method to quantify semantic similarity between reviews and responses

## Future Work

- Collect more data to address class imbalance
- Experiment with other model architectures
- Develop a user interface for hotel managers to easily analyze reviews

## Technologies Used

- Python
- PyTorch
- Transformers library (Hugging Face)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Beautiful Soup
- Selenium
