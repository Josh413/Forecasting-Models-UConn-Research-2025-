Energy Load Forecasting Research
at University of Connecticut
Under the Guidance of Professor Junbo Zhao

Overview:
This repository documents my summer research on load forecasting models using real-world energy data. The project focuses on improving predictive accuracy for energy demand by leveraging time series analysis and machine learning techniques.

Key Notes:
Regression models (e.g., XGBoost) consistently outperformed pure neural network architectures (e.g., CNN, LSTM, Transformer) in forecasting tasks.

Neural networks often produced higher errors and were less stable for time-series forecasting compared to tree-based and statistical methods.

Achieved 24-hour forecasts with the following results:

Wind speed: RMSE of 0.763 m/s (best model: XGBoost)

Load demand: RMSE of 251 MW (best model: XGBoost)

Key Contributions:
Implemented and compared 8 forecasting models, identifying regression-based methods as the most reliable forecasting models.

Wrote Python pipelines for preprocessing, feature engineering, and model evaluation.

Published visualizations and analysis to highlight performance gaps between neural networks and traditional ML (see results/).
