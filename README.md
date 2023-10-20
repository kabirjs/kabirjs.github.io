# Kabir Snell's Portfolio

---
---

## UCSB Data Science Capstone
**Project Overview:** The goal of this project is to **digitize Inogen’s comprehensive patient database of medical forms**. We are utilizing two distinct implementations of Optical Character Recognition (OCR) tools – a commercial software tool and custom scripting in **Tesseract**, an open-source **Python** package that utilizes Google’s OCR system; and **Keras OCR**, which is developed by the popular machine learning library Keras. Independently of text extraction, additional data manipulation is necessary to render text content in analysis-ready form. Our primary objective for this project is to automate the extraction of key patient information from prescription forms and **render this data in analysis-ready form**. We are using mock patient forms to develop an automated pipeline and aim to provide Inogen with an approach and/or program that can be implemented at scale with real patient records.

Overall, our team was able to attain an accuracy of about 80% on handwritten prescription forms. Additionally, we were able to create a dashboard which included forecasts, data visualizations, and automated flagging of the misuse of oxygen concentrators. 
<p align="center">
  
![Inogen Poster](assets/inogen_poster.jpg)

<img src="assets/inogen_poster.jpg" alt="hi" class="inline"/>

</p>


_**Technical Skills:**_ Optical Character Recognition, Linear Regression & Forecasting, Excel Dashboarding

_**Tools:**_ R, Python, Excel

_**Student team:**_ Ankur Malik and Kabir Snell

_**Project Advisors:**_ Trevor Ruiz (UCSB), Paula Sarmiento (Purdue University), Norbert Leinfellner (Inogen Inc.)

_Code not shared due to medical information privacy_

---

## Santa Barbara Airport (SBA) Time Series Analysis Project
**Project Abstract:** This project presents a **time series analysis** of monthly passenger counts through Santa Barbara Municipal Airport. The data was obtained from the Bureau of Transportation Statistics. Two forecasting models were used: a **Seasonal Autoregressive Integrated Moving Average (SARIMA) model and a Lagged Regression model**.

The SARIMA model is a widely used method for forecasting time series data that exhibits seasonality. It is an extension of the Autoregressive Integrated Moving Average (ARIMA) model that includes seasonal terms. The Lagged Regression model, on the other hand, is a linear regression model that uses lagged values of the dependent variable as predictors.

In this study, both models were fit to the data and their forecasting performance was evaluated. The results show that both models were able to accurately forecast passenger counts, with the **SARIMA model performing slightly better**. Further research is needed to determine the optimal model parameters and to evaluate the performance of these models on other datasets. In conclusion, this paper demonstrates the usefulness of both SARIMA and Lagged Regression models for forecasting passenger counts through Santa Barbara Municipal Airport. These models can provide valuable insights for airport management and planning.


[insert images]

_**Technical Skills:**_ Seasonal Autoregressive Integrated Moving Average (SARIMA) Model & Forecasting, Time Series Analysis, Lagged Regression Model

_**Tools:**_ R, Python

---

## Music Genre Classification - A Machine Learning Approach
**Project Overview:** The goal of this project is to answer the question: _Can we predict the genre of a song using the attributes provided by the Spotify API data?_ We will begin with an exploratory data analysis (EDA), followed by building and assessing the metrics of various **machine learning models** in order to discover the best predictive model. This project used a **dataset of over 20,000 songs** and their respective Spotify data. I fit many different machine learning models using both **Python** and **R** in order to find the highest accuracy for music genre classification. The models used were: **decision trees, random forest, xgboost, k-nearest neighbors, and a neural network**. Ultimately the accuracy was very high ~90% for some musical genres and very low for others ~35%. This is due to musical genre overlap such as Rap and Hip-Hop. 

[images]

_**Technical Skills:**_ XGBoost, Random Forest, Neural Network, Keras, Tensorflow

_**Tools:**_ R, Python
