**Quantitative Risk Management & Modelling (FM321) Assignment**

In this repository I address the following assignment title:

Risk Forecasting With Machine Learning (ML) (only for students with a solid knowledge of ML). Select three price series, load them into R, and convert them to returns. Briefly describe the data statistically. Create a ML forecasting model for risk.

I selected 3 stocks:
* Apple (ticker: AAPL)
* JP Morgan (ticker: JPM)
* Tesla (ticker: TSLA)

Throughout this assignment I tested various ML models (Decision Trees, Random Forests, XGBoost), an LSTM neural network (in Tensorflow), and typical quant volatility statistical models like GARCH.

This yielded the following results:

<img width="468" alt="image" src="https://github.com/user-attachments/assets/233a74bc-0a55-4f70-b0d2-0cf08e2eb780" />

<img width="436" alt="image" src="https://github.com/user-attachments/assets/29c0793b-fee5-4707-8f7b-4a4438767835" />

Overall, the Random Forest was proven to be my best performing model.

Note: the original data was used from WRDS, but cannot be attached publicly to Github as this requires a license to access.
