# UK-Online-Retail-Analysis-Forecasting-with-Deep-Learning
This project presents an end-to-end data analysis of a UK online retail dataset. It includes data cleaning, exploratory data analysis (EDA), and demand forecasting using deep learning techniques. The goal is to uncover key business insights and predict future sales trends.

The original dataset (Online Retail.xlsx) contains 541,909 rows and 8 columns, spanning from December 1, 2010, to December 9, 2011. The data cleaning process posed several challenges:
	•	The dataset is large, with extensive detail and variety.
	•	Product descriptions are not consistently categorized and include thousands of variations, some with typographical errors.
	•	Successful transactions, cancellations, and bad debt are all mixed together.

Additionally, the one-year time span limits the ability to identify long-term seasonal trends and make reliable forecasts. To overcome this and support the forecasting phase, a synthetic dataset (GH_UK_2011_to_2013.xlsx) was created. Assuming consistent business activity, seasonal data was randomly sampled and redistributed across three years (2011–2013), enabling more robust modeling of temporal patterns.

Given the company’s online retail nature, two key industry statistics were also incorporated: Value of Retail Sales and Value of Internet Sales. Furthermore, external economic indicators such as CPI, GDP, and Holiday & Seasonal Trends were integrated to enhance the model’s ability to capture demand fluctuations and improve forecasting accuracy.

⸻
