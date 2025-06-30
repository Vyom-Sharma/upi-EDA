# 📊 UPI Transactions 2024 – Exploratory Data Analysis

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of UPI (Unified Payments Interface) transaction data from **2024**, focusing on patterns, anomalies, and key insights across banks, users, and transaction types.

## 📁 Dataset
The dataset was accessed via [KaggleHub](https://github.com/kagglehub/kagglehub) using the Kaggle API: kagglehub.dataset_load(KaggleDatasetAdapter.PANDAS, "skullagos5246/upi-transactions-2024-dataset", filepath)


## 🔧 Tools & Libraries
This project was implemented in a Jupyter Notebook using the following Python libraries:

- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [hvPlot](https://hvplot.holoviz.org/)
- [Plotly](https://plotly.com/python/)

## 📌 Key Analyses & Visualizations

### 🏦 Bank-wise Transaction Analysis
- Total number of transactions **sent and received** by each bank
- Visualized using bar plots and heatmaps for sender–receiver patterns

### 💸 Spending Distribution
- Distribution of transaction amounts across users
- Identification of **high-value vs low-value transaction trends**

### 🚨 Fraud Transactions Analysis
- Detection and visualization of **suspicious/fraudulent patterns**
- Compared across banks and time periods

### ❌ Failed Transactions Pattern
- Analysis of failed transactions by:
  - Bank
  - Time of day
  - Amount

### 📈 Time Series Trends (Optional)
- Transaction volume trends across months
- Spikes during festivals or salary dates

## 📊 Visuals
- Static graphs via Matplotlib and Seaborn
- Interactive plots using hvPlot and Plotly for better insight exploration

## 🧠 Insights
- Which banks handle the most UPI volume?
- How do failed transactions correlate with volume or value?
- Are frauds clustered around certain banks or times?

## 🚀 Getting Started

To run this notebook:

1. Clone the repo
2. Install dependencies (preferably in a conda environment):
   ```bash
   conda install pandas numpy matplotlib seaborn plotly hvplot -c conda-forge
3. Download the dataset from Kaggle (or load it via KaggleHub)
4. Run the notebook in Jupyter Lab or Notebook


