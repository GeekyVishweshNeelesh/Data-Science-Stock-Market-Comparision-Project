# 📈 Stock Market Comparison using Python & Plotly

This project analyzes and compares multiple stock market indices (e.g., NIFTY, SENSEX, NASDAQ) to understand their investment growth, volatility, and market behavior over time. Using real-time data from Yahoo Finance via `yfinance`, we calculate cumulative returns, evaluate risk using volatility, and assess beta to understand index sensitivity.

## 🔧 Libraries & Tools

- `yfinance` – for fetching historical stock data  
- `plotly.graph_objects` – for interactive visualizations  
- `pandas` – for data processing  
- `numpy` – for numerical calculations (implied by finance metrics)

## 📊 Core Analysis

- **Cumulative Return**: Tracks total return over the investment period  
- **Volatility Comparison**: Measures price fluctuations (risk) across indices  
- **Covariance & Beta**: Evaluates how one index moves relative to others  
- **Scatter Plots**: Shows correlation and ROI behavior visually

## 📁 Folder Structure
📂 Data-Science-Stock-Market-Comparision-Project  
├── Stock_Market_Comparison.ipynb     # Main Jupyter Notebook  
├── images/                           # Exported visuals (e.g., volatility, return plots)  
└── readme.md                         # Project overview  

## 🚀 How to Run

1. Clone this repo:  
   `git clone https://github.com/GeekyVishweshNeelesh/Data-Science-Stock-Market-Comparision-Project.git`

2. Install required packages:  
   `pip install yfinance plotly pandas`

3. Open the notebook:  
   `jupyter notebook Stock_Market_Comparison.ipynb`

## 📷 Sample Visuals

Visualizations include:  
- Cumulative return line graphs  
- Bar charts for volatility
  

All plots are generated using `plotly` and are stored in the notebook and `images/` folder.

## ❤️ Made with Love by [GeekyVishweshNeelesh]
(https://github.com/GeekyVishweshNeelesh)
