---

# Exploratory Data Analysis (EDA)

## Overview
This EDA (Exploratory Data Analysis) project focuses on analyzing a dataset containing various economic indicators and gold prices. The dataset includes features such as commodity prices, currency exchange rates, and stock market indices, with the target variable being the closing price of gold.

## Requirements
To run this code, you will need the following dependencies:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn plotly
```

## Usage
1. Clone this repository to your local machine.
2. Ensure you have the required dataset available. The dataset used in this project can be accessed from [this link](https://raw.githubusercontent.com/datzxje/ML_Project/main/data/saved/merged_data.csv).
3. Run with JupiterNotebook (can use VSCode to run .ipynb file) or run the provided Python script to perform exploratory data analysis and visualize the data.

```bash
python eda_analysis.py
```

4. The script will generate various visualizations, including line plots for each feature, distribution plots, a plot of gold closing prices over time, and a heatmap showing the correlation between different variables.
5. Additionally, the script will print the correlation matrix and highlight pairs of variables with high correlation (> 0.7 or < -0.7).

## File Description
- `eda_analysis.py`: Python script containing code for exploratory data analysis and visualization.
- `merged_data.csv`: Dataset containing historical data including gold prices, commodity prices, currency exchange rates, and stock market indices.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---
THANKS!
