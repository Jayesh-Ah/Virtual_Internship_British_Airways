# ✈️ Virtual Internship - British Airways
Airline Review Analysis and Customer Booking Prediction

## 🛠 Project Overview
This project involves analyzing airline reviews and predicting customer booking behaviors through a full data science pipeline. It includes web scraping, data cleaning, sentiment analysis, and predictive modeling to derive actionable insights for business decision-making. The aim is to understand how customer sentiment influences booking patterns, helping British Airways optimize their customer service and marketing strategies.

## 📂 Repository Contents
prediction_model.ipynb: Jupyter Notebook containing code for developing and evaluating the customer booking prediction model.
web_scraping.ipynb: Jupyter Notebook for scraping and preprocessing airline review data using BeautifulSoup.
Customer_Bookings.pdf: Detailed report on the development, evaluation, and performance of the booking prediction model.
Data_Scraping.pdf: Comprehensive documentation on data scraping and preprocessing methodologies.
data/: Folder containing raw and cleaned datasets used for model training and evaluation.
[customer_bookings.csv](./customer_bookings.csv): Cleaned dataset used for training and testing the model.
## 🔑 Key Components
1. Web Scraping
Employed BeautifulSoup to scrape over 1,000 airline reviews from a major review platform.
Cleaned and preprocessed the data to prepare it for sentiment classification and prediction tasks.
2. Sentiment Analysis
Applied a Naive Bayes classifier to perform sentiment analysis on the airline reviews, achieving an accuracy of 85% in classifying customer sentiments as positive, negative, or neutral.
3. Prediction Model
Developed advanced machine learning models like Random Forest and XGBoost for initial forecasting tasks.
Built a highly efficient LightGBM model to predict customer bookings with 90% accuracy.
Utilized SHAP (SHapley Additive exPlanations) to interpret model outputs, identifying key factors influencing booking decisions, such as sentiment polarity, flight duration, and service quality ratings.
4. Insights and Presentation
Generated insightful visualizations and compiled performance metrics in PDF reports.
Presented strategic insights to inform future business decisions regarding customer retention, service improvement, and marketing strategies.
## 📦 Requirements
Python 3.7+
Jupyter Notebook
BeautifulSoup4
scikit-learn
LightGBM
SHAP
## 📈 Conclusion
This project demonstrates a comprehensive workflow, from data collection to predictive modeling and business insights. Users can replicate or extend the analysis by following the provided Notebooks and reports. The tools and methodologies applied here are applicable to a wide range of industries facing similar challenges in customer behavior prediction.
