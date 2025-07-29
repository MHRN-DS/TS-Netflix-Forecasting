# Time Series Analysis: Netflix Forecasting

This project explores the modeling and forecasting of **Netflix stock prices** using classical and robust statistical approaches. It combines **time series models (ARIMA, ARIMAX)** with **Gradient Boosting Regression (GBR)** using various loss functions (Gaussian, Laplace, Pseudo-Huber) to analyze and predict stock behavior over time.

> **Grade received: 30/30**  
> **Contributors**: [@MaxHorn](https://github.com/MHRN-DS), [@MikhailIsakov](https://github.com/Mishlen337), [@LennartBredthauer](https://github.com/Lenny945)  
> **University of Padova, Business, Economic and Financial Data – July 2025**  
> Supervisor: Prof. Dr. Mariangela Guidolin

---

## Overview

In this project, we analyzed the historical stock prices of **Netflix (NFLX)** to explore the effectiveness of various forecasting techniques. The project combines:

- **Exploratory Data Analysis (EDA)** of stock price time series  
- **ARIMA and ARIMAX models** to capture trend and seasonal patterns  
- **Gradient Boosting Regression (GBR)** using three loss functions:  
  - Gaussian  
  - Laplace  
  - Pseudo-Huber  

The performance of each model was evaluated using forecast accuracy and visual diagnostics.

---

## Project Structure

```
.
├── Netflix_Stock_Price_Analysis.pdf     # Final project report (graded 30/30)
├── EDA_and_ARIMA.Rmd                    # Exploratory data analysis + ARIMA model
├── Arima_and_Arimax.Rmd                 # ARIMA vs. ARIMAX comparison
├── GBR-Gaussian.Rmd                     # GBR with Gaussian loss
├── GBR-Laplace.Rmd                      # GBR with Laplace loss
├── GBR-Pseudo-Huber.Rmd                 # GBR with Pseudo-Huber loss
```

---

## How to Run

1. Open each `.Rmd` file in **RStudio**.
2. Ensure required R packages are installed (see below).
3. Knit the files to HTML or PDF to generate visual outputs.

---

## Datasets Used

- Historical Netflix, Disney, Amazon and WarnerBros Discovery stock prices retrieved via financial APIs or CSV from Yahoo Finance

---

## Key Features

- Robust comparison of ARIMA and ARIMAX models
- Application of different regression losses
- Visual interpretation of model residuals and forecast intervals
- Evaluation of model sensitivity to noise and outliers

---

## Requirements

Make sure to install the following R packages:

```r
install.packages(c("forecast", "tseries", "ggplot2", "zoo", "MASS"))
```

Some parts of GBR may use additional statistical libraries depending on your R setup.

---

## License

This project is intended for academic reference only.  
Unauthorized reuse or modification is not permitted.