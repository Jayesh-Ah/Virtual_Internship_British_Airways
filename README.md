# Virtual_Internship_British_Airways
## Airline Review Analysis and Customer Booking Prediction
### Project Overview
This project focuses on scraping airline reviews and performing sentiment analysis to predict customer bookings. The workflow includes web scraping, data cleaning, sentiment classification, model development, and presenting insights to drive business decisions.

### Repository Contents
- prediction_model.ipynb: Jupyter Notebook containing the code for developing and evaluating the prediction model.
- web_scraping.ipynb: Jupyter Notebook containing the code for scraping and preprocessing airline review data.
- Customer_Bookings.pdf: Detailed report on the customer booking prediction model.
- Data_Scraping.pdf: Detailed report on the data scraping and preprocessing steps.
- data/: Folder containing raw and processed datasets.
- customer_bookings.csv: Cleaned dataset used for model training and evaluation.
### Key Components
#### Web Scraping
- Utilized BeautifulSoup to scrape and collect over 1,000 airline reviews.
- Processed and cleaned the data for sentiment analysis.
#### Sentiment Analysis
Applied Naive Bayes classifier to analyze review sentiments, achieving an accuracy of 85%.
#### Prediction Model
- Engineered advanced algorithms like Random Forest and XGBoost for bike rental forecasting.
- Developed a robust LightGBM model to predict customer bookings with 90% accuracy.
- Employed SHAP for comprehensive model interpretability, identifying key variables influencing booking decisions.
#### Insights and Presentation
Compiled findings, visualizations, and performance metrics in comprehensive PDF reports.
Presented insights to inform strategic business decisions and future planning.
### How to Use
Clone this repository:
bash
Copy code
git clone https://github.com/yourusername/airline-review-analysis.git
Navigate to the project directory:
bash
Copy code
cd airline-review-analysis
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebooks:
bash
Copy code
jupyter notebook
Open and run web_scraping.ipynb to perform web scraping and data preprocessing.
Open and run prediction_model.ipynb to develop and evaluate the prediction model.
#### Requirements
- Python 3.7+
- Jupyter Notebook
- BeautifulSoup4
- scikit-learn
- LightGBM
- SHAP
#### Conclusion
This project demonstrates a complete workflow from data collection to model development and insight generation. By following the provided Notebooks and reports, users can replicate and extend the analysis for similar use cases.
