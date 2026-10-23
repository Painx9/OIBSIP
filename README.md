# Oasis Infobyte Internship (OIBSIP) - Data Analytics 📊

Welcome to my portfolio repository for the Oasis Infobyte Summer Internship Program (OIBSIP). This repository contains all my completed task submissions for the **Data Analytics** track.

## 🎯 Objective

To apply data analytics, machine learning, and data visualization techniques to real-world datasets, extracting actionable business insights and solving analytical problems.

## 🎥 Video Presentation

_(Add the link to your video presentation here once uploaded!)_

- **Watch the full project breakdown and demonstration:** [Insert YouTube/LinkedIn Link Here]

## 📂 Repository Structure

This repository strictly follows the OIBSIP folder naming convention: `[TrackName]-[Level/Task]-[ProjectName]/`.

### Completed Tasks

#### Level 1

- **[Task 1: Exploratory Data Analysis (EDA) on Retail Sales](DataAnalytics-L1-EDARetailSales/)**
  - **Description:** Performed data cleaning, time series analysis, demographic breakdowns, and correlation analysis on a retail dataset to identify sales trends and product performance.
  - **Tech Stack:** Python, Pandas, Matplotlib, Seaborn

- **[Task 2: Customer Segmentation Analysis](DataAnalytics-L1-CustomerSegmentation/)**
  - **Description:** Applied RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment an e-commerce customer base into distinct behavioral profiles (e.g., VIPs, Loyalists, At-Risk).
  - **Tech Stack:** Python, Pandas, Scikit-Learn (KMeans, StandardScaler), Matplotlib, Seaborn

- **[Task 3: Data Cleaning](DataAnalytics-L1-DataCleaning/)**
  - **Description:** Handled missing values, standardized categorical labels, performed mathematical data imputation, and converted incorrect string formats into proper numeric and datetime types using Pandas.

- **[Task 4: Sentiment Analysis](DataAnalytics-L1-SentimentAnalysis/)**
  - **Description:** Applied NLP techniques to classify the sentiment of social media text. Utilized NLTK's VADER SentimentIntensityAnalyzer to generate compound polarity scores, achieving a 63% baseline accuracy, and visualized model bias against ground-truth labels using Seaborn.

#### Level 2

- **[Task 1: Predicting House Prices with Linear Regression](DataAnalytics-L2-HousePrices/)**
  - **Description:** Developed a predictive model for house prices using the Ames Housing dataset. Performed extensive EDA, handled missing values, and applied One-Hot Encoding. Discovered extreme coefficient inflation in standard Linear Regression due to sparse categorical features, which was successfully corrected by implementing a Ridge Regression model (achieving an R² score of ~0.88).

- **[Task 2: Wine Quality Prediction](DataAnalytics-L2-WineQuality/)**
  - **Description:** Built a machine learning pipeline to classify red wine quality based on physicochemical properties. Addressed class imbalance through feature binning and stratification, evaluated Random Forest, SGD, and SVC models (achieving ~94% accuracy with RF), and visualized chemical feature importances.

- **[Task 3: Credit Card Fraud Detection](DataAnalytics-L2-FraudDetection/)**
  - **Description:** Analyzed severe class imbalance in transaction data and applied SMOTE to generate synthetic fraud cases. Trained Logistic Regression and Random Forest models, achieving a 0.89 Recall to effectively minimize false negatives.
  - **Tech Stack:** Python, Pandas, Scikit-Learn (SMOTE, RandomForestClassifier), Matplotlib, Seaborn

- **[Task 4: Google Play Store Analysis](DataAnalytics-L2-GooglePlayStore/)**
  - **Description:** Conducted Exploratory Data Analysis (EDA) on the Android app market to identify category saturation and download trends. Cleaned malformed string data and visualized rating distributions and monetization impacts using Matplotlib and Seaborn.

- **[Task 5: Autocomplete and Autocorrect](DataAnalytics-L2-AutocompleteAutocorrect/)**
  - **Description:** Built a predictive bigram autocomplete model and a Levenshtein edit-distance autocorrect engine using NLTK and pyspellchecker. Processed a Gutenberg corpus and visualized Top-20 token frequencies and autocorrect confusion matrices.

✅ _All internship tasks successfully completed!_

## 🛠️ Tech Stack & Tools

- **Programming Language:** Python 3.x
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-Learn
- **Natural Language Processing:** NLTK, pyspellchecker
- **Environment:** Jupyter Notebook / VS Code
- **Version Control:** Git & GitHub

## 📜 License

This repository is created solely for the educational and evaluation purposes of the Oasis Infobyte internship program.
