# Spam-Message-Detector
A simple Flask API to detect spam or ham using Python and sklearn

This API allows us to utilize the predictive capabilities through HTTP requests.

The data is a collection of SMS messages tagged as spam or ham that can be found here:https://www.kaggle.com/uciml/sms-spam-collection-dataset

This is the directory tree inside the folder:

```
app.py
templates/
        home.html
        result.html
static/
        style.css
```

The sub-directory templates is the directory in which Flask will look for static HTML files for rendering in the web browser, in our case, we have two html files: home.html and result.html .

The app.py file contains the main code that will be executed by the Python interpreter to run the Flask web application, it included the ML code for classifying SMS messages

Steps:
```
* clone this repo:
* download the dataset
* cd deploy-spam-classifier-with-flask
* python app.py
```
Now you could open a web browser and navigate to http://127.0.0.1:5000/
