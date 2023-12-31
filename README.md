# BitForecast
---

## Introduction:
BitForecast is a simple project based on Time Series Data Analysis which helps to predicts/forecasts the value of bitcoin in the near future. It consists of several models which calculates the value of bitcoin. The dataset is taken the CoinDesk.

## Different Modelling Experiments:
BitForecast have different models implemented which are as follows:

| EXPERIMENTS | MODEL |
| ---- | ---- |
| Model 0 | Naive Bayes Model (baseline) |
| Model 1 | Dense Model (Window size=7, Horizon = 1) |
| Model 2 | Dense Model (Window size=30, Horizon = 1) |
| Model 3 | Dense Model (Window size=30, Horizon = 7) |
| Model 4 | Conv1D Model |
| Model 5 | LSTM Model |
| Model 6 | Dense Model (multivariate data) |
| Model 7 | N-BEATS Algorithm |
| Model 8 | Ensemble Model (multiple models stacked) |
| Model 9 | Future Prediction Model |
| Model 10 | Dense Model (turkey data) |


## Features of BitForecast:
* N-BEATS algorithm
* Ensemble model
* Future Prediction model
* Model performing on Turkey data
* Comparing results of each model

## Model Visualizations:
* **Naive Bayes Model (Baseline):**
![](https://i.imgur.com/R0njaZr.png)

* **Future Prediction Model**
![](https://i.imgur.com/7b50R0e.png)

*  **Prediction on Turkey Dataset:**
![](https://i.imgur.com/W8hGhbI.png)

* **Comparing Results:**
![](https://i.imgur.com/ilTwHN7.png)

## Conclusion: 
The Baseline model is able to perform the best among all other models achieving the highest accuracy.