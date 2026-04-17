# Fetal Cardiographic Data Analysis 

##  Overview
This repository contains a Jupyter Notebook (`Assignment(5).ipynb`) dedicated to a thorough exploratory data analysis (EDA) of a `cardiographic.csv` dataset. The primary objective is to uncover insights, identify patterns, and understand the underlying structure of fetal cardiogram readings. 

By analyzing metrics such as Baseline Fetal Heart Rate (FHR), Uterine Contractions, and Decelerations, this project demonstrates how statistical summaries and visual data manipulation can be used to interpret complex medical data.

##  Dataset Dictionary
The dataset contains key medical indicators related to fetal health, including:
* **LB:** Baseline Fetal Heart Rate (FHR)
* **AC:** Accelerations in FHR
* **FM:** Fetal Movements detected
* **UC:** Uterine Contractions
* **DL / DS / DP:** Late, Short, and Prolonged Decelerations
* **ASTV / MSTV:** Abnormal and Mean Short Term Variability
* **ALTV / MLTV:** Abnormal and Mean Long Term Variability

##  Key Skills & Methodology

The analysis follows a structured, end-to-end data science workflow:

### 1. Data Cleaning & Preparation
* Loaded and inspected the dataset for structural integrity.
* Addressed missing values through appropriate imputation/deletion strategies.
* Corrected inconsistent data types.
* Detected and treated statistical outliers to ensure accurate analysis.

### 2. Statistical Summarization
* Calculated central tendencies (mean, median) and dispersion metrics (standard deviation, IQR) for all numerical variables to establish baseline distributions.

### 3. Advanced Data Visualization
* **Distributions:** Utilized histograms and boxplots to visualize the spread of numerical variables.
* **Categorical Frequencies:** Deployed bar charts to display category counts.
* **Relationship Mapping:** Created scatter plots and **correlation heatmaps** to identify highly correlated features.
* **Deep Insights:** Employed pair plots and violin plots for multi-dimensional data exploration.

### 4. Pattern Recognition & Conclusions
* Extracted meaningful correlations between variables (e.g., how uterine contractions impact FHR).
* Summarized key insights into a brief report detailing how these findings could impact medical decision-making or guide predictive modeling.

## 🛠️ Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
