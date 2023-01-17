# Disaster Response Pipeline Project

This project classifies messages into 36 different categories to aid Disaster Respinse Teams filtering incoming messages and requests and improve the help they can provide.

### Instructions (when using the app for the first time and no model has been trained):
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterCleaned.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterCleaned.db models/classifier.pkl`
        (the model can be further optimized by adding or adjusting parameters in the "build_model()" function)

2. Go to `app` directory: `cd app`

3. Run your web app: `python run.py`

4. Click the `PREVIEW` button to open the homepage

### Instructions after the model is already trained
1. Go to `app` directory: `cd app`

2. Run your web app: `python run.py`

3. Click the `PREVIEW` button to open the homepage

The App runs in the Workspace of Udacity, but not yet in Windows, since create_engine from sqlalchemy won't work and joblip from sklrarn.externals can't be imported. 
Since the goal of the project was to provide a running code in the given Workspace the code has not been modified to work on Windows.
