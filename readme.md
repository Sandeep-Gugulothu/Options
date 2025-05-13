# Options Strategy Using Directional Change, Kalman Filters, and Hidden Markov Models

This project builds an options trading strategy leveraging advanced statistical tools such as **Directional Change (DC) indicators**, **Kalman Filters**, and **Hidden Markov Models (HMMs)** to detect market regimes and optimize trading decisions.

## 📈 Overview

- **Objective**: Create a robust options trading strategy that adapts to changing market conditions using regime-switching models and signal filtering techniques.
- **Dataset**: Historical price data of BEL (Bharat Electronics Limited) fetched from Yahoo Finance (`BEL_equity.csv`).
- **Techniques Used**:
  - Directional Change Event Detection
  - Kalman Filtering for price smoothing
  - Regime detection via Hidden Markov Models
  - Technical indicators via `pandas_ta`

---

## 🧠 Core Components

### 📉 Data Preprocessing
- Cleaned and converted raw price data (OHLCV) to float type.
- Calculated percentage change and plotted it using Plotly for visualization.

### 🔁 Directional Change Indicators
- Implemented a DC event detection algorithm (Chen & Tsang, 2021) to identify market turning points and trends dynamically.

### 🔮 Hidden Markov Models
- Trained an HMM model on price change data to uncover hidden market states and use them for predictive signals.

### 🧮 Kalman Filters
- Applied Kalman filtering for dynamic smoothing and trend extraction in noisy market data.

---

## 📊 Visualizations & Analysis
- Interactive time-series plots using Plotly
- Market state detection and trend visualization
- Strategy behavior across identified regimes

---

## 🛠️ Tech Stack

- **Python**
- `numpy`, `pandas`, `matplotlib`, `plotly`, `scikit-learn`
- `pandas_ta` for technical indicators
- `hmmlearn` for Hidden Markov Models
- `pykalman` for Kalman Filters
- `yfinance` for financial data

---

## 📂 Project Structure

```bash
├── BEL_equity.csv          # Historical BEL stock data
├── final2.ipynb            # Main notebook implementing strategy
├── requirements.txt        # Python dependencies
└── README.md
```

---

## ▶️ Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/options-strategy-dc-hmm-kalman.git
   cd options-strategy-dc-hmm-kalman
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook final2.ipynb
   ```

---

![Image Description](certificate/ed53afd8-ce77-4b08-8200-929d441a4f7d.pdf)

