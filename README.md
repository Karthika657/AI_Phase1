## Project Title : AI-Driven Exploration and Prediction of Company Registration Trends with the Registrar of Companies (ROC)

The project "AI-Driven Exploration and Prediction of Company Registration Trends with the Registrar of Companies (ROC)" appears to involve using artificial intelligence (AI) to analyze and predict patterns and trends related to company registrations with the Registrar of Companies (ROC). It uses Python libraries like Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn to perform data processing, exploration, and machine learning.

Dataset link : : https://tn.data.gov.in/resource/company-master-data-tamilnadu-upto-28th-february-2019

## Prerequisites
Before processing the project, Python should be installed and import the various libraries and packages required for processing, visualization of data.

## Usage
This project has the potential to provide valuable insights into the dynamics of company registrations with the Registrar of Companies. It can help various stakeholders make data-driven decisions, adapt to changing market conditions, and contribute to economic growth and development.

The code provided in this repository can be used to:

1. The data set is imported from a CSV file "encoded-Data_Gov_Tamil_Nadu (1).csv"
2. Data preprocessing and Data cleaning:
     Data cleaning means fixing bad data in the dataset. The bad data could be empty cells, data in wrong format and wrong data.
   - Remove duplicate records.
   - Remove rows with missing values.
   - Data Quality Checks.
   - Convert the "REGISTERED_STATE" column to uppercase.
   - Convert the "DATE_OF_REGISTRATION" column to datetime.
     After cleaning the duplicate rows and wrongd data are removed and the dataset is cleaned.
4. The cleaned dataset is saved to a new CSV file "NewCleanedFile.csv"
5. Data analysis:
     Data analysis is a systematic approach which follows the process of inspecting, cleaning, transforming and interpreting data to extract valuable insights.
   The data is analyzes using the describe() function.
7. Data visualization, including:
   - Using Pandas descriptive analysis is done.
   - Values are counted for the "PAIDUP_CAPITAL" and "INDUSTRIAL_CLASS" columns.
   - Analysis is done using different charts and plots for various relations of the columns.
   - Create various plots and visualizations using Matplotlib and Seaborn.
8.Model is chosen for the prediction and to find the accuracy. The model is Random Forest Classifier.
  Random Forest Classifier is trained to predict the "COMPANY_CLASS" based on the dataset.
9. Evaluate the model's performance by calculating accuracy, generating a confusion matrix, and creating a classification report.
