# Gold-Price-Prediction-Machine-Learning

Predicting gold prices using Machine learning algorithm.

Gold is a highly valued commodity, and predicting its price is a valuable tool for investors and people who want to buy gold. However, predicting the price of gold has traditionally been a challenging task due to its volatile nature. In this project, I developed a machine learning model to predict gold prices.

## Model: 

* I developed a machine learning model that leverages historical gold price data and other relevant features like Oil Price, Standard and Poor’s (S&P) 500 index, Dow Jones Index US Bond rates (10 years), Euro USD exchange rates, prices of precious metals Silver and Platinum and other metals such as Palladium and Rhodium, prices of US Dollar Index, Eldorado Gold Corporation and Gold Miners ETF, to predict the price of gold.
* The model uses a random-forest algorithm. It's trained on a large dataset of gold price data spanning from November 18th 2011 to January 1st 2020 from various sources, with a focus on ensuring that the model can accurately predict price fluctuations.

## Technologies Used:

  * Python
  * Pandas
  * NumPy
  * Seaborn
  * Matpplotlib
  * Scikit-learn

## Data:

* Publicly available diabetes dataset ([Kaggle](https://www.kaggle.com/datasets/sid321axn/gold-price-prediction-dataset))
* Pre-processing steps performed (missing value handling, feature engineering)

## Methodology:

* Analysed the data for statastical Analysis, Missing Values, Correlational analysis.
* Found outcome distribution and correlation between input parameters.
* Split the data into training and testing dataset and further applied normalization.
* Used Random Forest Regressor algorithm for prediction.
* Evaluated models using R square score with value of 0.98.

## Visualization:

[Actual Vs Predicted Values of Gold](

## Project Structure:

The project is organized as follows:

* Data: This directory contains the Gold Price dataset in CSV format.
* Notebooks: This directory contains Jupyter notebooks with the Python code used for data analysis and visualization.
* README.md: This file provides an overview of the project, objectives, and instructions for running the code.
* LICENSE: This project is under the MIT License.

## Contributing: 

Contributions to this project are welcome! If you have ideas for improving the analysis, adding new features, or fixing issues, please open an issue or submit a pull request.

## License: 

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments:

The Gold Price dataset used in this project is publicly available and can be found on various sources, including Kaggle.
Thank you for your interest in the Diabetes Dataset Prediction project! We hope you find the insights and code provided valuable for your data analysis endeavors.
