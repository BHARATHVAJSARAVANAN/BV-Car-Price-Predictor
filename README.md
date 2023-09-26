# Car Price Predictor
[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

Project link: https://car-price-price.herokuapp.com
Demo Video: https://youtu.be/HEaFU68WAPM

<img src="https://github.com/rajtilakls2510/car_price_predictor/blob/master/demo.png">



# Aim

This project aims to provide a useful tool for both buyers and sellers in the automotive market, assisting them in making informed decisions about car pricing and predict the Price of an used Car by taking it's Company name, it's Model name, Year of Purchase, and other parameters.

<img src="https://github.com/rajtilakls2510/car_price_predictor/blob/master/predict.png">

## How to use?

1. Clone the repository
2. Install the required packages in "requirements.txt" file.

Some packages are:
 - numpy 
 - pandas 
 - scikit-learn

3. Run the "application.py" file
And you are good to go. 

# Description

## What this project does?

1. This project takes the parameters of an used car like: Company name, Model name, Year of Purchase, Fuel Type and Number of Kilometers it has been driven.
2. It then predicts the possible price of the car. For example, the image below shows the predicted price of our Hyundai Grand i10. 

<img src="https://github.com/rajtilakls2510/car_price_predictor/blob/master/predict.png">

## How this project does?

1. First of all the data was scraped from Quikr.com (https://quikr.com) 
Link for data: https://github.com/BHARATHVAJSARAVANAN/BV-Car-Price-Predictor/blob/master/quikr_car.csv

2. The data was cleaned (it was super unclean :( ) and analysed.

3. Then a Linear Regression model was built on top of it which had 0.92 R2_score.

Link for notebook :https://github.com/BHARATHVAJSARAVANAN/BV-Car-Price-Predictor/blob/master/quikr_predictor.py

4. This project was given the form of an website built on Flask where we used the Linear Regression model to perform predictions.

## How to run on your local host?

Prerequisite: Download all files from Github Link :https://github.com/BHARATHVAJSARAVANAN/BV-Car-Price-Predictor

Download PyCharm

1. Create new environment using command --> conda create -n env_name python==3.10.2
   
2. Activate environment using command --> conda activate env_name
   
3. Install requirements by typing (cd ProjectFolder) --> pip install -r requirements.txt
   
4. Now run app.py by writing command --> python app.py

OR

Download VScode

1. Download Project code from github 
   
2. Open Car Price Predictor Folder in VScode.
   
3. Open Terminal and Install requirements by typing (cd ProjectFolder) --> pip install -r requirements.txt
   
4. Now run app.py by writing command --> python app.py

CAR DATASET:https://github.com/BHARATHVAJSARAVANAN/BV-Car-Price-Predictor/blob/master/quikr_car.csv

Project Demo: linkedin
