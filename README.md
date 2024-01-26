# Walmart-TimeSeries-Analysis
Walmart is a global retail giant with a vast network of stores and a wide range of products. Effective inventory management and sales prediction are critical for Walmart's operations. Our project focuses on leveraging time series forecasting techniques to optimize these processes.
It e involves analyzing historical sales data to unveil intricate temporal patterns and construct resilient forecasting models. The goal is to empower Walmart to achieve ideal inventory levels, make strategic pricing decisions, and maximize resource efficiency.

![alt text](https://github.com/BlackReaper0/Walmart-TimeSeries-Analysis/blob/main/Poster_Walmart_TSF.jpg)

## Prerequisites

- Make sure you have Python installed on your system. If not, you can download it from [Python's official website](https://www.python.org/).

- Dataset : [Link](https://www.kaggle.com/code/rohanchopade/walmart-pbl/input)

Overview of files :
- The repository consist of 2 ipynb files:
    a) EDA.ipynb
    b) Time-Series.ipynb
- It also contains PowerBi dashboard file, Project Report and Poster.

### 1. EDA.ipynb
a. Merging:
Combining multiple datasets into a single, unified dataset. 

b.Cleaning:
Handling missing values, removing duplicates, and addressing any data quality issues.

c. Formatting:
Standardizing the format of the data, ensuring consistency.

d. Manipulation:
Performing transformations on the data to make it suitable for analysis.

e. Analysis:
Exploring and deriving insights from the data through statistical and visual analysis.

f. Feature Importance:
Assessing the importance of different features in the dataset, which is crucial for building predictive models.

### 2. Time-Series.ipynb
a. ARIMA Model:
Implementation of the Autoregressive Integrated Moving Average (ARIMA) model for time series analysis. ARIMA is a widely used method for forecasting based on historical patterns.

b. SARIMA Model:
Application of the Seasonal Autoregressive Integrated Moving Average (SARIMA) model. SARIMA extends ARIMA by considering seasonality in the data, making it suitable for time series with recurring patterns.

c. FB PROPHET Model:
Utilization of the Facebook Prophet model for time series forecasting. Prophet is designed to handle daily observations that display patterns on different time scales, including holidays and special events.

d. Model Comparison:
Comparative analysis of the three models (ARIMA, SARIMA, FB PROPHET). Evaluation metrics, visualizations, and insights derived from each model's performance are presented.

e. Selection of Best Model:
Discussion on the criteria used to select the best model for time series prediction. In this case, it's mentioned that FB PROPHET was identified as the most suitable model.

f. Prediction using FB PROPHET:
Application of the selected FB PROPHET model for making predictions on the time series data. This includes code snippets and explanations demonstrating how predictions are made and visualized.




## Getting Started
These instructions will guide you on how to set up and activate a virtual environment for this project.

### Virtual Environment Setup

1. Clone the repository to your local machine.
   ```bash
   git clone git clone https://github.com/mangoresoham/Walmart-Time-Series-Analysis.git
   ```

2. Create a virtual environment. Run the following command
    ```bash
    python -m venv venv
    ```
3. Activate the Environment
    ```bash
    .\venv\Scripts\activate
    ```


### Libraries

You need to install the following libraries inside the environment :

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install xgboost
pip install plotly
pip install holidays
pip install pandasql
pip install statsmodels
pip install pmdarima
pip install prophet
pip install ipykernel
pip install jupyter notebook
```
    
## Deployment

Once the virtual environment is activated and Jupyter is installed, run:
```bash
jupyter notebook
```
Inside the jupyter notebook locate and run .ipynb files.


## Authors

- [@BlackReaper0](https://github.com/BlackReaper0)
- [@mangoresoham](https://github.com/mangoresoham)
- [@BhaktiAyarekar](https://github.com/BhaktiAyarekar)
- [@2003-ankita](https://github.com/2003-ankita)
