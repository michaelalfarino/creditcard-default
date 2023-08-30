# Predicting Default of Credit Card Clients

![Python](https://img.shields.io/badge/Python-black?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-black?logo=scikitlearn)
![pandas](https://img.shields.io/badge/pandas-black?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-black?logo=numpy)
![Matplotlib](https://img.shields.io/badge/matplotlib-black?logo=data:image/svg%2bxml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMjgiIGhlaWdodD0iMTI4IiBzdHJva2U9IiM3NzciIGZpbGwtb3BhY2l0eT0iLjgiPgo8cGF0aCBmaWxsPSIjRkZGIiBkPSJtNjMsMWE2Myw2MyAwIDEsMCAyLDB6bTAsMTRhNDksNDkgMCAxLDAgMiwwem0wLDE0YTM1LDM1IDAgMSwwCjIsMHptMCwxNGEyMSwyMSAwIDEsMCAyLDB6bTAsMTRhNyw3IDAgMSwwIDIsMHptNjQsN0gxbTEwOC00NS05MCw5MG05MCwwLTkwLTkwbTQ1LTE4djEyNiIvPgo8cGF0aCBmaWxsPSIjRjYwIiBkPSJtNTAsOC0yMCwxMCA2OCw5MiAxMC0xMEw2NCw2NHoiLz4KPHBhdGggZmlsbD0iI0ZDMCIgZD0ibTE3LDUwdjI4TDY0LDY0eiIvPgo8cGF0aCBmaWxsPSIjN0Y3IiBkPSJtNjQsNjQgNiwzNUg1OHoiLz4KPHBhdGggZmlsbD0iI0NGMyIgZD0ibTY0LDY0IDEzLTQwIDksNXoiLz4KPHBhdGggZmlsbD0iIzA0RiIgZD0ibTY0LDY0IDE0LTYgMSw0emwtMjYsMTMgMyw0eiIvPgo8L3N2Zz4=)
![seaborn](https://img.shields.io/badge/seaborn-black)

This project focuses on building a machine learning model to predict whether credit card clients will default on their payments. The dataset encompasses diverse client attributes like credit limit, gender, education, marital status, age, and repayment history across months, with the target being the occurrence of default in the subsequent month. By training on historical data, the goal is to develop a model that helps financial institutions identify high-risk clients and make informed lending choices.

To tackle data imbalance, the SMOTE-upsampling technique is employed, yielding synthetic data points that enhance model training. A comparative analysis between the original and upsampled Logistic Regression models highlights the considerable improvement in predictive performance achieved through the synthetic samples, demonstrated by the increase of F1-scores and accuracy.

Further exploration of the SMOTE-upsampled data was done using multiple algorithms such as Logistic Regression, Random Forest, AdaBoost, XGBoost, and LightGBM. LightGBM emerged as the most effective in this case, achieving an 84.186% accuracy. The project showcases the potential of advanced techniques in real-world scenarios for credit risk assessment and informed decision-making by financial institutions.

* [Project Notebook](https://github.com/michaelalfarino/creditcard-default/blob/main/Predicting_Default_of_Credit_Card_Clients.ipynb)
