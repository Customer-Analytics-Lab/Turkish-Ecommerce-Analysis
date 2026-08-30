# Turkish E-Commerce Customer Analysis

Segmentation, lifetime value, and churn modeling on a 17,049-transaction
e-commerce dataset (5,000 customers, Jan 2023 – Mar 2024).

**Methods:** RFM analysis with K-Means clustering, OLS regression for
customer lifetime value, logistic regression for 180-day churn.

**Note on the data:** exploratory analysis showed unusually low variance
in discount rates, delivery times, and satisfaction ratings, indicating
the dataset is synthetically generated. Analysis was aggregated to the
customer level, where meaningful behavioral variation remains.

**Files:** `TurkishEcommerceAnalysis.ipynb` (code), 
`TurkishEcommerceAnalysis.pdf` (full report).

Python · pandas · NumPy · scikit-learn · statsmodels · Matplotlib · Seaborn
