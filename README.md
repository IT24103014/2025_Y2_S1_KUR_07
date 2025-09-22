# AI_ML_GroupProject-

# Overview
This project is a group assignment for an AI & ML module, focused on building a machine learning model to predict lung cancer using a publicly available dataset. We preprocess the data using six key techniques: handling missing values, encoding categorical variables, scaling features, handling outliers, feature engineering, and handling duplicate values. Each preprocessing step includes Exploratory Data Analysis (EDA) visualizations to illustrate the impact on the dataset.

The project is implemented in Python using Google Colaboratory (Colab). After preprocessing, we train and evaluate a machine learning model (e.g., logistic regression, random forest etc.). The goal is to demonstrate data preprocessing best practices and their role in improving model performance for healthcare-related predictions.

Key objectives:

-Clean and prepare the dataset for modeling.
-Visualize data transformations through EDA.
-Train a predictive model and evaluate its accuracy.
-Collaborate as a team, with each member handling one preprocessing task.

This repository contains Google Colab notebooks for each preprocessing step and all associated visualizations.

# Dataset Details
We used the Lung Cancer Dataset from Kaggle. This dataset contains information on patients' health attributes and whether they have lung cancer.

-Size: Approximately 890000 rows and 17 columns.
-Features: Includes categorical and numerical variables such as age, gender, smoking history, chronic diseases (e.g., asthma, allergies) and the target variable (Survied from Lung Cancer: Yes/No).
-Target Variable: Binary classification (e.g., 1 for cancer, 0 for no cancer).
-Source: [Kaggle Link (or your source URL)](https://www.kaggle.com/datasets/khwaishsaxena/lung-cancer-dataset).
-License: CC BY-NC-SA 4.0.
-Challenges: The dataset may contain missing values, imbalances, outliers, and categorical features requiring encoding.
-EDA visualizations (e.g., histograms, box plots) are included in the notebooks to show data distribution before and after each preprocessing step.


# Group Member Roles
Our team consists of 6 members, each responsible for one preprocessing technique. Contributions include implementing the technique in Python, creating EDA visualizations, and documenting the process in a dedicated Google Colab notebook section.

-Gunawardhana M.D.K   (IT24103005 ): Handling missing values (e.g., imputation using mean/median or dropping rows).
-Abeysinghe J.H.C.M   (IT24103014  ): Encoding categorical variables (e.g., one-hot encoding or label encoding for features like gender or smoking status).
-Karunanayake K.M.C.N   (IT24103084 ): Scaling features (e.g., using StandardScaler or MinMaxScaler for numerical features).
-Ransith K.A.K   (IT24103049  ): Handling outliers (e.g., using IQR method or Z-score to detect and remove/cap outliers).
-Rajamanthree R.M.K.V   (IT24102935  ): Handling duplicate values (e.g., identifying and removing duplicates based on key columns).
-Ahangama A.V.D.S   (IT24102922 ): Feature Selection (e.g., Select a subset of the original features by using SelectKBest method).

# Requirements
-Python 3.8+
-Libraries:
-pandas
-numpy
-scikit-learn
-matplotlib
-seaborn
-jupyter (for local running)

# How to Run the Code
This project is designed to run on Google Colaboratory for easy collaboration, but it can also be run locally with Jupyter Notebook.

1. Open Google Colab: Go to colab.research.google.com.
2. Upload the notebooks: From the repository, download the .ipynb files and upload them to Colab, or connect directly to GitHub.
3. Load the dataset: Upload the lung_cancer.csv file to your Colab session or load it from a URL (e.g., via pandas read_csv).
4. Run the notebooks: Execute cells sequentially. Start with individual preprocessing notebooks, then run final_model_training.ipynb for the complete pipeline.
5. View visualizations: EDA plots will render inline in Colab.
