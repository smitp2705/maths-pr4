# Probability Distribution and Spread Analysis Project

A Python-based data analysis project that explores probability distributions and spread analysis using an e-commerce transaction dataset.

---

## Objective

Understand and apply core statistical concepts — probability distributions, normality testing, and data transformation — on real transaction data.

---

## Dataset

**File:** `spread_locator_dataset - spread_locator_dataset.csv.csv`

| Column | Description |
|---|---|
| `transaction_id` | Unique transaction identifier |
| `customer_id` | Customer identifier |
| `transaction_amount` | Value of the transaction |
| `transaction_date` | Date of the transaction |
| `transaction_count` | Number of transactions |
| `region` | Geographic region |
| `transaction_status` | Success or failure status |

---

## Requirements

Install dependencies with:

```bash
pip install pandas numpy scipy statsmodels matplotlib seaborn
```

---

## Project Structure

```
├── probability_distribution_project.ipynb   # Main notebook
├── spread_locator_dataset.csv               # Dataset
└── README.md
```

---

## Topics Covered

| Section | Description |
|---|---|
| **Bernoulli Distribution** | Models transaction success/failure probability |
| **Binomial Distribution** | Counts successes across multiple trials |
| **Poisson Distribution** | Models transaction count frequency |
| **Log-Normal Distribution** | Fits skewed transaction amount data |
| **Power Law Distribution** | Identifies rare high-value transactions |
| **Q-Q Plot** | Tests whether data follows a normal distribution |
| **Box-Cox Transformation** | Reduces skewness to stabilize variance |
| **Z-Score Analysis** | Detects outliers in transaction amounts |
| **PDF & CDF** | Visualizes probability density and cumulative probability |

---

## How to Run

1. Clone or download this repository.
2. Place the dataset CSV in the same directory as the notebook (or update the file path in the notebook).
3. Open the notebook:
   ```bash
   jupyter notebook probability_distribution_project.ipynb
   ```
4. Run all cells in order.

---

## Key Outputs

- Bernoulli and Poisson distribution plots
- Log-normal fit on transaction amounts
- Q-Q plot for normality check
- Box-Cox transformed distribution histogram
- Z-scores for outlier detection
- PDF and CDF curves for transaction amounts

---

## Conclusion

- Bernoulli distribution captures success/failure of transactions.
- Poisson distribution models transaction count behavior.
- Log-normal distribution fits the skewed transaction amounts.
- Box-Cox transformation helps normalize skewed data.
- Z-score analysis flags unusual transaction values.
