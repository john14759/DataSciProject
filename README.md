# Covid-Forecasting

## About
This is a mini project for SC1015 (Intro to Data Science and Artificial Intelligence) which focuses on COVID-19 data collected over the pandemic. We will be using past data recorded to see whether we will be able to predict and forecast COVID-19 cases in the future.

#### Dataset retrieved from
[Coronavirus Pandemic (COVID-19) | OurWorldInData (OWID)](https://ourworldindata.org/coronavirus)

For a more detailed walkthrough, please view the source code in order:
- [Data Cleaning & Exploratory Analysis](https://github.com/john14759/covid-forecasting/blob/main/Data%20Cleaning%20%26%20Exploratory%20Analysis.ipynb)
- [Machine Learning model & conclusion](https://github.com/john14759/covid-forecasting/blob/main/Machine%20Learning.ipynb)

## Contributors
1. **@JabLau** (Jabez Lau)
2. **@john14759** (Johnathan Chow)

## Problem definition
- Does the statistics from the dataset *(eg. weekly_hosp_patients, new_vaccinations, stringency_index)* give an accurate representation of the number of COVID-19 cases *(new_cases)* on the given day?

- Can we use these statistics and apply it to a machine learning model to predict future COVID-19 cases for a particular country?

- Whether the machine learning model used gives an accurate forecast of future COVID-19 cases

## Models used
#### Facebook Prophet
[Intro to Facebook Prophet | Prophet Github](https://facebook.github.io/prophet/docs/quick_start.html)

## Conclusion
- Covid-19 cases can be very hard to predict because of alot of various factors that can affect the spread of the virus

- In fact, some of this factors are very inconsistent with the number of COVID-19 cases daily

- So, the best way to predict COVID-19 cases can be through the use of previous recorded daily cases and the holidays where COVID-19 cases might spike

- Through our machine learning model, we forecasted a few months worth of daily covid cases, and the results are quite accurate in terms of predicting whether there will be an increasing or decreasing trend

- However, the drawback of this machine learning model is that COVID-19 cases sometimes can be very abrupt where the number of cases can just skyrocket from one day to another and this model won't be able to foresee it.


## References

- https://www.mikulskibartosz.name/prophet-plot-explained/
- https://towardsdatascience.com/forecasting-at-scale-with-facebook-prophet-a-case-study-on-its-merits-limitations-b24a694dd7c7
- https://towardsdatascience.com/using-prophet-after-covid-read-this-first-fc27cd77f3d7
