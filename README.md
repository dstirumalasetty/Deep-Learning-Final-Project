# Forecasting Stock Prices with Machine Learning: Combining Sentiment Analysis and Technical Indicators  

This repository contains the code and datasets used for the stock price forecasting project. The project aims to develop accurate prediction models for AAPL stock prices using various machine learning techniques. By leveraging historical stock price data, sentiment analysis scores, and news articles related to AAPL stock, we seek to gain insights into market trends and build models that can effectively forecast future stock prices.

## Dataset

The dataset used in this project is crucial for training and evaluating the forecasting models. It is available in the `datasets` folder and includes multiple files representing different stages of data processing. The initial dataset contains historical stock price data for Apple, retrieved from reliable sources such as Yahoo Finance. It also incorporates sentiment analysis scores, including compound, subjectivity, and polarity, calculated using the VADER lexicon and the TextBlob library. Furthermore, news articles related to AAPL stock, obtained from the polygon.io API, are included to capture market events and sentiment. The dataset is organized and documented to ensure data integrity and facilitate reproducibility.

## Data Cleaning and Processing

The `data-cleaning` folder contains the code and scripts used for data cleaning and preprocessing. As part of the data cleaning process, missing values in the collected data were handled, ensuring the integrity and reliability of the dataset. Data normalization techniques were employed to address variations in scale among the different technical indicators. Feature engineering techniques were applied to extract additional relevant features from the existing dataset and technical indicators. Moreover, natural language processing techniques were utilized to process the news articles, extract sentiment analysis scores, and incorporate them into the dataset. These preprocessing steps aimed to enhance the quality and usability of the dataset for subsequent analysis and model training.

## Models

The `models` folder encompasses the implementation of different stock price forecasting models. Each model is organized in a separate file and includes the necessary code for model training, evaluation, and prediction. The models employed in this project include LSTM, CNN+LSTM, Transformer, and ARIMA. These models were chosen based on their relevance to stock price forecasting tasks and their proven performance in similar prediction problems. The choice of models provides a comprehensive comparison of different architectures, allowing us to assess their effectiveness in forecasting AAPL stock prices. Additionally, we explored the impact of using sentiment analysis scores and technical indicators separately by training two versions of the CNN+LSTM model—one with only sentiment scores and one with only technical indicators. This analysis enables us to evaluate the effectiveness of each feature in stock price prediction.

## Usage

To use this project, follow these steps:
1. Clone the repository to your local machine.
2. Ensure that the required dependencies are installed.
3. Explore the `datasets` folder to access the available datasets, including historical stock price data, sentiment analysis scores, and news articles.
4. Review the code in the `data-cleaning` folder to understand the data cleaning and preprocessing steps taken.
5. Explore the `models` folder to access the different forecasting models implemented in this project.
6. Run the desired model files to train, evaluate, and predict stock prices.
7. Experiment with different configurations and hyperparameters to further refine the models and improve the forecasting accuracy.

## Contribution

Contributions to this project are welcome. If you have any suggestions, improvements, or additional models to include, feel free to create a pull request. Contributions can range from refining the data cleaning and preprocessing techniques to exploring new forecasting models or integrating additional data sources for enhanced analysis.
