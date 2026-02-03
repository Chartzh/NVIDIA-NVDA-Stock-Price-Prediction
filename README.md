# NVIDIA (NVDA) Stock Price Prediction

This project aims to predict NVIDIA (NVDA) stock prices using Machine Learning. By leveraging historical market data, the model attempts to capture trends and patterns to provide future price estimations.

## 📌 Project Overview

NVIDIA is a leading player in the semiconductor and AI industry, making its stock price highly dynamic. This project covers the full data science workflow: data acquisition, preprocessing, Exploratory Data Analysis (EDA), and model implementation.

## 🚀 Key Features

* **Data Acquisition**: Automatically fetches the latest stock data using the `yfinance` library.
* **Feature Engineering**: Implementation of technical indicators like Moving Averages (MA) and lag features to improve model accuracy.
* **Data Visualization**: Visualizing historical price trends and comparing Actual vs. Predicted values.
* **Machine Learning Model**: Built using **Linear Regression** to forecast the closing price.

## 🛠️ Technologies Used

* **Language**: Python
* **Libraries**:
* `Pandas` & `NumPy` (Data Manipulation)
* `Matplotlib` & `Seaborn` (Data Visualization)
* `Scikit-Learn` (Machine Learning)
* `yfinance` (Financial Data Source)
* `Scipy` (Statistical Analysis)


* **Tool**: Google Colab / Jupyter Notebook

## 📊 Results and Evaluation

The model's performance is evaluated using standard regression metrics:

* **Root Mean Squared Error (RMSE): $2.16**
* **Mean Absolute Error (MAE): $1.34**
* **R-squared (R²): 0.9966**
<img width="1005" height="547" alt="download" src="https://github.com/user-attachments/assets/9cc64c6a-35fa-4a76-9694-f1c5bd40dac3" />



## 📂 Repository Structure

* `Prediksi_Close_Price_Nvidia.ipynb`: Main notebook with the complete code and analysis.
* `README.md`: Project documentation.
* `requirements.txt`: List of necessary Python libraries.

## ⚙️ How to Run

1. **Clone this repository**:
```bash
git clone https://github.com/Chartzh/NVIDIA-NVDA-Stock-Price-Prediction.git

```


2. **Install dependencies**:
```bash
pip install -r requirements.txt

```


3. **Run the Notebook**:
Open the `.ipynb` file in Jupyter Notebook or upload it to Google Colab.
