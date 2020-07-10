# Car-Price-Predictions
## Table of Content
* Demo
* Overview
* Technical Aspect
* Installation
* Run
* Deployement on Pivotal
* Directory Tree
* To Do
* Technologies Used
* Team
* Credits
* References

## Demo
Link:- https://carpricepredictioner.herokuapp.com/

![index_page](https://github.com/rs301378/Car-Price-Predictions/blob/master/car_price.JPG)

## Overview
This is a simple car price predictor Flask app. It shows the selling price of your car by putting the vaules/features like year in which the car was bought, ex-showroom price of the car, the distance completed by the car in km, the number of owners the car has previously had, Fuel type of the car, whether the seller is a dealer or an individual, and whether the car is manual or automatic. By using this data it will predict the cars selling price. All the data contain in a `.csv` file.
## Technical Aspect
This project is divided into two parts:-
1. Build model using python.
2. Design an app using Flask framework.
2. Host a Flask app on Heroku cloud.

  * A user can fill all the fields that are given.
  * Click on `Calculate the Selling Price` button. It will show the selling price below that `Calculate the Selling Price` button.
  * Used flipkart site to show the reviews of products.
  * Used Vehicle  dataset from cardekho Kaggle.
  * Used Heroku platform to make this app public.
## Installation
The code is written in `Python 3.6`. If you don't have Python installed you can find it [here](https://www.python.org/downloads/ "install python") .To install the required packages and libraries, run this command in the project directory after [clonning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/ "cloning") the repository.
`pip install -r requirements.txt`
## Run
### Step1.
To run this on local machine, click on `run` button in `flask_app.py` file.
### Step2.
Copy the link for e.g. `http://127.0.0.1:5000/` and past it on your browser and hit enter.
## Deployement on Heroku
### Step1.
Maintain necessary files like `requirements.txt, Procfile` . **Givent in the project directory check there.**
### Step2. 
This step would be to follow the instructions given on [Heroku Documnetation](https://devcenter.heroku.com/categories/deployment "Heroku Documnetation") to deploy a web app.
## Directory Tree
```
|--static/css
| |--css
| | |--all.css
| | |--all.min.css
| |--webfonts
| | |--fa-brands-400.lot
| | |--fa-brands-400.svg
| |--main.css
|--templates
| |--index.html
|--app.py
|--car data.csv
|--Car data_model.ipynp
|--Procfile
|--README.md
|--requirements.txt
|--rf_model.pkl
```
## To Do
1. Improve the model accuracy by increase the data size and apply some advance machine learning techniques.
2. Add better UI and animations.
## Technologies Used
![Python](https://www.python.org/static/community_logos/python-logo-master-v3-TM.png)  ![Heroku](https://cdn.technologyadvice.com/wp-content/uploads/2019/09/Heroku-Logo-01-300x300.png)  ![Flask](https://miro.medium.com/max/438/1*0G5zu7CnXdMT9pGbYUTQLQ.png)  
## Team
| ![Rohit](https://avatars1.githubusercontent.com/u/35064155?s=60&v=4) |
| -------------------------------------------------------------------- |
| [Rohit Sharma](https://github.com/rs301378/)
## Credits
All the creadits of this project goes to [Krish Niak](https://github.com/krishnaik06 "Krish Niak"). :heart:
## References
 * [Dataset](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho "Dataset")
