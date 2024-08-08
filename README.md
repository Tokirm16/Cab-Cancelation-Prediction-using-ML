# Cab-Cancelation-Prediction-using-ML

## Project Overview
This project involves analyzing the YourCabs dataset to build predictive models for a binary classification problem. The project includes data preprocessing, visualization, model training, and evaluation. To improve model accuracy and performance, the dataset is divided into three parts based on the travel_type_id column, and separate models are trained for each subset.

## File Description
CapstoneProject_Code.ipynb: Jupyter notebook containing the entire project code, including data loading, preprocessing, visualization, model training, and evaluation.
YourCabs.csv: Dataset used for analysis and model building.
### Requirements
The project requires the following Python libraries:
pandas
matplotlib
seaborn
numpy
scikit-learn
These libraries are listed in the requirements.txt file.

## Usage
Clone the repository.
Install the required libraries using the command:
bash
Copy code
pip install -r requirements.txt
Open the Jupyter notebook CapstoneProject_Code.ipynb to run the code and see the analysis.
## Project Steps
Importing Libraries: Import necessary libraries for data manipulation, visualization, and machine learning.
Loading Data: Load the dataset using pandas.
Data Inspection: Check for null values and data types.
Data Visualization: Visualize the data to understand the distribution and relationships.
Data Preprocessing: Clean the data and engineer necessary features.
Model Training: Split the data into training and testing sets, standardize the features, and train logistic regression models.
Model Evaluation: Evaluate the models using ROC curve, AUC score, classification report, and confusion matrix.
## Model Strategy
The dataset is divided into three subsets based on the travel_type_id column, and separate models are trained for each subset. This approach is used to address the specific characteristics and patterns of each travel type, leading to more accurate and specialized models. By segmenting the data, the models can better capture the nuances and provide more reliable predictions.

## Results
The models' performance is evaluated based on several metrics to ensure their effectiveness in predicting the target variable.
