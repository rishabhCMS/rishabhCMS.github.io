---
title: "Emergency Messages Classification Using NLP"
excerpt: "<br/><img src='/images/1.gif'>"
collection: portfolio
---



The Objective of this Project was to develop a web app where the emergency responders can infer from a help message the type of help that needs to be supplied.
This project uses Natural Language Processing and trains a Random Forest Classifier to categorize messages.

[GitHub Code](https://github.com/rishabhCMS/Disaster_Response)


# Disaster Response Pipeline Project



### Aim:
The Objective of this Project was to develop a web app where emergency workers can infer from a help message the possible categories that a message belongs to... to be able to redirect necessary support as per “shelter”, “food” etc


### Demo



### Dependencies
Python 3 and the following Python libraries installed:

    NumPy
    Pandas
    Matplotlib
    Json
    Plotly
    Nltk
    Flask
    Sklearn
    Sqlalchemy
    Sys
    Re
    Pickle
    
### Instructions to run:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to http://0.0.0.0:3003/ with udacity spaceid and domian

### Results:
I was able to train the model and deploy the model


### Data Source:

[Figure Eight API](https://www.programmableweb.com/api/figure-eight-rest-api-v1)

### Acknowlegements

Udacity for the project template and Figure Eight for the data
