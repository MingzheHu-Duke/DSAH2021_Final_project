# DSAH2021_Final_project
In-Hospital Motality Prediction

This is the folder for DSAH 2021 Final Project.

The file structure is shown below with descriptions.
./Report
    "The final report"
./ANN_classifier.ipynb
    "The code to develop the ANN classifiers"
./LR_classifier.ipynb
    "The code to develop the logistic regression model"
./RandomForest_classifier.ipynb
    "The code to develop the random forest classifier"
./exploratory_data_analysis.ipynb
This jupyter notebook requires the feature extracted from the MIMICIII dataset by first running files in ./Data_part.rar. Once feature extraction is done, this jupyter notebook visualizes data distributions of the features and detects outliers. The plots generated in this file includes: pari correlation plots between 17 features and labels, box plots of standard deviations of blood oxygen level, and mean blood pressure based on labels, correlation matrix and finally the number of positive subjects and negative subjects. 
./Data_part.rar
extract_patients.py
“Extract patient cohort as described in our report ”
clean_events.py
“Clean the events data as described in our report”
extract_timeseries.py
“Break up per-subject data into separate episodes as described in our report”
transform_timeseries.py
“Transform the time series data into features that we will use in our models”
./in_hospital_mortality_with_validation.zip
./in_hospital_mortality.zip
./Models/resampled_model.zip
    "The saved model of optimized ANN (oversampling)"
./Models/weighted_model.zip
    "The saved model of optimized ANN (adjust class weights)"
./Models/saved_logistic.sav
    "Saved logistic regression model"
./Models/saved_randomforest.sav
    "Saved random forest classifier"
./requirements.txt
    “The package version requirements”

The codes are also available on GitHub:
https://github.com/MingzheHu-Duke/DSAH2021_Final_project.git
