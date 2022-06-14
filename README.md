# ML/DL Algorithms on Breast Cancer Dataset
## Introduction

This project is the implementation of machine learning and deep learning models on Breast Cancer dataset, which is available in sklearn package. We are trying to findout
how different models work on the default dataset available associated with the package.

## Dataset

Features are measured from a digitalized image of a Fine needle aspirate (FNA) of a breast mass. We have 569 entries in the dataset and 33 columns. We are trying to focus
on the diagnosis of cancer level based on the measurements available in the dataset, and using the trained model we can do the prediction on the unseen data. 
We are trying to predict the class of diagnosis variable and all remaining 32 variables are independent. Dependent variable has two classes- Malignant (M), Benign (B). Below are the attribute information:

id                    
diagnosis             
radius_mean           
texture_mean          
perimeter_mean        
area_mean             
smoothness_mean       
compactness_mean      
concavity_mean        
concave points_mean   
symmetry_mean         
fractal_dimension_mean
radius_se             
texture_se            
perimeter_se          
area_se               
smoothness_se         
compactness_se        
concavity_se          
concave points_se     
symmetry_se           
fractal_dimension_se
radius_worst           
texture_worst          
perimeter_worst        
area_worst             
smoothness_worst       
compactness_worst      
concavity_worst        
concave points_worst   
symmetry_worst         
fractal_dimension_worst
Unnamed: 32

One of the main challeges we have seen during our model implementation was the class imbalance and we used 'class_weight' parameter to avoid this issue. A few of the
variables are mutually correlated which are really not providing any significant roles to the analysis. No null values were in dataset and we have excluded id column 
because it doesn't add any value to our analysis.

## Training & Testing

For the machine learning we used Logistic Regression and for deep learning we have chosen Neural Network. For both the models we did the same train and test split.
Training- 80% of the data and 20% for the testing.

## Models

Logistic Regression Model
Deep Neural Network
Python programming language is used for execution.

## Contact

Akhil Mathew (mathewakhil1110@gmail.com)

