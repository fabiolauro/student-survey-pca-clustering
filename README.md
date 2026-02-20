# Data Analysis on the Young Student Survey #

Overview
----------
This project presents an exploratory data analysis, dimensionality reduction and clustering study on the Young People Survey dataset, using Principal Component Analysis (PCA) to uncover latent patterns in students' preferences, behaviors, and characteristics, and k-means clustering to identify students/clients' profiles that embody such characteristics.

The main objective is to reduce the dimensionality of a high-dimensional survey dataset and identify interpretable latent factors that explain the variability in student responses.

This project demonstrates skills in:

Exploratory Data Analysis (EDA)

Data preprocessing and cleaning

Dimensionality reduction using PCA

Statistical interpretation of latent variables

Clustering through K-means

Identification of typical customer profiles

Data visualization

Python-based data analysis workflows

Dataset
-------------
The dataset contains survey responses from young individuals aged 15–30, covering multiple aspects of their lives including:

Music preferences

Movie preferences

Hobbies and interests

Personality traits

Lifestyle and habits

Social and behavioral patterns

Dataset characteristics:

~1000 observations

~150 variables

Numerical and categorical features

Missing values requiring preprocessing

Such datasets are commonly used to identify hidden behavioral patterns and reduce dimensional complexity using statistical techniques like PCA .

Objectives
------------
The main goals of this project are:

Clean and preprocess a high-dimensional survey dataset

Perform exploratory data analysis to understand structure and distributions

Apply Principal Component Analysis (PCA) to reduce dimensionality

Identify the most important latent components

Interpret principal components in terms of student behavior and preferences

Visualize variance explained and component structure

Methodology
-------------
The project follows a structured data science workflow:

### 1. Data Loading and Preprocessing

Loading dataset using pandas

Handling missing values

Selecting relevant numerical features

Standardizing variables for PCA

### 2. Exploratory Data Analysis

Summary statistics

Distribution analysis

Correlation analysis

Data visualization

### 3. Principal Component Analysis

Standardization of features

Computation of principal components

Explained variance analysis

Scree plot visualization

Interpretation of component loadings

### 4. Interpretation

Identification of dominant latent factors

Behavioral interpretation of components

Dimensionality reduction assessment

### 5. K-Means Clustering

The K-Means algorithm was applied for multiple values of k:

Tested range: k = 3 to k = 10

Random state fixed for reproducibility

### 6. Cluster Evaluation

Cluster quality was evaluated using the:

Silhouette coefficient

Visual inspection of cluster separation

Centroid positions in PCA space

Key Results
---------------
The analysis demonstrates that:

A small number of principal components capture a significant portion of the total variance

High-dimensional survey data can be effectively compressed into a lower-dimensional representation

Latent components reveal underlying behavioral and preference patterns among students

PCA provides meaningful structure useful for clustering, segmentation, or predictive modeling



Tech Stack
---------------
Languages and tools used:

Python

Jupyter Notebook

Main libraries:

pandas

numpy

matplotlib

scikit-learn

How to Run
----
Clone the repository:

git clone https://github.com/fabiolauro/Data-analysis-on-the-Young-Student-Survey.git
cd Data-analysis-on-the-Young-Student-Survey

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

Run the notebook:

jupyter notebook HWpca_Lauro_Martellone.ipynb

Skills Demonstrated
-----
This project highlights competencies relevant for Data Science and Business Analytics roles:

Statistical analysis

Dimensionality reduction

Data preprocessing

Python data stack proficiency

Analytical thinking

Interpretation of complex datasets

Data visualization

K-Means clustering

Cluster evaluation using silhouette score


Author
-----
Fabio Lauro
MSc Mathematical Engineering — Statistics and Optimization
Politecnico di Torino

GitHub: https://github.com/fabiolauro

