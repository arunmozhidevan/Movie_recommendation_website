# Movie_recommendation_website

Possibly contains awesomeness and Movie_recommendation_webs related files

## Overview
This is a Flask web app which predicts the fare of Flight ticket developed using python(Jupyter Notebook) and deployed on Heroku app.

## Installation
The Code is written in Python 3.8.6. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip, navigate into the installed python directory and open command promt:
```bash
python -m pip install --upgrade pip
```
If you have a higher version i.e. 3.8 or 3.9, make sure you install pip during your python installation or use this [get-pip.py](https://bootstrap.pypa.io/get-pip.py) in your python directory.
```bash
py get-pip.py
```
To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
## Coding on Jupyter Notebook
1. Load the csv file using pandas
<img target="_blank" src="https://64.media.tumblr.com/463714f1c095cab3b6035f0e7286dd0f/2b75f174b7825786-0b/s1280x1920/1b4ab36a3fc8cac02f3d1690b4bc87872bbd2b82.png">

2. Plotting the histogram to understand which year has the highest number of movies
<img target="_blank" src="https://64.media.tumblr.com/bec079d6cfcbeae06bdf32b086a9b825/2b75f174b7825786-6d/s1280x1920/0f912a13e608deb099f2d12204af9276768ba2c9.png">

3. The recommendatoin will be based on these features only
<img target="_blank" src="https://64.media.tumblr.com/f23c10188af921b5ce444145ca526944/2b75f174b7825786-95/s1280x1920/876b211f1a2e1b73c6358feaa50e9e2227f14743.png">

4. A little text processing on the movie titles
<img target="_blank" src="https://64.media.tumblr.com/8da2d70bb7fa6c25b144a6023d8cb2aa/2b75f174b7825786-ad/s1280x1920/8a909c5a8b7cc9999f06f69cd4fb3addf527f005.png">

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

You also use this [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Website


## Technologies Used
[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" height=50>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" height=50>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" height=50>](https://scikit-learn.org/stable/) [<img target="_blank" src="https://pandas.pydata.org/static/img/pandas_white.svg" height=50>](https://pandas.pydata.org/) [<img target="_blank" src="https://numpy.org/doc/stable/_static/numpylogo.svg" height=50>](https://numpy.org/doc/stable/) 
<br>
[![made-with-python](https://img.shields.io/badge/made%20with-Python-yellow)](https://www.python.org/) [![made-with-jupyter](https://img.shields.io/badge/made%20with-Jupyter-orange)](https://jupyter.org/)

## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/arunmozhidevan/Movie_recommendation_website/issues) here by including your search query and the expected result.

## Directory Tree 
```
├── static
│   ├── favicon.png
│   ├── profileimage.jpg
├── templates
│   ├── base.html
│   ├── home.html
│   ├── recommend.html
├── Procfile
├── README.md
├── Stage_2.ipynb
├── Stage_3.ipynb
├── app.yaml
├── main.py
├── main_data.csv
├── requirements.txt
├── stage_1.ipynb
```

