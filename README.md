# 📊 Data Analysis with Pandas & Visualization in Colab

This repository contains a Google Colab notebook demonstrating fundamental data manipulation, cleaning, and visualization techniques using the **Pandas**, **Matplotlib**, and **Seaborn** libraries.

---

## 🚀 Key Learning Objectives

The core of this project is to practice essential skills for any data analyst or data scientist working with tabular data:

| Concept | Purpose |
| :--- | :--- |
| **Import Libraries** | Setting up the working environment by importing Pandas, Matplotlib, and Seaborn. |
| **Data Ingestion** | Reading data from different file types, specifically **CSV** (`pd.read_csv`) and **Excel** (`pd.read_excel`). |
| **Data Selection** | Accessing and filtering specific rows and columns using **`loc`** and **`iloc`**. |
| **Data Subsetting** | Creating new DataFrames based on filtering criteria. |
| **Data Aggregation** | Summarizing data using the powerful **`groupby()`** function. |
| **Visualization** | Creating meaningful plots (like histograms and bar charts) using Matplotlib and Seaborn. |

---

## 🛠️ Essential Techniques Covered

### 1. Library Imports

The notebook begins by importing the necessary libraries under their common aliases: `pandas` as `pd`, `matplotlib.pyplot` as `plt`, and `seaborn` as `sns`.

### 2. Reading Data Files

The project demonstrates reading data into a DataFrame using both `pd.read_csv()` for Comma Separated Values and `pd.read_excel()` for Excel spreadsheets, often specifying a particular sheet name.

### 3. Data Selection and Subsetting

* **Subsetting Columns:** Demonstrated by selecting a list of columns (e.g., 'genre' and 'popularity') from the main DataFrame.
* **`loc` (Label-based indexing):** Used for filtering rows based on a condition, such as selecting all tracks where popularity is greater than 80.
* **`iloc` (Integer-based indexing):** Used for selecting data by its numerical position (row and column index).

### 4. Grouping and Aggregation

The **`groupby()`** function is used to calculate summary statistics. An example includes grouping the data by a categorical column (like 'genre') and calculating the mean of a numerical column (like 'popularity') for each group.

### 5. Visualization

The notebook provides examples of creating visualizations:

* **Matplotlib:** Used for generating basic charts, such as a bar chart to visualize the average popularity across different genres.
* **Seaborn:** Used for advanced statistical plotting, such as a histogram to visualize the distribution of a single variable, like 'energy'.

---

## 🔗 How to Run the Notebook

1.  Access the Colab notebook associated with this repository.
2.  Upload any required sample data files (e.g., `spotify_features.csv`) to your Colab environment.
3.  Execute the cells sequentially to run the data processing steps and generate the visualizations.
