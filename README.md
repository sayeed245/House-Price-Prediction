# House-Price-Prediction
## Table of Content
  * [Overview](#overview)
  * [Data](#data)
  * [Technical Aspect](#technical-aspect)
  * [Installation](#installation)
  * [Feature Request](#feature-request)
  * [Credits](#credits)
  * [Connect](#connect)
## Overview
To predict house price from 80 different features by comparing Linear Regression, Lasso and XGboost models and using an ensemble of XGBoost and Lasso regression
## Data
The data is taken from [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) competition hosted in Kaggle
#### Data description: [Click here](https://github.com/sayeed245/House-Price-Prediction/blob/main/data_description.txt)
## Technical Aspect
- [Linear Regression Ensemble](https://github.com/sayeed245/House-Price-Prediction/blob/main/Linear%20Regression%2Censemble%20XGB%2CLASSO(complete%2020-11-2020).ipynb)
     
     - Performed outlier elimination and imputed missing values
     - Applied Box-Cox transformation on skewed features
     - Generated 81 new features from existing 80 feautres
     - Achieved RMSLE score of 0.174 using Linear Regression
     - Achieved 47% decrease in RMSLE using an ensemble of XGBoost and Lasso regression model 
## Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
## Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/sayeed245/Fraud-Detection/issues/new) by including your search query and the expected result.
## Credits
#### Kaggle: [House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
## Connect
#### LinkedIn: [https://www.linkedin.com/in/sayeed-mohammad-83b691108/](https://www.linkedin.com/in/sayeed-mohammad-83b691108/)
#### Twitter: [https://twitter.com/6SAYEED](https://twitter.com/6SAYEED)
#### Tableau Public: [https://public.tableau.com/profile/sayeed.mohammad#!/](https://public.tableau.com/profile/sayeed.mohammad#!/)
