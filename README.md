# British Airways Data Science Job Simulation
![BALogo](https://logos-world.net/wp-content/uploads/2021/02/British-Airways-Logo.png)


## Objective
The primary goal of this project is to extract, clean, analyze customer reviews and build a predictive model. This involves:

- Web Scraping: Extracting review data from multiple pages of the Skytrax website using BeautifulSoup.
- Data Cleaning: Removing irrelevant text (e.g., "✅ Trip Verified") and preparing the data for analysis.
- Exploratory Data Analysis (EDA): Visualizing and summarizing the key insights from the data.
- Machine Learning: Building and evaluating predictive models to understand factors that influence buying behaviour.

## Project Structure

- `BA_Task1.ipynb`: Notebook containing the complete code for web scraping, data cleaning and Sentiment Analysis using TextBlob.
- `BA_Task2.ipynb`: Notebook containing the complete code for EDA and machine learning tasks.
- `BA_reviews.csv`: The CSV file containing the review data uncleaned for task1.
- `cleaned_BA_reviews.csv`: The CSV file containing the review data cleaned for task1.
- `customer_booking.csv`: The CSV file containing the customer booking data for task2.
- `README.md`: This file, providing an overview of the project and instructions for replicating the analysis.

## Random Forest Model Result
![Alt text](https://github.com/GhaydaMal/British_Airways_DataScience_Job_Simulation/blob/main/RandomForest_Result.png)

## XGBoost Model Result
![Alt text](https://github.com/GhaydaMal/British_Airways_DataScience_Job_Simulation/blob/main/XGBoost_result.png)
