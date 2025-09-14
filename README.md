# Hypo\_Testing.py

A collection of Jupyter notebooks illustrating different types of hypothesis testing in statistics: Z-test, T-test, Chi-square test, ANOVA.

---

## Contents

| File                | Description                                                                                   |
| ------------------- | --------------------------------------------------------------------------------------------- |
| `Z_test.ipynb`      | Notebook covering how to perform a Z-test: when to use it, assumptions, examples.             |
| `T_test.ipynb`      | Notebook covering the T-test: types (one-sample, independent, paired), assumptions, examples. |
| `Chi_sq_test.ipynb` | Notebook on Chi-square tests: goodness-of-fit, independence, examples.                        |
| `Annova_test.ipynb` | Notebook on ANOVA (analysis of variance): one-way ANOVA, assumptions, examples.               |

---

## Features

* Step-by-step explanation of statistical hypothesis testing methods.
* Examples with sample datasets.
* Visualizations & checking assumptions (normality, independence, etc.).
* Comparison between different test types & when each is appropriate.

  

## When to Use Each Test

| Test       | Use Case                                                              | Key Assumptions                                                 |
| ---------- | --------------------------------------------------------------------- | --------------------------------------------------------------- |
| Z-test     | When population variance is known, or sample size is large (n ≥ \~30) | Normality of distribution or large sample size                  |
| T-test     | When population variance is unknown; smaller samples                  | Normality (or near), independent samples (if appropriate)       |
| Chi-square | Categorical data; independence or goodness-of-fit                     | Sufficient expected counts in categories, independence          |
| ANOVA      | Comparing means across more than two groups                           | Homogeneity of variances, independence, normality within groups |
