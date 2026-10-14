# Data Exploration and Visualization: Capstone Project

Complete Capstone Project covering **Units 1 to 5** of Data Exploration and Visualization using the **UCI Heart Disease dataset**, featuring exploratory analysis, advanced Matplotlib/Seaborn plots, statistical analysis, PCA, and machine learning models.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Bhaavana-Kanagaraj/Dev_Capstone_project/blob/main/notebooks/Dev_capstone_project.ipynb)

---

## Quick Links

| Resource | Link |
|---|---|
| Notebook | [`notebooks/Dev_capstone_project.ipynb`](notebooks/Dev_capstone_project.ipynb) |
| Dataset (CSV) | [`data/heart.csv`](data/heart.csv) |
| All output images | [`EDA Implementations/`](EDA%20Implementations) |

---

## Dataset

- **Source:** UCI Heart Disease dataset
- **Size:** 1025 rows x 14 columns
- **Features:** `age`, `sex`, `cp`, `trestbps`, `chol`, `fbs`, `restecg`, `thalach`, `exang`, `oldpeak`, `slope`, `ca`, `thal`
- **Target:** `target` (0 = no heart disease, 1 = heart disease)
- **Data quality:** no missing values, 723 duplicate rows (removed, leaving 302 unique records for the analysis)

---

## Project Structure

```
Dev_Capstone_project/
├── EDA Implementations/     # Output images for every unit
├── data/                    # Heart disease CSV
├── notebooks/               # Colab / Jupyter notebook
├── .gitignore
└── README.md
```

---

## Unit 1: Exploratory Data Analysis (CO1)

**Topics covered:** Data Science Process, EDA vs Classical and Bayesian analysis, Python libraries, data loading and initial inspection (missing values, duplicates, encoding, slicing), transformation techniques, grouping datasets.

### Head and Shape
![Head and Shape](EDA%20Implementations/01_head_shape.png)

### Dataset Info (Data Types and Non-Null Counts)
![Dataset Info](EDA%20Implementations/02_dataset_info.png)

### Missing and Duplicate Values
![Missing and Duplicates](EDA%20Implementations/03_missing_duplicates.png)

### Data Slicing using `loc`
![Loc Slice](EDA%20Implementations/04_loc_slice.png)

### Grouped Dataset Summary
![Grouped Summary](EDA%20Implementations/05_grouped_summary.png)

---

## Unit 2: Visualizing using Matplotlib (CO2)

**Topics covered:** Simple line plots, scatter plots, visualizing errors, density and contour plots, histograms, legends, colors, subplots, text and annotation, 3D plotting, Seaborn and Plotly.

### Simple Line Plot and Scatter Plot
![Line and Scatter](EDA%20Implementations/06_line_scatter.png)

### Error Bars and Histogram
![Error Bars and Histogram](EDA%20Implementations/07_errorbar_histogram.png)

### Density Contour (Hexbin) Plot
![Hexbin Density](EDA%20Implementations/08_hexbin_density.png)

### Subplots with Text and Annotation
![Subplots and Annotation](EDA%20Implementations/09_subplots_annotation.png)

### Three-Dimensional Plot
![3D Scatter](EDA%20Implementations/10_3d_scatter.png)

### Seaborn Count Plot and Plotly Interactive Scatter
![Seaborn and Plotly](EDA%20Implementations/11_countplot_plotly.png)

---

## Unit 3: Univariate Analysis (CO3)

**Topics covered:** Histograms, box plots, density plots, summary statistics, skewness and outliers, bar charts, pie charts, frequency tables.

### Summary Statistics, Histogram with KDE, Box Plot and Density Plot
![Summary, Histogram, Box, KDE](EDA%20Implementations/12_summary_hist_box_kde.png)

**Key findings**
- Mean age is about 54 years, and mean cholesterol is about 246.5 mg/dl.
- Cholesterol is right-skewed (skewness ≈ 1.15), with several high outliers.

### Frequency Table, Bar Chart and Pie Chart (Sex)
![Sex Bar and Pie](EDA%20Implementations/13_sex_bar_pie.png)

**Key findings**
- The dataset is about 68% male (206) and 32% female (96).

---

## Unit 4: Bivariate Analysis (CO4)

**Topics covered:** Scatter plots, Pearson and Spearman correlation, stacked and grouped bar charts, box plots and violin plots across categories.

### Age vs Max Heart Rate (with Correlation)
![Age vs Thalach](EDA%20Implementations/14_age_vs_thalach.png)

**Key findings**
- Age and maximum heart rate have a moderate negative correlation (Pearson -0.40, Spearman -0.39).

### Stacked and Grouped Bar Charts (Sex vs Target)
![Stacked and Grouped Bar](EDA%20Implementations/15_stacked_grouped_bar.png)

### Box Plot (Target vs Age) and Violin Plot (Target vs Cholesterol)
![Box and Violin](EDA%20Implementations/16_box_violin.png)

---

## Unit 5: Multivariate Analysis and Insights (CO5)

**Topics covered:** Pair plots, correlation heatmaps, grouped visualizations, dimensionality reduction (PCA), Scikit-learn for machine learning model development.

### Correlation Matrix Heatmap
![Correlation Heatmap](EDA%20Implementations/17_correlation_heatmap.png)

**Key findings**
- Max heart rate (`thalach`) has the strongest positive correlation with the target (0.42).
- Age has a negative correlation with the target (-0.22).

### Pair Plot (Scatter Matrix)
![Pair Plot](EDA%20Implementations/18_pairplot.png)

### PCA: 2D Dimensionality Reduction
![PCA Projection](EDA%20Implementations/19_pca_projection.png)

### Machine Learning Models (Scikit-learn)

<!-- Add your model names and accuracy results here, for example:
| Model | Accuracy |
|---|---|
| Logistic Regression | xx% |
| Random Forest | xx% |
-->

Model code and results are in the [notebook](notebooks/Dev_capstone_project.ipynb).

---

## Tools and Libraries

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Plotly` · `SciPy` · `Scikit-learn` · `Google Colab`

---

## How to Run

1. Click the **Open in Colab** badge at the top, or open the notebook from the `notebooks/` folder.
2. Upload `data/heart.csv` to the Colab session (or mount Google Drive).
3. Run all cells from top to bottom.

---

## Author

**Bhaavana Kanagaraj**
B.Tech Artificial Intelligence and Data Science
[GitHub](https://github.com/Bhaavana-Kanagaraj)
