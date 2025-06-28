# 🛍️ UK Online Retail Analysis & Forecasting with Deep Learning

This project presents an end-to-end data analysis of a UK online retail dataset. It encompasses data cleaning, exploratory data analysis (EDA), and demand forecasting using deep learning techniques. The objective is to uncover insights and predict future sales trends.

---

## 📊 Project Overview

- **Dataset**: `Online Retail.xlsx` containing 541,909 rows and 8 columns, spanning from December 1, 2010, to December 9, 2011.
- **Challenges**:
  - Large dataset with extensive detail and variety.
  - Inconsistent product descriptions with typographical errors.
  - Mixed data including successful transactions, cancellations, and bad debt.
  - Limited one-year time span restricting long-term seasonal trend analysis.

To address the limited time span, a synthetic dataset (`GH_UK_2011_to_2013.xlsx`) was created by randomly sampling and redistributing seasonal data across three years (2011–2013), assuming consistent business activity. This approach enables more robust modeling of temporal patterns.

Additionally, external economic indicators such as CPI, GDP, and Holiday & Seasonal Trends were integrated to enhance the model’s ability to capture demand fluctuations and improve forecasting accuracy.

---

## 🛠️ Tools & Techniques

- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, TensorFlow/Keras
- **Models**: Transformer-based deep learning models for time series forecasting
- **Data Processing**: Data cleaning and preprocessing using pandas
- **Visualization**: EDA using matplotlib and seaborn

---

## 📂 Repository Structure

- `Data-Cleaning & EDA.ipynb`: Jupyter Notebook for data cleaning and exploratory data analysis.
- `Forecasting by using Transformer Model.ipynb`: Jupyter Notebook implementing a Transformer-based model for demand forecasting.
- `Data-Clean & EDA Summary.pdf`: PDF summarizing the data cleaning and EDA process.
- `Online Retail.xlsx`: Original dataset.
- `GH_UK_2011_to_2013.xlsx`: Synthetic dataset for extended time series analysis.

---

## 📈 Results

The deep learning model effectively captures complex patterns in the sales data, providing accurate forecasts for future demand. The integration of external economic indicators further enhances the model's predictive capabilities.

---
