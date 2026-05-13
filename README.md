# Telecom Churn Prediction with KNN

This project demonstrates a simple machine learning workflow for predicting customer churn in the telecom sector using the K-Nearest Neighbors (KNN) algorithm.

## Features
- Loads and explores a telecom churn dataset
- Preprocesses data and scales features
- Finds the best value of K for KNN
- Trains and evaluates the final model
- Visualizes accuracy and confusion matrix

## Requirements
- Python 3.7+
- pandas
- matplotlib
- seaborn
- scikit-learn

## How to Run
1. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   ```
3. Run the script:
   ```bash
   python task1.py
   ```

## Dataset
- The script downloads the dataset automatically from:
  [telecom_churn_clean.csv](https://raw.githubusercontent.com/DataAnalyst21/DatasetsForDataAnalytics/refs/heads/main/telecom_churn_clean.csv)

## Output
- Prints dataset shape and churn distribution
- Plots KNN accuracy for different K values
- Prints classification report
- Plots confusion matrix

## Author
- Your Name

---
Feel free to modify and extend this project for your own use!
