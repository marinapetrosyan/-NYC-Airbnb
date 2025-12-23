# -NYC-Airbnb
📊 NYC Airbnb EDA Project
📌 Project Description

This project was completed as part of a data analysis (EDA) assignment.
The New York City Airbnb Open Data dataset was used to analyze listings in New York City, including pricing, location, room type, availability, and other characteristics.

The dataset was chosen because it:

contains both numerical and categorical features

includes missing values

is large and complex enough for meaningful exploratory analysis

📂 Dataset

The data was obtained from Kaggle:
New York City Airbnb Open Data (2019)

The dataset is uploaded into the notebook using an interactive upload method to ensure the project can run in any environment.

🔍 Project Workflow
1️⃣ Exploratory Data Analysis (EDA)

Examined the dataset size and structure

Analyzed data types and basic statistics

Identified and explored missing values

Created visualizations, including:

Price distribution

Number of listings by borough

2️⃣ Data Cleaning

Filled missing values in reviews_per_month with 0

Removed invalid records where price ≤ 0

3️⃣ Feature Engineering

New features were created to enhance the analysis:

price_per_night – price divided by minimum number of nights

high_availability – binary feature indicating high yearly availability

4️⃣ Insights & Conclusions

Location (borough) and room type have a strong impact on pricing

Listings in Manhattan and Brooklyn tend to be more expensive

Private rooms are generally more affordable than entire apartments

Engineered features helped provide more practical insights

🛠 Technologies Used

Python

Pandas

Matplotlib

Google Colab

📁 Repository Structure

NYC_Airbnb_EDA_Interactive.ipynb – main project notebook

README.md – project documentation

✅ Conclusion

This project demonstrates the full workflow of exploratory data analysis, data cleaning, and feature engineering. The results can be used as a foundation for further analysis or predictive modeling
