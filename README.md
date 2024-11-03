# Product Review Sentiment Analysis

## Overview

The **Product Review Sentiment Analysis** project is designed to analyze customer feedback on products using Natural Language Processing (NLP) and Machine Learning techniques. The tool provides insights into customer satisfaction by evaluating the sentiments expressed in product reviews. Users can upload their CSV files containing reviews, and the application will process the data, visualize sentiment distributions, and extract keywords, helping businesses make informed decisions based on customer feedback.

## Features

- Upload CSV files containing product reviews.
- Clean and preprocess text data for analysis.
- Perform sentiment analysis using TextBlob and advanced transformer-based models.
- Visualize sentiment distributions and review length.
- Extract keywords from reviews using RAKE.
- Generate interactive word clouds for visual representation of keywords.
- Train and evaluate machine learning models (Random Forest and SVM) for sentiment classification.
- Save processed results to a CSV file for further analysis.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Pandas
  - NLTK
  - TextBlob
  - Matplotlib
  - Seaborn
  - Plotly
  - WordCloud
  - Hugging Face Transformers
  - RAKE-NLTK
  - Scikit-learn

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

2. Open the project in Google Colab or set up a local environment with the necessary libraries.

3. Install the required libraries by running the following command in a Jupyter Notebook or Google Colab:
   
   ```!pip install pandas nltk textblob matplotlib seaborn plotly wordcloud transformers rake-nltk scikit-learn```

## Usage
Open the Google Colab notebook provided in this repository.
Run the cells in order to import libraries, upload your CSV file with product reviews, and execute the analysis.

After uploading the CSV file, the tool will:
- Clean and preprocess the reviews.
- Perform sentiment analysis.
- Visualize the results, including sentiment distribution and keywords.
- Train and evaluate machine learning models to classify sentiments.
- Download the results as a CSV file for your records.

## Sample Data
A sample dataset is included in this project to help you test the functionality of the tool. You can find the sample dataset in the data folder.

## Conclusion
The Product Review Sentiment Analysis project is a powerful tool for businesses seeking to understand customer sentiment and improve their products based on feedback. By leveraging advanced NLP techniques and machine learning models, this project demonstrates a comprehensive analysis pipeline suitable for real-world applications. It provides actionable insights into customer opinions, enabling businesses to enhance their offerings and better meet consumer expectations.
