# Walmart_stocks_analysis_and_prediction
This repository contains an analysis of Walmart stock data from 1972 to 2025. The analysis includes data preprocessing, exploratory data analysis (EDA), visualization, and predictive modeling using machine learning techniques.

## Dataset
The dataset consists of Walmart stock prices over the years, including features such as:
- Date
- Open Price
- Close Price
- High Price
- Low Price
- Volume

## Key Insights
The notebook explores several aspects of Walmart stock data, including:
- **Data Cleaning & Preprocessing:** Handling missing values, converting date formats, and normalizing data.
- **Exploratory Data Analysis (EDA):** Visualizing trends, stock performance, and feature correlations.
- **Machine Learning Modeling:** Implementing Linear Regression to predict future stock prices.
- **Performance Evaluation:** Using metrics like Mean Squared Error (MSE) and R-squared (R2) to assess model accuracy.

## Sample Code
```python
# Importing the dependencies 
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import warnings 
warnings.filterwarnings('ignore')
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, r2_score

# Loading the data
walmart_stocks = pd.read_csv('walmart_stock_prices.csv')
walmart_stocks.head()
```

## Dependencies
To run this analysis, install the required Python packages:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/walmart-stocks-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd walmart-stocks-analysis
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook walmart_stocks.ipynb
   ```

## Conclusion
This analysis provides insights into Walmart's stock performance and trends over time. The predictive model offers a basis for forecasting future stock prices, though further improvements and additional features can enhance accuracy.

## Author
Richard Olanite - Data Analyst

## License
This project is licensed under the MIT License.

