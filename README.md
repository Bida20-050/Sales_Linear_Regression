Linear Regression Model
Description
This project demonstrates a linear regression model utilizing 22GB of data from September 2022 to May 2023. The goal is to predict sales using various features and data cleaning techniques.

Table of Contents
Installation
Usage
Features
Contributing
License
Credits
Contact
Installation
To set up this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/Linear_Regression_Model.git
cd Linear_Regression_Model
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
To use this linear regression model, open and run the Jupyter notebook Linear_Regression_Model.ipynb. The notebook covers the following steps:

### read Sep 2022 - May 2023 data (9 months-worth)
Merging Datasets

Data Cleaning:

Remove negative sales
Filter for Mango sales
Filter columns for the model
Data Preparation:

Convert type of sale column to binary
Convert BST_TXN_DT_TIME from datetime to integer
Define features and target variables
Model Training:

#### Fit and train the LinearRegression Model
Performing Predictions:

markdown
Copy code
#### Performing Predictions
Model Evaluation:

Visualize the relationship between actual and predicted values using a scatter plot
Evaluate model accuracy using R² score
Calculate Mean Squared Error
