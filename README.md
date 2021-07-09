# Car-Price-Prediction

## Overview
This is a Flask web app which predicts price of cars.

## Dataset:
https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho

This dataset contains information about used cars.
This data can be used for a lot of purposes such as price prediction to exemplify the use of linear regression in Machine Learning.
The columns in the given dataset are as follows:

##### 1.name
##### 2.year
##### 3.selling_price
##### 4.km_driven
##### 5.fuel
##### 6.seller_type
##### 7.transmission
##### 8.Owner

For used motorcycle datasets please go to https://www.kaggle.com/nehalbirla/motorcycle-dataset


## Installation
The Code is written in Python 3.7.3 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```


## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download Hroku CLI to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```

├── templates
│   ├── index.html
├── Procfile
├── README.md
├── app.py
├── Car Price Prediction model.ipynb
├── random_forest_regression_model.pkl
├── requirements.txt
```

## Frontend Using Flask and HTML

https://carpredix.herokuapp.com/

![image](https://user-images.githubusercontent.com/75041273/125060149-aec31180-e0c9-11eb-9849-0b5c1cc3ba38.png)

![image](https://user-images.githubusercontent.com/75041273/125059567-13ca3780-e0c9-11eb-9967-c003aa73db09.png)




## 🏁 Technology Stack

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## 📋 Further Changes to be Done

- [ ] Deploying the Web Application on Cloud.
     - [ ] Google Cloud 
     - [ ] Azure
     - [ ] AWS EC2 Instance

