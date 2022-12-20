# Medical Markers to Predict Heart Disease


**INTRODUCTION**

This is analysis for a heart disease dataset that was collected in 1988 from 4 different geographical locations and amalgulmated into one dataset of 1025 patients.

The target variable (y) is a categorical indicator confirming the presence of heart disease. 0 = no disease and 1 = disease.

There are 14 covariates as detailed below:

  1. age (in years) 
  2. sex (1=male, 0= female)
  3. cp: chest pain type (4 values)
  4. trestbps: resting blood pressure (in mm Hg on admission to hospital)
  5. chol: serum cholestoral in mg/dl
  6. fbs: fasting blood sugar > 120 mg/dl where 1=true, 0=false
  7. restecg: resting electrocardiographic results (0 = Hypertrophy 1 =            Having ST-T wave abnormality, 2 = Showing probable or definite left          ventricular hypertrophy by Estes' criteria)
  8. thalach: maximum heart rate achieved
  9. exang: exercise induced angina 1 = yes, 0 = no
  10. oldpeak: ST depression induced by exercise relative to rest
  11. slope: the slope of the peak exercise ST segment
  12. ca: number of major vessels (0-3) colored by flourosopy
  13. thal: Thalium Stress test Result 0 = normal 1 = fixed defect; 2 =             reversable defect

The original scientific source of the data is unknown but was originally taken from https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset?select=heart.csv and saved into my local harddrive.

All names and identification of patients have been removed from the dataset.

**OBJECTIVES**

To visually explore the dataset and to determine if there are variables that can be used within a medical environment to provide a prediction as to whether a patient is likely to have heart disease. 

**TO RUN**

The code has been written with descriptive markdowns in a Python Notebook. The dataset being analysed it Heartdata.csv.

1. Download the Heartdata.pynb script, Heartdata.csv and Project notes in this repository.

2. Explore the dataset and notes above to familiarise yourself with the data.

3. Open the python notebook `Heartdata.pynb` in your preferred GUI (I used Anaconda Navigator and Jupyter lab) and run the script line by line. The code is clearly annotated so you can follow the process and reasoning throughtout. 

4. By following the above you will be able to re-run the analysis and machine learning pipeline model to discover if any of the x variables can be considered as reliable predictors for heart disease. 

**THE ANALYSIS**

The following concepts are explored in this script: Visualising and Exploring the Data. 

In particular I cover:

  1. Multiple Cross Correlation
  2. Heatmaps and Scattermatrixes
  3. Nearest Neighbours Analysis
  4. Standardisation of data
  5. Principle Component Anaylsis
  6. Pipeline models
  Data Standardistaion 




