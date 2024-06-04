# ML_Project

# Gold Price Prediction

## Overview
This project aims to predict the price of gold using machine learning techniques. Specifically, it utilizes Support Vector Regression (SVR) with features such as copper prices, crude oil prices, currency exchange rates, stock market indices, and other relevant factors.

## Requirements
To run this code, you will need the following dependencies:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

You can install these dependencies using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
1. Clone this repository to your local machine.
2. Ensure you have the required dataset available. The dataset used in this project is stored in `"..\data\saved\merged_data.csv"`. You may need to adjust the path accordingly.
3. Run with JupiterNotebook (can use VSCode to run .ipynb file) or run the provided Python script to train the SVR model and make predictions.

```bash
python gold_price_prediction.py
```

4. The script will output evaluation metrics including Mean Absolute Percentage Error (MAPE), Root Mean Squared Error (RMSE), and R2 Score for both the test and validation sets. It will also display a predicted gold price for the next day.
5. Additionally, the script generates visualizations such as:
   - Actual vs Predicted Gold Prices plot
   - Residual Plot
   - Feature Importance plot

## File Description
- `gold_price_prediction.py`: Python script containing the code for training the SVR model, making predictions, and generating visualizations.
- `merged_data.csv`: Dataset containing historical data including gold prices, commodity prices, currency exchange rates, and stock market indices.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

THANKS!