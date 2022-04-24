# Project statement
We aim to help mobile game developers increase the likelihood of creating a successful application in the mobile game market, based on factors that can be predetermined before release.

The dataset used can be found [here](https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps) (note that we used Version 7 of the data, the current most recent version).

---

# How to use this repository
1. Download the Jupyter notebook files
2. Follow the link in the PDF document in the 'Datasets and Models' folder/or follow the link [here](https://drive.google.com/drive/folders/1Yjt0WPY1M-7OwkbCnmTev6RSr5d8CRg-?usp=sharing)
3. Download the "data.zip" file from the Google Drive
5. Put all downloaded files in the same directory
6. Unzip the data file

Run the Jupyter notebooks in the following order
1. Data Preparation and Cleaning
2. Exploratory Data Analysis
3. Machine Learning Techniques

Project deliverables (link to video and PDF slides) can be found in the 'Project Deliverables' folder.
Alternatively, follow [this link](https://youtu.be/0OAhe5IueII) to view our project video!

---

# Notebooks explanations
## Data preparation and cleaning
Some cleaning and preparation we did includes:
- Selecting the columns we need
- Extracting only game categories
- Removing rows containing NA values
- Removing duplicate apps (by finding duplicate app names)
- Ensuring all prices are in the same currency (USD)
- Converting app size to kilobytes
- Deriving new columns

etc.

## Exploratory data analysis
Here we explored the data to understand it better. We did univariate exploration to view the distributions of single variables. Then we did bivariate exploration to study the relationships between predictor variables and the response variable.

### Univariate exploration
For numeric data we did boxplots and histplots. For categorical, we used countplot.
### Bivariate exploration
For numeric data we use stripplot. For categorical, we studied heatmaps and proportions of our response variable for each category in the predictor variable.

## Machine learning
We prepared the data by doing train-test split, SMOTE on the train data, and dummy variable encoding. 

The machine learning models we used were:
1. Random forest
2. AdaBoost
3. Logistic regression
4. Random forest with XGBoost

---

# New things we've leant
- SMOTE for handling class imbalance
- Encoding categorical data using pandas get_dummies() function
- Trying out different machine learning models not covered in the module:
  - Logistic regression
  - AdaBoost
  - Random forest with XGBoost
- Finding feature importance
