# Predicting Cardiovascular Disease README

## Authors
- Angelina Amato
- Rebecca Breland
- Charlie Cryer
- Braedyn Edwards
- Magdeline Ng

****

## Getting started
Within the zip folder, you should find a datasets folder containing all of our different datasets that were used to train our different estimators. Since some of our estimators use standardized data and some do not, you will find subfolders in the datasets folder that contain those necessary datasets.   

It is recommended that you download all the datasets at once; however, if you would like to download them one at a time, the datasets needed for each classifier will be listed below.  

****
## Data Processing
To see our data preprocessing, feature engineering, or would like to recreate our datasets from scratch, please refer to the *Preprocessing* folder. In this folder you will find two files: *Data_cleaning.ipynb* and *Data_cleaning_reduced.ipynb*. Upload these files to a Jupyter server with the *datasets/other/cardio_train.csv* dataset downloaded to run the file in full.

In the first file, you will find some of our initial data cleaning efforts that involved several diagrams and outlier removal. 

The second file was our second attempt at data cleaning and preprocessing that does not contain many diagrams; however, it produces most of the datasets used in our classifiers as seen below.   

****

## Running the Classifiers
For each classifier that we analyzed, you will find their individual instructions and respective code paths from the zip in this section.

### KNN Classifier
- Location: CVD_code.zip
- Files: 
    - KNN PCA 95.ipynb   
- Datasets: 
    1. datasets/standardized/engineered_df_with_category_interactions.csv   

To run *KNN PCA 95.ipynb*, upload the Jupyter Notebook file to a Jupyter server, as well as download the above mentioned dataset. You should then be able to run the file in its entirety. 

### Logistic Regressor
- Location: CVD_code.zip
- Files: 
    - Logistic_Regression.ipynb   
- Datasets: 
    1. datasets/standardized/engineered_df_with_category_interactions.csv  
    2. datasets/non standardized/cleaned_df.csv

To run *Logistic_Regression.ipynb*, upload the Jupyter Notebook file to a Jupyter server, as well as download the above mentioned datasets. You should then be able to run the file in its entirety. 

### Decision Tree Classifier
- Location: CVD_code.zip/Decision Trees/ 
- Files:    
    - Decision Trees (CVD Prediction First Attempt).ipynb
    - Decision Trees (CVD Prediction Second Attempt).ipynb 
- Datasets: 
    1. datasets/other/X.csv
    2. datasets/other/y.csv
    3. datasets/other/cardio_train.csv

To see the preliminary results of the Decision Tree on its first training, please use *Decision Trees (CVD Prediction First Attempt).ipynb*. Upload this Jupyter notebook to a Jupyter server and please have the *cardio_train.csv* dataset downloaded.

To see the final results of the Decision Tree, please use *Decision Trees (CVD Prediction Second Attempt).ipynb*, upload the Jupyter Notebook file to a Jupyter server, as well as upload the *X.csv* and *y.csv* files from above. You should then be able to run the file in its entirety. 

### Random Forest Classifier
- Location: CVD_code.zip/Random Forest/
- Files
    - RandomForest_PCA.ipynb
    - RandomForest_NoFeatEng.ipynb
    - RandomForest_Demo.ipynb
- Datasets: 
    1. datasets/non standardized/engineered_df_with_category_interactions.csv 
    2. datasets/non standardized/cleaned_df.csv   

To see the preliminary results of the Random Forest classifier without feature engineering, upload *RandomForest_NoFeatEng.ipynb* to a Jupyter server. Upload the *cleaned_df.csv* dataset to run the file in full.

To see the final results of the Random Forest classifier with feature engineering and some PCA testing, upload *RandomForest_PCA.ipynb* to a Jupyter server. Upload the *engineered_df_with_category_interactions.csv* dataset to run the file in full.

To see our demo that was presented to the class, upload *RandomForest_Demo.ipynb* to a Jupyter server. For this file to work, you will need to download both the above mentioned datasets.

### Support Vector Machine
- Location: CVD_code.zip
- Files:
    - SVM_Heart_Prediction.ipynb
    - SVM_project_hyperparam_tuning.ipynb
- Datasets: 
    1. datasets/standardized/engineered_df_without_category_interactions.csv  
    2. datasets/non standardized/cleaned_df.csv

To view and reproduce the initial results of the SVM classifier before hyper-parameter tuning, download *SVM_Heart_Prediction.ipynb* and upload it to a Jupyter server. Upload the *engineered_df_without_category_interactions.csv* dataset to run the file in full.

To see the hyper-parameter tuning and final results of the SVM classifier, download *SVM_project_hyperparam_tuning.ipynb* and upload it to a Jupyter server with the *cleaned_df.csv* to run the file in full.# CVD-Prediction
