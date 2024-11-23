# Sentiment Analysis of Rotten Tomatoes Movie Reviews  

## Description  
This project focuses on building a sentiment analysis model for movie reviews on Rotten Tomatoes using traditional machine learning techniques and natural language processing (NLP). It explores the relationship between review content and sentiment polarity, providing valuable insights for the film industry.  

## Key Aspects  
- **Dataset:**  
  Over 1.1 million reviews from Rotten Tomatoes, spanning from 1800 to 2020, representing diverse genres and audiences.  

- **Preprocessing:**  
  Comprehensive text cleaning, tokenization, stopword removal, n-grams, and feature extraction to prepare raw text for analysis.  

- **Techniques Used:**  
  Implemented Bag of Words (BoW) and TF-IDF for feature engineering, alongside machine learning models including:  
  - Logistic Regression  
  - Naive Bayes  
  - Support Vector Machine (SVM)  

- **Model Performance:**  
  The best-performing model, SVM with TF-IDF vectorization, achieved an accuracy of 79%, highlighting its robustness for sentiment classification.  

- **Feature Analysis:**  
  Analyzed linguistic patterns and key sentiment indicators like positive phrases (`"masterpiece"`) and negative expressions (`"disappointing"`).  

- **Error Analysis:**  
  Identified challenges such as sarcasm and nuanced language, proposing future work with advanced deep learning models like BERT and attention mechanisms.  

- **Future Directions:**  
  Plans to incorporate:  
  - Temporal sentiment trends  
  - Aspect-based sentiment analysis  
  - Pre-trained NLP models (e.g., BERT, RoBERTa)  

## Key Takeaways  
This project provides a comprehensive framework for sentiment analysis, combining machine learning and NLP techniques to derive meaningful insights from textual data. It serves as a foundation for further research and applications in:  
- Media analytics  
- Audience engagement  
- Product feedback analysis  

## Technologies Used  
- **Programming Languages:** Python  
- **Libraries and Tools:** scikit-learn, pandas, NumPy, TF-IDF, Bag of Words  

## Getting Started  
1. Clone this repository:  
   ```bash  
   git clone <repository-url>  
2. Install the required R packages:
   ```bash
   install.packages(c("tidyverse", "tidyquant", "caret", "e1071", "rpart", "rpart.plot", "ggplot2"))
## How to Run
- Open the Investment_Analysis.R file in RStudio.
- Set the working directory and ensure the dataset is accessible.
- Run the script to replicate the analysis and generate outputs.
