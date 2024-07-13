# Premier League Game Winner Predictor

<img src="https://github.com/user-attachments/assets/d2fd750c-9798-4f4f-bbe8-16b34d2e45fe" alt="pml" width="25%">

## Overview
This project aims to predict Premier League game winners using historical data, player stats, and team performance metrics. By leveraging machine learning techniques, the model provides predictions to assist in game outcome analysis.

## Features

- **Data Collection**: Scrapes Premier League game data from multiple seasons using Python and requests.
- **Data Cleaning**: Utilizes BeautifulSoup and pandas to parse and clean HTML data.
- **Feature Engineering**: Processes features such as team performance metrics, match stats, and more.
- **Model Training**: Implements machine learning models to predict game outcomes.
- **Visualization**: Generates insightful graphs to illustrate feature importance and model accuracy.

## Model Explanation

### Data Collection
- **Script**: `collect_data.py`
- **Libraries**: `requests`, `BeautifulSoup`
- **Description**: Scrapes Premier League game data for over 1,500 matches from multiple seasons.

### Data Cleaning
- **Script**: `preprocess_data.py`
- **Libraries**: `BeautifulSoup`, `pandas`
- **Description**: Parses and cleans the HTML data to extract match statistics with 95% accuracy.

### Feature Engineering
- **Script**: `feature_engineering.py`
- **Libraries**: `pandas`, `numpy`
- **Description**: Processes features such as `opp_code`, `hour`, `day_code`, and `venue_code`.

### Model Training
- **Script**: `train_model.py`
- **Libraries**: `scikit-learn`
- **Description**: Trains a machine learning model to predict Premier League game winners using historical data, player stats, and team performance metrics.

### Visualization
- **Script**: `visualize.py`
- **Libraries**: `matplotlib`, `seaborn`
- **Description**: Generates visualizations to illustrate feature importance and model accuracy.

<img width="70%" alt="MatchPic2" src="https://github.com/user-attachments/assets/412d7fa3-8856-404f-945b-237dff30a056">

<img width="70%" alt="MatchPic1" src="https://github.com/user-attachments/assets/92d51ac3-c2b4-489a-a1c1-8ead2bad5ffb">
 

## Results

- **Model Accuracy**: 60.28%
- **Precision with Rolling Averages**: 62.50%

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.
