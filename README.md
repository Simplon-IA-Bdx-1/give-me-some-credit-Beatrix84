github link: https://github.com/Beatrix84/Credit_p.git

## How to start the project
* Download training and test csv : https://www.kaggle.com/c/GiveMeSomeCredit/data

### Create a docker folder with:
* docker.compose.yml
* Dockerfile
* requirements 
* auth.env document:
    BIGML_API_KEY=()
    BIGML_USERNAME=()
    KAGGLE_USERNAME=()
    KAGGLE_KEY=()

### In Credit_p/docker:
    docker-compose up --build

## Project

### In Credit_p/docker:
    docker-compose up 

### Modification on datasets
* credit_modified.ipynb

### BigML prediction and Kaggle submission
* bigml_credit_prediction.ipynb :
    Kaggle public score : 0.85753

### Model analysis
* AUC_calculation.ipynb
* prediction_error.ipynb
* Learning_curves.ipynb

### Scikit-learn and XGBoost
* Credit-Split.ipnyb 
* Credit_model_scikit-learn.ipynb

### Prediction on a new entry
* Exo_191107.ipynb

### ML-Python book (chp 5, 6, 7)
* Exercise_book_ML_python_credit.ipynb