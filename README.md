Indoor Air Quality (IAQ) plays a crucial role in human health, especially as people spend increasing amounts of time indoors. Poor IAQ, caused by pollutants such as PM2.5, PM10, and CO, can pose serious long-term health risks.
This project focuses on predicting indoor pollutants using a Threshold Autoregressive (TAR) model integrated with Random Forest (RF) to achieve high prediction accuracy.
Traditional models such as ARIMA, SARIMA, TBATS, VAR, and Exponential Smoothing were also employed for comparison, but their limitations in handling non-linear, non-stationary time series data became evident.
Our approach using TAR + RF outperformed these models, achieving the highest prediction accuracies.

Objectives

Predict pollutant concentrations (PM2.5, PM10, CO) with high accuracy.
Compare TAR + RF with traditional forecasting methods.
Highlight the role of temperature and humidity in IAQ monitoring.
Support better sensor design and smarter monitoring systems.

Methodology

Data Preprocessing
Time series data collection for IAQ pollutants.
Normalization & handling missing values.
Feature inclusion: temperature, humidity, pollutant levels.
Models Applied
Baseline: ARIMA, SARIMA, TBATS, VAR, Exponential Smoothing.
Proposed Hybrid: Threshold Autoregressive (TAR) + Random Forest (RF).

Evaluation Metrics
R² Score, RMSE, MAE, MASE

Results
The TAR + RF model achieved:
PM2.5 → 97.38%
PM10 → 96.39%
CO → 96.87%

Traditional models showed lower performance, especially for non-linear and non-stationary pollutant data.

Tech Stack
Programming Language: Python
Libraries: pandas, numpy (data preprocessing), statsmodels (ARIMA, VAR, SARIMA, etc.), scikit-learn (Random Forest, metrics), matplotlib, seaborn (visualization)

Future Work
Integrate additional IAQ parameters (NO2, SO2, VOCs).
Deploy real-time IAQ monitoring using IoT sensors + cloud.
Extend hybrid model with deep learning architectures (LSTM, TCN, Transformer).

Citation
If you use this work in your research, please cite:

@project{iaq_prediction_2025,
  title={Indoor Air Quality (IAQ) Prediction using TAR + RF},
  author={Samiksha Sandeep Zokande},
  year={2025},
  note={}
}

Contributing
Contributions are welcome! Feel free to fork this repository, create a new branch, and submit a pull request.

Contact
For questions or collaboration opportunities, reach out at:
samikshazokande29@gmail.com
