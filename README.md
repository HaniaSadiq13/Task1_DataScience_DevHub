# Task 1: Exploring and Visualizing a Simple Dataset

## 🎯 Objective
Understand how to read, summarize, and visualize a dataset using Python. The **Iris dataset** is used to explore basic data analysis and visualization techniques.

## 📁 Dataset
- **Name**: Iris Dataset  
- **Source**: Built-in via Seaborn (`sns.load_dataset("iris")`)  
- **Target Variable**: `species` (Setosa, Versicolor, Virginica)

## 🛠️ Libraries Used
- `pandas` – for data loading and summarization  
- `seaborn` – for statistical visualizations  
- `matplotlib.pyplot` – for general plotting  

## 🔍 Steps Performed

### 1. Load and Inspect the Dataset
- Loaded the dataset using `sns.load_dataset("iris")`
- Displayed:
  - Dataset shape using `.shape`
  - Column names using `.columns`
  - First few rows using `.head()`

### 2. Basic Visualizations

#### ✅ Scatter Plot
- Plotted **sepal_length vs sepal_width**
- Colored by `species` to analyze relationships between different flower types

#### ✅ Histogram
- Plotted histogram of **petal_length**
- Used KDE to show the distribution shape

#### ✅ Box Plot
- Plotted **sepal_length** across different species
- Used to identify outliers and understand value spread

## 📌 Key Skills Demonstrated
- ✅ Dataset loading with Seaborn/Pandas  
- ✅ Basic dataset inspection using `.shape`, `.columns`, and `.head()`  
- ✅ Exploratory data visualization:
  - Scatter plots for correlation
  - Histograms for distribution
  - Box plots for spread and outliers
