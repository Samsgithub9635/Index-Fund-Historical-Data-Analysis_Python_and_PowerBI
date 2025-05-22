# Mutual Fund Plan: Analyzing Nifty50 for High Returns & Low Risk

---

## Overview

This project develops a mutual fund investment strategy by analyzing daily stock prices of Nifty 50 companies. The goal is to select companies offering high returns and low risk, simulate long-term investment growth, and provide actionable insights for investors and stakeholders.

---

## Problem Statement

- **Objective:** Build a mutual fund investment bucket optimized for long-term growth, balancing risk (volatility) and reward (ROI).
- **Goals:**
  - Select stocks with high ROI and low volatility.
  - Evaluate performance using historical data and quantitative metrics.
  - Simulate future value of monthly investments (SIP).
  - Enable stable, compounded growth for conservative investors.

---

## Dataset

- **Source:** Daily closing prices of 50 major Indian companies (Nifty 50) from Stato.io
- **Features:**
  - Date
  - Company Ticker (e.g., RELIANCE.NS, ICICIBANK.NS)
  - Closing Price

- **Sectors Covered:** Banking, Technology, Consumer Goods, Automotive, and more.

---

## Project Workflow

1. **Data Collection & Preparation**
    - Gathered historical stock data.
    - Used Excel to remove duplicates.
    - Restructured and standardized the dataset using ChatGPT.
2. **Exploratory Data Analysis (EDA)**
    - Calculated Return on Investment (ROI) and volatility for each stock.
    - Used Python and Plotly for interactive visualizations.
3. **Stock Selection Strategy**
    - Chose stocks with high ROI and low volatility.
    - Ranked the top 10 companies for mutual fund inclusion.
4. **Investment Simulation**
    - Simulated a monthly SIP of ₹5,000.
    - Projected portfolio growth over 1, 3, 5, and 10 years.
5. **Insights & Recommendations**
    - Compared mutual fund picks with high-growth companies.
    - Provided clear, data-driven investment guidance.

---

## Key Results

### Top 10 Mutual Fund Picks (Based on ROI and Volatility)

| Rank | Company         | ROI (%) | Volatility |
|------|----------------|---------|------------|
| 1    | BAJAJ-AUTO.NS  | 22.11   | 1.55       |
| 2    | BAJAJFINSV.NS  | 19.64   | 1.37       |
| 3    | BHARTIARTL.NS  | 18.12   | 1.34       |
| 4    | DIVISLAB.NS    | 15.40   | 1.46       |
| 5    | HEROMOTOCO.NS  | 14.66   | 1.09       |
| 6    | ICICIBANK.NS   | 13.48   | 1.16       |
| 7    | BAJFINANCE.NS  | 12.80   | 1.58       |
| 8    | TITAN.NS       | 9.28    | 1.25       |
| 9    | HINDUNILVR.NS  | 8.24    | 1.21       |
| 10   | BRITANNIA.NS   | 7.71    | 0.93       |

---

### SIP Simulation Results

- **Monthly Investment:** ₹5,000
- **Projected Accumulated Value:**
  - **1 Year:** ~₹62,000
  - **5 Years:** ~₹300,000
  - **10 Years:** ~₹860,000

---

## Visualizations

> **Paste your graphs and charts below for maximum clarity.**

### Stock Price Trends of All Nifty 50 Companies

![Stock pices](https://github.com/Samsgithub9635/Mutual-Fund-Plan-Analyzing-Nifty50-High-Returns-Low-Risk_Python_and_PowerBI/blob/main/Stock%20Price.png)

### ROI Comparison 

![ROI Comparison](https://github.com/Samsgithub9635/Mutual-Fund-Plan-Analyzing-Nifty50-High-Returns-Low-Risk_Python_and_PowerBI/blob/main/ROI%20comparison.png)

### Risk Comparison 

![Risk Comparison](https://github.com/Samsgithub9635/Mutual-Fund-Plan-Analyzing-Nifty50-High-Returns-Low-Risk_Python_and_PowerBI/blob/main/Risk%20Comparison.png)

### SIP Growth Over Time

![Expected Growth](https://github.com/Samsgithub9635/Mutual-Fund-Plan-Analyzing-Nifty50-High-Returns-Low-Risk_Python_and_PowerBI/blob/main/expected%20return%20value%20for%20upcoming%2010%20years.png)

---

## Insights & Recommendations

- **Risk-Reward Balance:** Selected companies offer high returns with lower volatility, ideal for long-term, stable growth.
- **Informed Decisions:** ROI and volatility metrics enable strategic stock selection for mutual fund allocation.
- **Risk Management:** Lower volatility ensures portfolio resilience against market fluctuations.
- **Personalized Planning:** Investors can tailor SIPs to meet financial goals.
- **Scalability:** The approach can be applied to other indices for broader fund planning.
- **Stakeholder Confidence:** Clear visuals and transparent criteria build trust with clients and managers.

---

## How to Run the Project Locally

### Requirements

- Python 3.x
- Jupyter Notebook
- Required libraries: pandas, numpy, plotly, matplotlib

### Step-by-Step Guide

1. **Clone or Download the Repository**
    - Click "Code" > "Download ZIP" or use `git clone <repo-url>`.
2. **Install Dependencies**
    - Open terminal/command prompt.
    - Run:
      ```
      pip install pandas numpy plotly matplotlib
      ```
3. **Open Jupyter Notebook**
    - Navigate to the project folder.
    - Run:
      ```
      jupyter notebook
      ```
    - Open `Mutual Fund Plan.ipynb` in your browser.
4. **Run All Cells**
    - Execute each cell in order to reproduce the analysis and charts.

---

## If You Can't Run the Notebook

- **Access the PPT:**  
  The full project, including all insights, tables, and visualizations, is available in the PowerPoint file:  
  `Mutual-Fund-Plan-Analyzing-Nifty50-High-Returns-Low-Risk.pptx`
- **How to Use the PPT:**  
  - Open in PowerPoint or Google Slides.
  - Review each slide for step-by-step methodology, results, and recommendations.
  - All major findings and visuals are included for easy understanding by non-technical stakeholders.

---

## Contact

For questions or collaboration, please reach out via [samratsaha9635@gmial.com/+91 9635246955].

---

**Note:**  
This project is for educational purposes and should not be considered as financial advice. Actual investment outcomes may vary due to market conditions.

---


