# Hotel-Discount-Prediction

# Hotel Discount Prediction Using Web Scraping & Machine Learning
This project focuses on analyzing hotel ratings and predicting discount percentages using machine learning. Data is collected from Trivago via Selenium-based web scraping, and predictive models are built to estimate discounts based on location, price, property type, and user ratings.

## 📌 Project Overview
##### Topic: Analyzing Hotel Ratings & Predicting Discounts
##### Goal: Predict the discount percentage offered on hotel listings using machine learning.
##### Tools Used:
1. Web Scraping: Selenium (Trivago)
2. Machine Learning: Scikit-learn

#### Notebook 1: Trivago_Web_Scraping.ipynb – Scrapes hotel listing data
#### Notebook 2: Builds regression models
#### Report: Detailed explanation of the full pipeline

### 📂 Files Included
Trivago_Web_Scraping.ipynb	Python notebook using Selenium to scrape hotel data from Trivago
Hotel Rating Prediction.ipynb	ML model development and evaluation
Hotel Rating Documentation	Complete report detailing methodology, results, and findings

### 🧾 Features Extracted
1. Location: City or region
2. Price: Original price listed
3. Lowest Price: Lowest available price
4. Rating: User-assigned score
5. Property Type: Hotel, Resort, etc.
6. Discount % (Target Variable): Calculated as derived field

### Workflow
Data Collection
1. Performed using Selenium automation on Trivago’s website.
2. Extracted details like hotel name, location, price, rating, etc.

Data Preprocessing
1. Missing values handled
2. Label encoding for categorical features

Feature scaling and normalization
Model Development
1. Multiple models were tried: Linear Regression, KNN, SVM, Random Forest, etc.
2. Final Model: Gradient Boosting Regressor chosen based on performance

Evaluation Metrics
1. MAE (Mean Absolute Error)
2. RMSE (Root Mean Squared Error)
3. Scatter plots used for visual inspection of predictions

### 📈 Key Results
1. The Gradient Boosting Regressor achieved strong prediction accuracy.
2. Important Features: Price, Rating, and Location had the greatest influence on discounts.

### Use Cases:
1. Travelers: Identify cost-effective hotels
2. Hotel Managers: Optimize pricing strategy

### ⚙️ Technologies Used
Python 3.x
Jupyter Notebook
Selenium
Pandas, NumPy, Scikit-learn
Matplotlib / Seaborn (for visualizations)


