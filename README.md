# Car-Price-Prediction

Using a history of previously used cars selling data and using machine learning techniques such as Supervised Learning can predict a fair price of the car, here I also used machine learning algorithms such as Random Forest and Extra Tree Regression along with powerful python library Scikit-Learn to predict the selling price.

Website Link- https://car-price-project1.herokuapp.com/

Testing Values:

Tech Stack:
* Front-End: HTML, CSS, Bootstrap
* Back-End: Flask
* IDE: Jupyter notebook, Pycharm

How to run this app:
* First create a virtual environment by using this command:
* conda create -n myenv python=3.6
* Activate the environment using the below command:
* conda activate myenv
* Then install all the packages by using the following command
* pip install -r requirements.txt
* Now for the final step. Run the app
* python app.py

Workflow:
* Data Collection:
Car Data from Kaggle

* Data Preprocessing:
* Missing values were handled.
* Drop unnecessary columns.
* Converted categorical variable into indicator variables.

* Data Visualization:
* Visualize final dataset using seaborn library.
* Made pairplots and heatmap.

* Model Creation:
* Different types of models were tried like linear regression, random forest.
* Out of these random forest is chosen.
* The conclusion were made using classification metrics.

* Model Deployment:
The model is deployed using Flask at Heroku server.
