# DP-final-project

# Can Words Reveal Mental Health? A Machine Learning Approach

This project aims to explore whether machine learning models can accurately predict an individual's mental health status based on the content of their written statements. By analyzing text data utilizing Natural Language Processing (NLP) and a range of machine learning (ML) techniques, I aim to detect mental health conditions such as depression, anxiety, or bi-polar disorder and others, given a text input. 

## Research Question
Can text-based features from an individual's written statements be used to accurately predict their mental health status using machine learning techniques?

## Dataset
The data used in this project was created by Suchintika Sarkar and obtained from Kaggle[https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health/data]. It compiles text data from publicly available datasets and sources, including social media posts, Reddit posts, Twitter posts etc. The dataset consists of 54,043 statements, each labeled with one of the following mental health statuses: `depression`, `anxiety`, `normal`, `stress`, `suicidal`, `bipolar`, `personality disorder`.

## Methods
The project follows a structured pipeline with the following key phases.
- Data Preprocessing: This step involves cleaning the text, removing NAs and duplicates, tokenization, lemmatization and transforming the text into numerical representations using TF-IDF.
- Exploratory Data Analysis (EDA): EDA is used to gain sinsights into the distribution of mental health categories, the frequency of specific words, as well as relationships between features and mental health statuses.
- Model Building and Evaluation: Multiple classification algorithms are trained and evaluated, including: Logistic Regression, Naive Bayes, Support Vector Machine (SVM), XGBoost, a feedforward neural network.Model performance will be assessed using accuracy, F1 scores, and confusion matrices to understand how well each model captures the nuances of mental health categories.

## Files
- `can_words_reveal_mental_health.ipynb` – main notebook with all analysis
- `process_book.md` – log of what I learned and when
- `project_description.md` – research question, setup, and reflection
- `combined_data.csv` - data file

## How to run?
1. Download the dataset `combined_data.csv`[https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health/data].
2. Download the noteboook `can_words_reveal_mental_health.ipynb`.
3. Make sure that the dataset and notebook are in the same working directory.
4. Run:)

