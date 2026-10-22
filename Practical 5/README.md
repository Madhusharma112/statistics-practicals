📊 Practical 5 — Understanding the Two-Tailed Test

«Statistical probability calculations and two-tailed hypothesis testing using Python.»

---

🎯 Objective

To understand probability calculations using the normal distribution and apply a two-tailed Z-test to determine whether a sample mean differs significantly from a given population mean.

---

📚 Practical Overview

This practical focuses on probability estimation and hypothesis testing using Python.

The analysis includes:

- Probability above a specified value
- Probability within a given interval
- Normal distribution and Z-scores
- Standard error calculation
- Null and alternative hypotheses
- Two-tailed Z-test
- P-value and critical-value interpretation

---

📊 Dataset

The practical uses the TeachingRatings dataset for probability calculations involving teacher evaluation scores.

A separate numerical example involving regional players' points per game is used for the two-tailed Z-test.

Main Variable

Variable| Type| Description
"eval"| Numerical| Teacher evaluation score

---

🔍 Analysis Performed

1. Probability Above 4.5

The probability of a randomly selected teacher evaluation score exceeding 4.5 is estimated using the normal distribution.

Parameter| Value
Mean| 3.998
Standard deviation| 0.5549
Estimated probability| 0.183

The estimated probability is approximately 18.3%.

---

2. Probability Between 3.5 and 4.2

The probability of an evaluation score falling between 3.5 and 4.2 is calculated using the cumulative distribution function (CDF).

The formula is:

[
P(a<X<b)=\Phi(z_b)-\Phi(z_a)
]

Parameter| Value
Lower limit| 3.5
Upper limit| 4.2
Estimated probability| 0.457

The estimated probability is approximately 45.7%.

---

3. Two-Tailed Z-Test

A two-tailed Z-test is performed to determine whether the mean points scored by regional players differs from the historic population mean.

Hypotheses

- Null hypothesis (H₀): The population mean is 12.
- Alternative hypothesis (H₁): The population mean is different from 12.

Test Results

Parameter| Value
Population mean| 12
Population standard deviation| 5.5
Sample size| 36
Sample mean| 10.7
Z-statistic| -1.418
Two-tailed p-value| 0.156
Significance level| 0.05
Critical Z-values| ±1.960

Since the p-value is greater than 0.05, the null hypothesis is not rejected.

There is insufficient statistical evidence to conclude that the population mean differs from 12.

---

📈 Summary of Findings

Analysis| Result
Probability above 4.5| 18.3%
Probability between 3.5 and 4.2| 45.7%
Two-tailed Z-test| Fail to reject H₀

---

🛠️ Technologies Used

Technology| Purpose
Python| Programming language
Pandas| Data manipulation and analysis
NumPy| Numerical calculations
SciPy| Probability and statistical calculations
Jupyter Notebook| Development environment

---

💻 Implementation

Import Libraries

import pandas as pd
import numpy as np
from scipy import stats

The SciPy library is used to calculate normal distribution probabilities and perform statistical calculations for the two-tailed Z-test.

---

📁 Project Structure

Understanding-Two-Tailed-Test/
├── README.md
├── Practical 5.ipynb
└── teachingratings.csv


