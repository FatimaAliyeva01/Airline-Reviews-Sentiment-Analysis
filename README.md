
# ✈️ Airline Reviews Sentiment Analysis

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![NLTK](https://img.shields.io/badge/NLTK-3.6-green.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.5.2-green.svg)

## 📝 Table of Contents
- [📚 Overview](#-overview)
- [🔍 Project Details](#-project-details)
  - [Objective](#objective)
  - [Data Source](#data-source)
  - [Methodology](#methodology)
- [✨ Key Features](#-key-features)
- [⚙️ Requirements](#️-requirements)
- [🚀 Getting Started](#-getting-started)
- [📈 Results and Insights](#-results-and-insights)
- [📄 License](#-license)
- [📧 Contact](#-contact)

## 📚 Overview

The **Airline Reviews Sentiment Analysis** project is a natural language processing (NLP) tool designed to analyze customer sentiment from airline reviews. This project uses machine learning to classify reviews as positive, negative, or neutral, helping airlines and analysts understand customer satisfaction and identify areas for improvement.

## 🔍 Project Details

### Objective
To build a sentiment analysis model that classifies airline customer reviews and extracts insights into customer satisfaction.

### Data Source
- **Website**: [Skytrax](https://www.airlinequality.com/)
- **Data**: Customer reviews with sentiments reflecting experiences with various airlines

### Methodology
1. **Data Collection**: Scrape customer reviews from the Skytrax website using BeautifulSoup.
2. **Data Preprocessing**:
   - Cleaning text data by removing HTML tags, special characters, and unnecessary spaces.
   - Tokenizing and stemming words for effective analysis.
3. **Feature Extraction**:
   - Applying TF-IDF vectorization to convert text into numerical features.
4. **Model Training**:
   - Training a sentiment analysis model using techniques like Naive Bayes, Logistic Regression, and Support Vector Machine (SVM).
5. **Evaluation**:
   - Assessing model performance with accuracy, precision, recall, and F1-score metrics.

## ✨ Key Features
- **Comprehensive Sentiment Analysis**: Distinguishes positive, neutral, and negative sentiments from airline reviews.
- **Scalable Design**: Easily adaptable to other review data sources or different NLP tasks.
- **Valuable Insights**: Provides insights into common complaints and positive feedback trends for airlines.

## ⚙️ Requirements
- **Python**: Version 3.8 or higher
- **Libraries**:
  - `requests`
  - `BeautifulSoup4`
  - `pandas`
  - `nltk`
  - `scikit-learn`

_All dependencies are listed in `requirements.txt`._

## 📈 Results and Insights

This project provides a clear analysis of airline review sentiments, identifying key patterns in customer satisfaction and dissatisfaction. It offers valuable insights into areas like customer service, comfort, and value for money.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 📧 Contact

For questions or feedback, feel free to reach out:

- **Email**: [fatimaliyva@gmail.com](mailto:fatimaliyva@gmail.com)
- **LinkedIn**: [Fatima Aliyeva](https://www.linkedin.com/in/fatima-aliyeva-/)
- **GitHub**: [FatimaAliyeva01](https://github.com/FatimaAliyeva01)

---
