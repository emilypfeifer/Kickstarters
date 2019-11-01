# What can you do to make your Kickstarter reach its goal?

The jupyter notebook for this project can be found [here.](https://github.com/emilypfeifer/NorthWind/blob/master/student.ipynb)

To view this jupyter notebook with NBviewer to experience Plotly's interactive graphs, please visit [here.](https://nbviewer.jupyter.org/github/emilypfeifer/Kickstarters/blob/master/kickstarter.ipynb)

The blog post for this project can be found [here.](https://pfeiferem.weebly.com/classifierssuccess-of-a-kickstarter.html)

## The Data
The Kickstarter dataset contains data on about 300,000 Kickstarter campaigns as well as whether or not they were successful in reaching their monetary goal. The data was obtained via Kaggle and can be found in the file `"kickstart2018.zip"` in this repository. The Kickstarter data includes several predictor variables for each project, including the country the project was started in, the category of the project, and the title of the project. 

## Goal

The goal of this project was to figure out which features have the most impact in making a Kickstarter campaign successful.

## Classification

After pre-processing the data and adding additional columns through feature engineering, I moved on to the classification stage of my notebook. There, I utilized several different classification models; including but not limited to Logistic Regression, Random Forest, and Decision Tree. 

After running my classifiers, I used hyperparameter tuning with GridSearch CV to improve the accuracy and SMOTE to combat class imbalance issues. 
