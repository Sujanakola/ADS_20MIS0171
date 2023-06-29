THYROID CLASSIFICATION USING DATA SCIENCE
ABOUT THYROID DISEASE:
The thyroid gland is a small organ that’s located in the front of the neck, wrapped around the windpipe (trachea). It’s shaped like a butterfly, smaller in the middle with two wide wings extending around your throat. The thyroid makes hormones that help control many vital functions of your body.

When the thyroid doesn’t work properly, it can impact your entire body: • If the body makes too much thyroid hormone, it can develop hyperthyroidism. • If the body makes too little thyroid hormone, it’s called hypothyroidism.

Both conditions are serious and need to be treated by your healthcare provider.

PROJECT OVERVIEW:
In this project, we have developed an efficient Thyroid Disease Classification System by comparing 6 different Classifier models' accuracy.

The result will be one of the following: • hyperthyroid • hypothyroid • sick • negative

PROJECT FLOW:
Importing the Libraries
Reading the Dataset
Analysing the Data
Visualizing the Data (Univariate, Bivariate and Multivariate Analysis)
Data Preprocessing i. Checking for Null Values ii. Checking for Outliers iii. Descriptive Analysis iv. Checking the Datatypes v. Checking Correlation vi. Handling Categorical Values vii. Splitting the Data into X and Y viii. Splitting the Data into Train and Test ix. Handling Imbalance x. Applying Standard Scaler
Model Building (Random Forest)
Performing Feature Importance
Selecting Output Columns
Model Building on Selected Columns i. Random Forest Classifier Model ii. XGBoost Classifier Model iii. SVC Classifier Model iv. Decision Tree Classifier Model v. K Nearest Neighbors Classifier Model vi. Naive Bayes Model
Selecting the Best Model with Highest Accuracy
Hyperparameter Tuning - Evaluating the Performance of the selected model using GridSearchCV and Cross Validation
Saving the Model (as .pkl file)
REPOSITORY CONTAINS
thyroid_data.csv
Thyroid Classifier.ipynb
thyroid_model.pkl
app.py
templates folder -> home.html
static folder -> style.css, thyroid.jpeg
.ipynb checkpoints folder -> Thyroid Classifier-checkpoint
Output Screenshots
Project Report
Project Demonstration Video
README.md
STEPS FOR EXECUTION
Extract the files of the repository to a folder.
Run the app.py on Spider IDE.
Copy the output url and paste it in the browser to get the output.

project video link : https://drive.google.com/file/d/17pnqKbftcIT0GCVQq2VWn7-3UoQ1Imld/view
