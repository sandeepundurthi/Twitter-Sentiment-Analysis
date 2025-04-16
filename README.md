# Twitter Sentiment Analysis

This project focuses on sentiment classification of tweets at the **entity level**, identifying whether users express **Positive**, **Negative**, or **Neutral** sentiment toward specific companies, products, or organizations. It showcases the use of classic machine learning models alongside a custom **Artificial Neural Network (ANN)** that achieved top performance.

## Project Overview

- **Goal**: Analyze tweet sentiment toward entities (e.g., Apple, Google).
- **Tech Stack**: Python, Scikit-learn, Keras, Pandas, NumPy, Matplotlib, Seaborn
- **Input Data**: `twitter_training.csv` and `twitter_validation.csv`
- **Output**: Predicted sentiment class for each tweet

---

## Key Achievements

- **Entity-Level Sentiment Classification**  
  Analyzed sentiment targeted at specific entities (e.g., Microsoft, Tesla).

- **Data Preprocessing & Feature Engineering**  
  - Cleaned and tokenized tweet text  
  - Removed mentions, URLs, special characters  
  - Handled missing values  
  - Standardized sentiment labels  
  - Applied **TF-IDF vectorization** for numerical representation of text  

- **Model Development & Comparison**
  - Implemented and evaluated five different models:
    | Model                  | Accuracy     |
    |-----------------------|--------------|
    | Naive Bayes           | 71.37%       |
    | Logistic Regression   | 81.88%       |
    | Decision Tree         | 88.69%       |
    | Random Forest         | 93.89%       |
    | Artificial Neural Network (ANN) | **96.89%** ✅ |

- **Deep Learning**  
  Demonstrated the effectiveness of ANN in handling complex sentiment patterns in tweet text.


