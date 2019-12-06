# Project D3

## Project Description
The goal of the project was to create an app and deploy it to `Heroku` (Cloud Application Platform).
The app runs a `Flask` server that renders the `index.html` file. The `Javascript` code queries an `sqlite` database, create a chart and plot the data using `D3` and `Plottly` libraries.
- The app deployed in Heroku can be found in the link below:
- `https://belly-button-biodiversity-cmg.herokuapp.com`

### App Running 
<hr>

![App Running](Screenshots/Belly_Button_Biodiversity_app.gif "App Running")
<hr>

### Sample app Screenshot
<hr> 

![Screenshot](Screenshots/Belly_Button_Biodiversity_app.png "Screenshot")
<hr>

## Instructions

### Offline
#### Requirements 
Install dependencies in your Python environment as described below:
- pip install gunicorn
- pip install psycopg2
- pip install flask
- pip install flask-sqlalchemy
- pip install pandas

#### Steps
1. - Run the `app.py` file with Python which creates a development server.
2. - While the `app.py` file is running open the route `http://127.0.0.1:5000/`or the one created by running the app.

### Online
Click the link below or type it in your web browser
- `https://belly-button-biodiversity-cmg.herokuapp.com`

# File Description
### - app.py
- Contains the code to run the `flask`server to run the app
### - db
- Contains the `Sqlite` databases queried by the app
### - Procfile
- Contains the instructions for `Heroku` to run the app on their server
### - requirements.txt
- Contains the libraries for `Heroku`to install in the server to run the app
### - Screenshots
- Contains the `gif` and `png` files with screenshots of the app running
### - Static
- Contains the `Javascript` code to plot and create tables in the `index.html` file
### - templates
- Contains the `html` file with the template to be used by `Javascript` to plot and create tables after the `app.py` file queries the `Sqlite`database