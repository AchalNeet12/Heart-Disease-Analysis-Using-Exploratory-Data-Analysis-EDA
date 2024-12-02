# Heart Disease Analysis Using Exploratory Data Analysis (EDA)
- - -

## 📋 Project Overview:

The primary aim of a heart disease analysis project using Exploratory Data Analysis (EDA) is to gain valuable insights into the factors that contribute to heart disease and to identify potential risk factors. By understanding these factors, healthcare professionals and researchers can develop effective strategies for prevention, early detection, and treatment of heart disease.

## 🔍 Dataset:

The dataset used in this project is the **Heart Disease Analysis**, which consists of several  features:
- age : age in years
  - sex : (1 = male; 0 = female)
  - cp : chest pain type
  - trestbps : resting blood pressure (in mm Hg on admission to the hospital)
  - chol : serum cholestoral in mg/dl
  - fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
  - restecg : resting electrocardiographic results
  - thalach : maximum heart rate achieved
  - exang : exercise induced angina (1 = yes; 0 = no)
  - oldpeak : ST depression induced by exercise relative to rest
  - slope : the slope of the peak exercise ST segment
  - ca : number of major vessels (0-3) colored by flourosopy
  - thal : 3 = normal; 6 = fixed defect; 7 = reversable defect
  - target : 1 or 0
The target variable indicates to the presence of heart disease in the patient.
It is integer valued as it contains two integers 0 and 1 - (0 stands for absence of heart disease and 1 for presence of heart disease)

## 🛠️ Project Components:

1.Data Collection and Cleaning:
- Data Sources: Gather relevant data from various sources like medical records, clinical trials, or public health databases.
- Data Cleaning:
  Handle missing values (imputation or removal).
  Address outliers (capping, flooring, or removal).
  Correct inconsistencies and errors.
2.Exploratory Data Analysis:
- Univariate Analysis:
  Statistical Summary: Calculate measures like mean, median, mode, standard deviation, quartiles, etc.
  Data Visualization: Use histograms, box plots, and density plots to visualize the distribution of each feature.
- Bivariate Analysis:
  Correlation Analysis: Calculate correlation coefficients (Pearson, Spearman) to assess the relationship between features.
  Cross-Tabulations: Analyze categorical variables to identify associations.
  Data Visualization: Use scatter plots, bar charts, and heatmaps to visualize relationships.
- Multivariate Analysis:
  Principal Component Analysis (PCA): Reduce the dimensionality of the dataset to identify the most important features.
  Cluster Analysis: Group similar patients based on their characteristics to identify distinct subgroups.
3.Data Visualization:
- Visualize Data Distributions: Use histograms, box plots, and density plots.
- Explore Relationships: Use scatter plots, line charts, and correlation matrices.
- Identify Outliers: Use box plots and scatter plots.
- Visualize Categorical Data: Use bar charts.

##  🤖 Technologies Used:

Pandas & NumPy: For data manipulation and analysis.
Matplotlib and Seaborn: For data visualization
EDA: - Understanding data: Get to know your data, its structure, and its variables.
     - Finding patterns: Identify trends, relationships, and anomalies.
     - Preparing for modeling: Clean data, handle missing values, and select relevant features.
     - Making informed decisions: Guide further analysis, model building, and insights.
  







