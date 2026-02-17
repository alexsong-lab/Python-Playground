# Dividend Detection Using Pandas — Financial Time Series Analysis

This project provides hands‑on experience working with real‑world financial time series data using Pandas. Students learn how to load stock price data, apply logical conditions to detect dividend events, and compute dividend amounts using differences between “Close” and “Adj Close” prices. The assignment reinforces essential data science skills such as data wrangling, exploratory analysis, and interpreting financial indicators.

---

## **Purpose**

By completing this task, students will gain experience in:

- Manipulating real‑world financial data with Pandas  
- Applying logical conditions to filter time series  
- Computing derived values such as dividends  
- Understanding the relationship between “Close” and “Adj Close” prices  
- Strengthening core data wrangling and exploratory analysis skills  

This assignment builds foundational knowledge for financial data analysis in data science.

---

## **Task: Find All Dividends**

This assignment uses Pandas to identify dividend events for six major stocks.

---

## **1. Data Preparation**

Use the historical stock data for the following six companies (from Assignment 3):

- IBM  
- MSFT  
- GOOG  
- AAPL  
- AMZN  
- FB  

Each stock has its own CSV file containing daily price information.

---

## **2. Load the Data into DataFrames**

Load each CSV file into a separate Pandas DataFrame.

You should end up with **six DataFrames**, one for each stock.

---

## **3. Understand How to Compute Dividends**

Each CSV file contains two key columns:

- **Close**  
- **Adj Close**

To detect dividend days:

1. Compute the ratio of the previous day's **Close** price to today's **Close** price.  
2. Compute the ratio of the previous day's **Adj Close** price to today's **Adj Close** price.  
3. On most days, these two ratios are equal.  
4. On dividend days, the ratios differ.  
5. The difference multiplied by today's **Close** price gives the dividend amount.

### Example (Provided in Assignment)

A dividend of approximately **$1.50** occurred on **2/8/2018**, which can be reproduced using the ratio‑difference method described above.

---

## **4. The Result**

Your final output should consist of **six DataFrames**, each containing:

- **Date**  
- **Dividend**  

Each DataFrame should include **only the rows corresponding to dividend days**, with the computed dividend amount.

---

## **Project Structure**

```
├── data/                 # Historical stock CSV files
├── notebooks/            # Jupyter notebook for dividend detection
└── README.md             # Project documentation
```

---

## **Tools and Libraries**

- Python  
- Pandas — data manipulation and time series operations  
- NumPy — numerical calculations  
- Jupyter Notebook — interactive analysis  

---

## **Learning Outcomes**

By completing this project, students will learn how to:

- Work with financial time series data  
- Detect dividend events using price adjustments  
- Apply ratio‑based logic to identify anomalies  
- Compute derived financial metrics  
- Produce clean, interpretable outputs from raw data  