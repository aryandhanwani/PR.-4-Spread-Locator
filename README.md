# Spread Locator – Statistical Distribution Analysis

## Project Overview
This project analyzes transaction data to understand patterns and behaviors using statistical distributions and probability concepts. The goal is to determine which statistical distributions best describe the dataset and extract insights that can support decision-making.

The dataset used in this project is **spread_locator_dataset.xlsx**, which contains information about transaction amounts, counts, and transaction status.

---

# Part A – Theoretical Foundation

## Statistical Distribution
A statistical distribution describes how data values are spread across different possible values. It helps understand patterns, variability, and probabilities within a dataset.

---

## Q-Q Plot
A Q-Q (Quantile–Quantile) plot compares the distribution of the dataset with a theoretical normal distribution.  
If the points lie along a straight line, the data is normally distributed. If the points deviate from the line, the data is skewed.

---

## Discrete vs Continuous Distribution

| Type | Description | Example |
|-----|-------------|--------|
| Discrete Distribution | Values are countable integers | Number of transactions |
| Continuous Distribution | Values can take any numeric value | Transaction amount |

---

## Bernoulli Distribution
Bernoulli distribution models experiments with only two possible outcomes, such as success or failure. In this dataset, transaction status (success or failure) follows a Bernoulli distribution.

---

## Binomial Distribution
Binomial distribution models the number of successful outcomes in a fixed number of trials. It helps estimate the probability of multiple successful transactions.

---

## Log-Normal Distribution
A variable follows a log-normal distribution if the logarithm of the variable is normally distributed. Transaction amounts often follow this pattern because most transactions are small while a few are very large.

---

## Power Law Distribution
Power law distribution occurs when a small number of observations are significantly larger than the majority. This pattern is often seen in financial and transaction data.

---

## Box-Cox Transformation
Box-Cox transformation is used to reduce skewness in data and make it closer to a normal distribution. This transformation helps improve statistical analysis.

---

## Poisson Distribution
Poisson distribution models the number of events occurring within a fixed time interval, such as the number of transactions per day.

---

## Z-Score
Z-score measures how far a value is from the mean in terms of standard deviations. It helps identify unusually high or low values in a dataset.

---

## PDF and CDF
Probability Density Function (PDF) describes the likelihood of a value occurring at a specific point, while Cumulative Distribution Function (CDF) represents the probability that a variable is less than or equal to a certain value.

---

# Part B – Data Analysis

The dataset was analyzed to study transaction behavior using multiple statistical distributions and visualization techniques.

### Bernoulli Distribution
Transaction success and failure were analyzed using Bernoulli distribution to determine the probability of successful transactions.

### Binomial Distribution
Binomial distribution was used to estimate the probability of multiple successful transactions within a given number of trials.

### Poisson Distribution
Poisson distribution was applied to model the number of transactions occurring within a fixed time period.

### Q-Q Plot Analysis
A Q-Q plot was used to compare the distribution of transaction amounts with a theoretical normal distribution to check for normality.

### Log Transformation
Log transformation was applied to transaction amounts to reduce skewness and analyze whether the data follows a log-normal distribution.

### Box-Cox Transformation
Box-Cox transformation was used to further normalize the dataset and reduce skewness.

### Z-Score Analysis
Z-score analysis helped determine how far transaction amounts deviate from the average value, which can assist in identifying unusual transactions.

### PDF and CDF Analysis
Probability Density Function and Cumulative Distribution Function were analyzed to understand the probability behavior of transaction amounts.

---

# Conclusion
Transaction success follows Bernoulli and Binomial distributions, while transaction counts are well modeled by a Poisson distribution. The transaction amount data is right-skewed and best fits a log-normal distribution. These insights help understand transaction patterns and support better decision-making by identifying normal and unusual transaction behaviors.
