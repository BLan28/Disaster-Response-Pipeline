This is README.md
=======
# Disaster Response Pipeline Project
### 1. Installation
To follow along with this project, you will need to install the following libraries which are not included in the default Anaconda distribution: pandas, numpy,sqlalchemy, re, NLTK, pickle, Sklearn, plotly. flask.

### 2. Project Motivation
The goal of this project is to create a machine learning pipeline to categorize real messages that were sent during disaster events so that we can send the messages to an appropriate disaster relief agency. The project will include a web app where an emergency worker can input a new message and get classification results in several categories. The web app will also display visualizations of the data.

### 3. File Descriptions
This repository contains 3 folder:
	1. Data: contain data files as: DisasterResponse.db, disaster_categories.csv, disaster_messages.csv and process_data.py for processing data to be ready for building model.
    2. models: contain "train_classifier.py" for building model and saved model "classifier.pkl
    3. app: "run.py" and templates folder for the web application

### 4. How to Interact with Your Project
	1. Run the following commands in the project's root directory to set up your database and model.

    	- To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    	- To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

	2. Go to `app` directory: `cd app`

	3. Run your web app: `python run.py`

### 5. Licensing, Authors, Acknowledgements
Alongside meeting educational purposes, this project was designed solely for exploration hence no serious licensing process is required for this work. This work serves as an affirmation of the data science skills I've learned through various training programs, including the Udacity Data Science course. Feel free to use any part of the code if helpful to you.
>>>>>>> master
