# 📊 JPMorgan Chase & Co. — Quantitative Research Simulation

![JPMorgan Chase](https://img.shields.io/badge/JPMorgan%20Chase-Quantitative%20Research-blue)
![Platform](https://img.shields.io/badge/Platform-Forage-green)
![Python](https://img.shields.io/badge/Python-3.x-yellow)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Overview

End-to-end implementation of real-world quantitative finance problems completed as part of the **JPMorgan Chase & Co. Quantitative Research Virtual Experience (Forage)**.

This project simulates workflows used in investment banking and quantitative research, including:

- Time series forecasting
- Commodity pricing and simulation
- Credit risk modelling
- Portfolio segmentation using optimisation

## ⚡ Key Highlights

- Built a **price forecasting model** using regression with trend and seasonality
- Developed a **gas storage contract pricing engine** using cashflow simulation
- Implemented **credit risk models** (Logistic Regression and Random Forest)
- Computed **Expected Loss (EL = PD × LGD × EAD)**
- Designed a **dynamic programming algorithm** for optimal FICO bucketing

## 🧠 Business Impact

- Enables **data-driven pricing decisions** for commodity storage
- Improves **credit risk assessment accuracy**
- Supports **interpretable and regulator-friendly modelling**
- Optimizes **customer segmentation strategies** for lending portfolios

## 📁 Repository Structure

```text
project/
├── T1/  # Natural Gas Price Forecasting
├── T2/  # Gas Storage Contract Pricing
├── T3/  # Credit Risk Modelling
├── T4/  # FICO Score Bucketing (Dynamic Programming)
```

Each folder contains:
- Jupyter Notebook
- Dataset(s)
- Full implementation

## 🚀 Project Breakdown

### 🛢️ Task 1 — Natural Gas Price Forecasting

**Objective:**  
Forecast natural gas prices using statistical and machine learning techniques.

**Approach:**
- Time series analysis and visualization
- Feature engineering:
  - Time trend variable
  - Monthly seasonality (one-hot encoding)
- Linear Regression model
- Hybrid forecasting:
  - Interpolation (historical values)
  - Extrapolation (future prediction)

**Outcome:**
- Captures **trend and seasonal patterns**
- Provides a simple, interpretable forecasting model

### 🛢️ Task 2 — Gas Storage Contract Pricing

**Objective:**  
Build a simulation model to price gas storage contracts.

**Approach:**
- Injection and withdrawal scheduling
- Market price interpolation
- Inventory tracking over time
- Storage cost accumulation
- Cashflow-based valuation

**Pricing Logic:**
- Injection → purchase at market price
- Withdrawal → sell at market price
- Storage cost → inventory × cost × time

**Outcome:**
- Scenario-based contract pricing engine
- Supports trading strategy evaluation and profitability analysis

### 🏦 Task 3 — Credit Risk Modelling

**Objective:**  
Estimate probability of default and expected loss.

**Approach:**
- Data preprocessing and cleaning
- Feature scaling using StandardScaler
- Models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluation using ROC-AUC

**Risk Metric:**

Expected Loss (EL) = PD × LGD × EAD

**Example Output:**
- Probability of Default: 12%
- Expected Loss: $1,080

**Outcome:**
- Borrower-level risk scoring system
- Model comparison framework

### 📊 Task 4 — FICO Score Bucketing (Dynamic Programming)

**Objective:**  
Segment borrowers into optimal credit risk buckets.

**Approach:**
- Sort FICO scores
- Prefix sum optimization
- Dynamic programming for optimal segmentation
- Maximize log-likelihood objective

**Outcome:**
- Data-driven credit score segmentation
- Clear mapping between score ranges and default risk

## 🧠 Key Skills Demonstrated

- Time series forecasting
- Financial simulation modelling
- Credit risk modelling (PD, LGD, EAD, EL)
- Machine learning classification
- Dynamic programming optimisation
- Financial feature engineering

## 🛠️ Tech Stack

- Python (pandas, numpy)
- scikit-learn
- matplotlib
- statsmodels (basic use)
- Jupyter Notebook

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/dharmesh9/jpmorgan_forage_job_simulation.git
cd jpmorgan_forage_job_simulation
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn statsmodels jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run projects

Open and run notebooks inside:

- `T1/`
- `T2/`
- `T3/`
- `T4/`

## 📌 Notes

- Models are **prototype implementations**, not production systems
- No advanced ARIMA/SARIMAX used
- Storage pricing uses rule-based simulation
- FICO bucketing uses dynamic programming
- All datasets are included in the repository

## 🎯 What This Project Demonstrates

- Translating financial problems into computational models
- Building end-to-end quantitative pipelines
- Applying machine learning to credit risk analysis
- Designing simulation-based pricing systems
- Using optimisation techniques for segmentation

## 👨‍💻 Author

**Dharmesh**  
GitHub: https://github.com/dharmesh9

## ⭐ Acknowledgement

Completed as part of the **JPMorgan Chase & Co. Quantitative Research Virtual Experience (Forage)**.
