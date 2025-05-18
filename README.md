# 🚢 Titanic-Data-Viz

This repository contains the analysis of the Titanic dataset using data visualization and clustering techniques.  
Additionally, a custom implementation of K-Means clustering from scratch is also included.

---

## 📂 Files

- **Titanic_Dataset.csv**: The raw dataset for the Titanic passengers.
- **titanic_data_analysis.py**: Python script for data analysis, visualization, and clustering.
- **README.md**: Documentation for the project.

---

## ✨ Features

- 📝 Data Cleaning and Preprocessing: Handling missing values, detecting duplicates, and binning age groups.
- 📊 Data Visualization: Histograms, scatter plots, and box plots to explore data patterns.
- 💡 Clustering Techniques: Using K-Means clustering to identify patterns among passengers.
- 🛠️ Custom K-Means from Scratch: Implementation of K-Means without using any libraries.
- 📐 Elbow Method: Determining the optimal number of clusters.

---

## 📈 Visualizations

### Histogram of Age Before and After Binning

- **Before Binning**: Shows the distribution of raw age values.
- **After Binning**: Categorizes ages into groups: Young, Adult, Middle-Aged, and Senior.
- Uses Matplotlib and Seaborn for visualization.

### Box Plot of Fare

- **Purpose**: Identifies outliers in ticket prices.
- Uses Matplotlib to create a horizontal box plot.

### Scatter Plot of Age vs Fare

- **Color-Coded by Survival**: Highlights the relationship between fare and age, distinguished by survival status.
- Uses Seaborn for better visualization.

### Clustering Visualization

- **Age vs Fare Clustering**:
  - Uses K-Means with multiple clusters to identify passenger groups.
  - Custom K-Means implementation from scratch using Euclidean distance.
- **Elbow Method Plot**:
  - Determines the optimal number of clusters.
  - Plots inertia vs the number of clusters to find the "elbow point."

---

## 💾 Installation

Ensure you have Python and the necessary libraries installed. Install dependencies using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

🛠️ Technologies Used

```bash
Python
Pandas: Data manipulation and analysis
NumPy: Numerical computations
Matplotlib: Data visualization
Seaborn: Statistical data visualization
Scikit-learn: Clustering and data preprocessing
```
