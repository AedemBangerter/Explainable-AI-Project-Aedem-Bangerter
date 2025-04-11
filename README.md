# Explainable AI Project

**Explaining LSTM-based Time Series Forecasting Using LIME and Integrated Gradients**

## Description

This project investigates the use of two Explainable AI (XAI) methods **LIME** and **Integrated Gradients**, to interpret predictions from an **LSTM model** trained on historical Apple stock price data.  
The goal is to understand which **time steps** are most influential in a one-step-ahead forecasting task and how each explanation method aligns with expectations in a financial prediction setting.

## Table of Contents

- [Installation](#installation)   
- [Data](#data)  
- [License](#license)

## Installation

To run this project, ensure you have **Python 3.7** or later installed, along with the following dependencies:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `scikit-learn`  
- `torch`  
- `captum`  
- `lime`  
- `yfinance`

You can install the required packages and launch the notebook using the following steps:

### Clone the repository

```bash
git clone https://github.com/AedemBangerter/Explainable-AI-Project-Aedem-Bangerter.git
cd Explainable-AI-Project-Aedem-Bangerter

### Install the required packages

```bash
pip install pandas numpy matplotlib scikit-learn torch captum lime yfinance
```

## Data

This project uses hourly Apple (AAPL) stock price data from January 2020 to January 2024, retrieved using the [`yfinance`](https://github.com/ranaroussi/yfinance) Python library.

The prediction task is a one-step-ahead forecast, where the model predicts the next price based on the previous 10 time steps.

## License

The data used in this project is sourced from public APIs (Yahoo Finance) and is subject to their usage policies.  
This project is for educational and research purposes only.
