# 📊 Employee Performance Analysis using Python

This project performs **statistical and mathematical analysis on employee performance data** using Python libraries such as **Pandas, NumPy, Matplotlib, Seaborn, and SciPy**.

The goal of this notebook is to understand employee salary patterns, promotion probability, performance distribution, and vector-based analysis of employee work attributes.

---

# 📁 Dataset

The dataset used in this project is:

**employee_performance.csv**

Example columns in the dataset:

* Employee_ID
* Department
* Salary
* Projects_Completed
* Working_Hours
* Performance_Score
* Promotion_Status

---

# 🧰 Libraries Used

The following Python libraries are used in this project:

* **Pandas** → Data analysis and manipulation
* **NumPy** → Mathematical calculations and vector operations
* **Matplotlib** → Data visualization
* **Seaborn** → Statistical plots
* **SciPy** → Gaussian distribution and statistical functions

Install required libraries using:

```
pip install pandas numpy matplotlib seaborn scipy
```

---

# 📑 Project Steps

## Step 1 — Import Libraries and Load Dataset

The dataset is loaded using Pandas and the first few rows and dataset information are displayed.

## Step 2 — Measures of Central Tendency

Calculate:

* Mean Salary
* Median Salary
* Mode Salary

These values help understand the **average salary distribution**.

---

## Step 3 — Measures of Dispersion

Compute:

* Variance
* Standard Deviation

For the **Projects Completed** column to measure how spread the data is.

---

## Step 4 — Probability of Promotion

Calculate the probability that an employee gets promoted:

[
P(Promotion) = \frac{\text{Number of Promoted Employees}}{\text{Total Employees}}
]

---

## Step 5 — Contingency Table

Create a **cross-tabulation table** between:

* Department
* Promotion Status

This helps analyze promotion patterns across departments.

---

## Step 6 — Conditional Probability

Calculate the probability of promotion **given that performance score is greater than 80**.

[
P(Promotion | Performance > 80)
]

---

## Step 7 — Histogram with Gaussian Distribution

A histogram of **Performance Score** is plotted and a **Gaussian (Normal) Distribution Curve** is fitted over the data.

This helps determine if the performance scores follow a **normal distribution**.

---

## Step 8 — Skewness and Kurtosis

Calculate:

* **Skewness** → Measures asymmetry of the salary distribution
* **Kurtosis** → Measures how heavy the tails of the distribution are

---

## Step 9 — Q-Q Plot

A **Quantile-Quantile (Q-Q) Plot** is used to compare the distribution of **Projects Completed** with a **normal distribution**.

If the points lie on a straight line, the data is approximately normal.

---

## Step 10 — Vector Representation

Employee work attributes are represented as vectors:

```
[Projects_Completed, Working_Hours]
```

Example:

```
v1 = [projects, hours]
```

---

## Step 11 — Dot Product

The dot product between two employee vectors is calculated:

```
dot_product = np.dot(v1, v2)
```

This helps measure **similarity between work patterns**.

---

## Step 12 — Vector Norms

Two types of norms are calculated:

### Norm-1 (Manhattan Distance)

```
np.linalg.norm(v1, ord=1)
```

### Norm-2 (Euclidean Distance)

```
np.linalg.norm(v1)
```

---

## Step 13 — Angle Between Vectors

The angle between two employee vectors is computed using:

```
cosθ = (v1 · v2) / (||v1|| ||v2||)
```

This helps understand **directional similarity of employee work metrics**.

---

# 📊 Visualizations Included

The notebook includes:

* Histogram with Gaussian Curve
* Q-Q Plot
* Statistical summaries

---

# 🎯 Learning Objectives

This project demonstrates concepts from:

* Statistics
* Probability
* Data Visualization
* Linear Algebra
* Data Analysis with Python

---

# 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/repository-name.git
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn scipy
```

3. Run the notebook

```
jupyter notebook
```

Open the notebook and run all cells.

---

# 👩‍💻 Author

**Disha Lukhi**
AI • ML • Data Science Student

---

# ⭐ If you like this project

Give this repository a **star ⭐ on GitHub**.
