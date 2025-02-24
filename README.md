
# Credit Card Default Prediction - Ayush Anand

Financial threats are displaying a trend about the credit risk of commercial banks as the incredible improvement in the financial industry has arisen. In this way, one of the biggest threats faced by commercial banks is the risk prediction of credit clients. The goal is to predict the probability of credit default based on credit card owner's characteristics and payment history.

Use of various classification models like Decision Tree, Random Forest, XGBoost, MLPClassifier was done. XGBoost was selected as best model from above. The XGBoost model provided 82.63% accuracy in training. Testing accuracy for model was 82.3%. 80% data was used for training and 20% data was used for testing.
After Providing various details the model will predict whether customer will default next month or not. This project also provides the probability of default.

## Data Source

In our dataset we have 25 columns which reflect various attributes of the customer. The target column is default.payment.next.month , which reflects whether the customer will default next month or not. Our aim is to predict the probability of default given the payment history of the customer. I have built my model using a public dataset available on kaggle.

URL - https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

## WebSite URL

My WebApp URL - https://ayush-credit-default-7606193afd2e.herokuapp.com

## Software Requirements 

1) Python 3.10.7
2) Visual Studio Code
3) Git Cli
4) Jupyter Notebook
5) Heroku account
6) GitHub account

## Approach

Below are steps taken to build this project
1) Create Repository on GitHub with gitignore as pyhton.
2) Clone Repository from GitHub to Local using git clone command in VS Studio Code
3) Create a virtual environment inside working foleder named venv use command - python -m venv "path/venv"
4) Create a requirements.txt file which contains all libraries that are required to run this project.
5) Read Dataset using pandas library
6) Start Exploratory data analysis
7) Start building various models like Decision Tree Classifier, Random Forest Classifier, XGBoost Classifier, KNN Classifier, MLP Clasiifier
8) Tune the models with cross validation using GridSearchCV
9) Select best model and make pickle file.
10) Create app.py file which used dash library for front-end design.
11) Test the app.py on local system.
12) Create Procfile for deployement in Heroku platform.
13) Add, Commit and Push all files from Local to GitHub
14) Deploy to Heroku and Link the GitHub Repository

## Documentation

1) [Detailed-Project-Report](https://drive.google.com/file/d/1RzAYSjtYzoOGyIkwBysER5hXyY185GgQ/view?usp=sharing)
2) [High-Level-Design-Document](https://drive.google.com/file/d/11fiewmwFeNMyfPswHj0VlTgf5bY5f3_R/view?usp=sharing)
3) [Low-Level-Design-Document](https://drive.google.com/file/d/1MNgbjo1Y6-NSChTjaVSNa6DpYm-D4D6X/view?usp=sharing)
4) [Architecture](https://drive.google.com/file/d/1IB8WKm8O8L5a5RM-I4cfh99Vzl4zPv07/view?usp=sharing)
5) [Wireframe](https://drive.google.com/file/d/1t5j5_Y-wRM6MeArjr2gRAwxZVJOOY84c/view?usp=sharing)

# Project Demo

[Youtube-Link](https://youtu.be/52DZdT9kpNk)

## Author Linkedin URL 

Linkedin URL - https://www.linkedin.com/in/ayush-anand-924ba3215/

## Author

[@AnandAyush11](https://github.com/AnandAyush11)












