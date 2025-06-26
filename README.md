# NBA Rookie Career Prediction

Predicting whether NBA rookies will stay in the league for 5+ years using K-Nearest Neighbors classification.

## Project Overview

This project analyzes NBA rookie statistics to predict career longevity using a **K-Nearest Neighbors (KNN) algorithm implemented from scratch**. The binary classification determines whether a player will remain in the NBA for at least 5 years based on their rookie season performance.

## Features

- **Custom KNN Implementation**: Built from scratch without using scikit-learn's KNN
- **Hyperparameter Tuning**: Systematic optimization of k-value
- **Data Preprocessing**: Standardization and train-test split
- **Performance Visualization**: Accuracy vs. k-value plotting

## Dataset

**Source**: [Kaggle - NBA Rookie Stats](https://www.kaggle.com/datasets/yakhyojon/national-basketball-association-nba)

The dataset contains NBA rookie statistics including:
- **Features**: Games played, minutes, points, field goals...
- **Target**: Binary classification (1 = stayed 5+ years, 0 = left before 5 years)
- **Size**: 1,340 rookies with 21 statistical features

**Download**: Place the CSV file as `nba-rookies.csv` in the project directory

## Key Results

- Implemented KNN algorithm from scratch using NumPy
- Achieved optimal performance through hyperparameter tuning
- Analyzed feature importance for career prediction

## Technologies Used

- **Python 3.12**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations and algorithm implementation
- **Matplotlib**: Data visualization
- **Scikit-learn**: Data preprocessing only (StandardScaler, train_test_split)

## Usage

1. Download the dataset: https://www.kaggle.com/datasets/yakhyojon/national-basketball-association-nba
2. Place the `nba-rookies.csv` file in the project directory
3. Install required packages: `pip install -r requirements.txt`
4. Run the Jupyter notebook: `jupyter notebook nba-rookies.ipynb`

## Project Structure

```
├── nba-rookies.ipynb               # Main analysis notebook
├── README.md                       # Project documentation
├── requirements.txt                # Python dependencies
└── nba-rookies.csv                 # Dataset (not included in repo)
```

## Author

Marlon Krüger - Medieninformatik Student at Berliner Hochschule für Technik
