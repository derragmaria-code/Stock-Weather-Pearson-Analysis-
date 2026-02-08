# 📊 MASI-Rain: Moroccan Stock vs. Rainfall Analysis (2024-2026)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

An analytical study investigating the statistical correlation between regional precipitation levels (Casablanca-Rabat axis) and the performance of key securities on the Casablanca Stock Exchange (MASI).

## 🧐 The Project Goal
Does rain drive the Moroccan stock market? This project uses data from 2024 to early 2026 to debunk (or confirm) the "agricultural pulse" theory—the idea that a wet January immediately pumps the valuations of listed companies.

## 📈 Key Findings: The "0.27" Pulse
Our analysis found a **Pearson Correlation Coefficient ($r$) of 0.2754**.

* **Positive Association:** There is a verifiable link between rainfall and stock prices.
* **Predictive Value:** Approximately **7.6%** ($R^2$) of January price variance can be explained by precipitation.
* **The 2026 Spike:** January 2026 saw an unprecedented surge in rainfall (~8.10mm daily avg), which coincided with historic highs for mining stocks like **Managem** (8,050 MAD).

## 🛠️ Data & Methodology
The study aggregates daily precipitation data (`prcp`) from two primary economic hubs:
1.  **Casablanca** (`casa2024-2026.csv`)
2.  **Rabat** (`rabat2024-2026.csv`)

**Calculation:** $r = \frac{\sum (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum (x_i - \bar{x})^2 \sum (y_i - \bar{y})^2}}$

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas matplotlib numpy
