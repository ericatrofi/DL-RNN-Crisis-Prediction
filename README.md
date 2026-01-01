# DL-RNN-Crisis-Prediction
Deep Learning for Financial Crisis Prediction | AI in Finance course at Universität St. Gallen

This project explores the use of deep learning methods for financial crisis prediction based on multi-market financial and macroeconomic time-series data.
The goal is to identify temporal patterns and early-warning signals preceding crisis events by modeling sequential dependencies across markets.
An end-to-end predictive pipeline is implemented, covering data ingestion, preprocessing, feature engineering, normalization, and time-series sequence construction.
Sequential data are modeled using a Recurrent Neural Network (RNN) architecture designed to capture dynamic temporal structures in financial indicators.

Beyond predictive accuracy, the project emphasizes quantitative reasoning and interpretability, analyzing model outputs to understand temporal risk dynamics and classification behavior, particularly under class imbalance.

## Methodology
- Construction of rolling time-series sequences from multi-market indicators
- Feature normalization and preprocessing tailored to sequential modeling
- Training of an RNN-based classifier using TensorFlow / Keras
- Model evaluation with appropriate classification metrics and attention to temporal consistency
## Technologies
Python: NumPy, Pandas, scikit-learn, TensorFlow, Keras
## Data Source
The dataset used in this project is publicly available on Kaggle.

