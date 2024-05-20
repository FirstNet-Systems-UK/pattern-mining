# Task 1: Product Orders

This repository contains the work for analyzing store sales data to discover interesting association rules and multilevel association rules. The tasks are divided into data preparation, mining association rules, and mining multilevel association rules.

## Dataset

The dataset `store.csv` contains tabular data about store sales. Each `Order.ID` determines which rows belong to the same order, indicating which products were bought together.

## Task Breakdown

### a. Data Preparation (10 Points)

1. **Familiarize with the Dataset:**
   - Load the dataset and understand its structure and contents.

2. **Data Cleaning:**
   - Identify and document any data quality issues such as missing values, duplicate records, or inconsistencies.
   - Perform necessary data cleaning to address these issues.

3. **Transformation for Association Rule Mining:**
   - Choose a suitable package for association rule mining (e.g., `arules` in R, `mlxtend` in Python, or KNIME).
   - Transform the cleaned dataset into the required format for association rule mining.

### b. Mining Association Rules (20 Points)

1. **Discover Association Rules:**
   - Determine appropriate support and confidence levels. Justify these choices based on the dataset characteristics.
   - Use an algorithm/package of your choice to find frequent itemsets.
   - Derive at least one interesting association rule.

2. **Detailed Evaluation:**
   - Analyze the contingency table for the rule.
   - Compute and interpret the rule’s metrics: confidence, support, lift, Kulczynski coefficient, and imbalance ratio.

### c. Mining Multilevel Association Rules (20 Points)

1. **Use Category and Sub-Category:**
   - Utilize the `Category` and `Sub.Category` attributes to discover multilevel association rules.

2. **Redundancy Check and Justification:**
   - Check for redundancy in the discovered rules.
   - Justify why the discovered rules are interesting and meaningful.

## Packages and Tools

You may use one of the following tools/packages for the tasks:
- **R:** `arules` package
- **Python:** `mlxtend` package
- **KNIME:** Data preparation and analysis nodes

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/product-orders-analysis.git
   cd product-orders-analysis
   ```

2. **Setup the environment:**
   - For R, install the `arules` package:
     ```R
     install.packages("arules")
     ```
   - For Python, install the `mlxtend` package:
     ```bash
     pip install mlxtend
     ```

3. **Load and clean the data:**
   - Follow the data preparation steps to clean and transform the dataset.

4. **Run the association rule mining:**
   - Use the chosen package/tool to mine association rules and evaluate them.

5. **Analyze multilevel association rules:**
   - Use the `Category` and `Sub.Category` attributes to find and justify multilevel association rules.

## Documentation

Ensure all steps, findings, and justifications are well-documented. This includes:
- Data cleaning process and identified issues.
- Chosen support and confidence levels with justification.
- Detailed evaluation of at least one association rule.
- Analysis of multilevel association rules with redundancy checks and justifications.

## References

- [arules package documentation](https://cran.r-project.org/web/packages/arules/arules.pdf)
- [mlxtend documentation](http://rasbt.github.io/mlxtend/)
- [KNIME documentation](https://www.knime.com/documentation)

---

Feel free to raise issues or contribute to this project. Happy mining!
