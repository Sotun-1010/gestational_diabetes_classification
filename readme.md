# Predicting Gestational Daibetes with Logistic Regression and some other classification Models

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
- [Tools](#tools)
- [Contact](#contact)

<!-- OVERVIEW -->

## Overview

![screenshot]()

In this project I analysed one of the datasets on [Kaggle](<https://www.kaggle.com>) centered on Diabetes. My aim was to build a classification model to see if it could predict cases of previous gestational diabetes based on some features. The [dataset](https://www.kaggle.com/datasets/marshalpatel3558/diabetes-prediction-dataset) contained 10,000 rows and  21 columns of data. I also used an automated EDA process with the ydataprofiling library which was quite exciting.
An interesting discovery about the data set is all the columns are very weakly correlated with one another which I thought might have affected the accuracy I got later on of less than 53%. I tried the Logistic Regression Model, Decision Tree Model, Random Forest Model and K Nearest Neighbours Model and still got subpar results with Logistic Regression model retaininng the highest accuracy. I also tried some feature engineering procedures by selecting the most relevant columns based on statistics amongst others but all to no avail. I also tried some other approaches in different notebooks not uploaded here but still the same result. I would love to conclude that the data isn't qualitative enough since all the columns had very weak correlations with one another which indicates low predictive power, but I'd be willing to try out the Naive Bayes model on it in the nearest future since it handles each feature independently not minding if thy are correlated or not, but for now, I'd place it on hold. Feel free to go through the notebook and reach out to me if you have any suggestions, ideas or comments please. Thanks.

## Tools

- [Pandas](https://pandas.pydata.org)
- [Seaborn](https://seaborn.pydata.org)
- [Sklearn](https://scikit-learn.org/stable/user_guide.html)
- [Ydata profiling](https://docs.profiling.ydata.ai/latest/)

## Contact

- GitHub [@Sotun-1010](https://github.com/Sotun-1010)
- Twitter [@O_G_Sotun](https://twitter.com/O_G_Sotun?t=kRiO1YNhYKn8NJJnxTZ42A&s=03)
- Portfolio Site [Ogunjirin Oluwasotun](https://www.datascienceportfol.io/oluwasotunogunjirind)
- Medium [Ogunjirin Oluwasotun Goodness](https://medium.com/@oluwasotunogunjirin)
- Website [Oglytics](https://oglytics.webflow.io/)
