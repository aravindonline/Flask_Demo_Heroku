### Flask_Demo_Heroku

This is a demo project to elaborate how Machine Learning Models are deployed on production using Flask API. source code taken from: https://github.com/krishnaik06/Deployment-flask.

### Project Structure

1. model.py - This contains code fot our Machine Learning model to predict employee salaries based on training data in 'hiring.csv' file.
2. app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
3. request.py - This uses requests module to call APIs already defined in app.py and dispalys the returned value.
4. templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.
