# Python Data Analysis with Pandas

A hands-on repository for learning and practicing **Python data analysis using Pandas**, with practical exercises involving data cleaning, transformation, manipulation, joining, and analysis of real-world-style messy datasets.

This repository contains Jupyter Notebook practice along with CSV and Excel datasets used to perform different data analysis operations.

---

##  About the Repository

This repository was created as a practical learning resource while exploring Python libraries used in **Data Analysis and Machine Learning**.

The main focus is on understanding how to work with structured and messy datasets using **Pandas**, including:

* DataFrame and Series operations
* Data inspection and exploration
* Handling missing values
* Detecting and removing duplicates
* Cleaning inconsistent data
* Data transformation
* Filtering and selecting data
* Grouping and aggregation
* Sorting and ranking
* Combining and joining datasets
* Working with CSV and Excel files
* Exploratory data analysis
* Creating and working with pivot tables

The repository also contains practice datasets that simulate real-world data cleaning and analysis scenarios.

---

## Technologies & Libraries

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**
* **CSV**
* **Excel**

---

##  Repository Contents

| File                        | Description                                                                                             |
| --------------------------- | ------------------------------------------------------------------------------------------------------- |
| `Practise_Section_pd.ipynb` | Main Pandas practice notebook containing data manipulation, cleaning, analysis, and practical exercises |
| `messy_customers.csv`       | Customer dataset containing messy/inconsistent data for cleaning and analysis                           |
| `messy_orders.csv`          | Orders dataset used for data manipulation and analysis                                                  |
| `messy_order_items.csv`     | Order-items dataset used for working with related data                                                  |
| `messy_products.csv`        | Product dataset used for analysis and dataset relationships                                             |
| `final_data_messy.csv`      | Processed/combined dataset generated during the practice                                                |
| `joined_data_messy.csv`     | Dataset created by joining multiple related datasets                                                    |
| `final_messy.xlsx`          | Excel version of processed data                                                                         |
| `result_messy.xlsx`         | Excel output containing analysis/results                                                                |

---

## Topics Practiced

### 1. DataFrame & Series

Working with Pandas' fundamental data structures.

* Creating DataFrames
* Selecting rows and columns
* Accessing individual values
* Understanding indexes
* Adding and modifying columns

### 2. Data Exploration

Understanding a dataset before performing analysis.

```python
df.head()
df.tail()
df.info()
df.describe()
df.shape
df.columns
```

### 3. Data Cleaning

Practical handling of common data-quality problems.

* Missing values (`NaN`)
* Duplicate records
* Inconsistent values
* Incorrect column names
* Data type issues
* Unclean categorical data

Examples include:

```python
df.isnull()
df.fillna()
df.dropna()
df.drop_duplicates()
```

### 4. Data Selection & Filtering

Selecting specific records based on conditions.

```python
df[df["column"] > value]
df.loc[]
df.iloc[]
```

### 5. Data Transformation

Manipulating existing data to create useful information.

* Creating new columns
* Modifying existing columns
* Applying functions
* Renaming columns
* Sorting data

### 6. Grouping & Aggregation

Performing calculations on groups of data.

```python
df.groupby()
df.mean()
df.sum()
df.count()
df.max()
df.min()
```

### 7. Pivot Tables

Creating summarized views of datasets using Pandas.

```python
pd.pivot_table()
```

### 8. Combining Datasets

Working with multiple related datasets using:

* `merge()`
* `join()`
* `concat()`

This is demonstrated using customer, order, product, and order-item datasets.

### 9. CSV & Excel Data

Reading and writing data using Pandas.

```python
pd.read_csv()
pd.read_excel()

df.to_csv()
df.to_excel()
```

---

## 🧹 Practical Data Cleaning Workflow

The repository follows a practical data-analysis workflow:

```text
Raw / Messy Data
       ↓
Data Inspection
       ↓
Data Cleaning
       ↓
Missing Value Handling
       ↓
Duplicate Detection
       ↓
Data Transformation
       ↓
Dataset Joining
       ↓
Data Analysis
       ↓
Processed / Final Dataset
```

This workflow represents common steps used when preparing data for **Data Analysis and Machine Learning**.

---

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/pooniaaryan/Python-libraries-Numpy-pandas-matplotlib-seaborn.git
```

### 2. Navigate to the project

```bash
cd Python-libraries-Numpy-pandas-matplotlib-seaborn
```

### 3. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Practise_Section_pd.ipynb
```

and run the notebook cells.

---

##  Learning Objectives

Through this repository, I am building practical understanding of:

* Python-based data analysis
* Pandas DataFrames and Series
* Data cleaning and preprocessing
* Missing-value handling
* Duplicate detection
* Dataset transformation
* Data aggregation
* Dataset merging and joining
* CSV and Excel data processing
* Exploratory data analysis

These concepts form an important foundation for **Data Science, Machine Learning, and AI/ML projects**.


---

## 👨‍💻 Author

**Aryan Poonia**

B.Tech CSE (AI & ML)
Guru Jambheshwar University of Science & Technology, Hisar

GitHub: [@pooniaaryan](https://github.com/pooniaaryan)

---

## ⭐ Purpose

This repository represents my hands-on learning and practice with Python's data-analysis ecosystem and serves as a foundation for further work in **Data Science, Machine Learning, and Artificial Intelligence**.
