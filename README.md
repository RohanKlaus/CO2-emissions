[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://co2-emissions-mqnffnz7ka5rnzpyqjmyae.streamlit.app/)


<img height="25" width="80" src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"> <img height="25" width="70" src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white"> <img height="25" width="80" src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black"> <img height="25" width="70" src="https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white"> <img height="25" width="110" src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white"> <img height="25" width="90" src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white"> 

# CO2 Emissions Predictions by Cars 

![Cover](https://github.com/RohanKlaus/CO2-emissions/assets/139590571/abab12ec-4210-403b-a4e7-89690f7baa63)


<h3>Hey there,👨🏻‍💻</h3>
<p>During my internship, I worked on a project titled <b>"CO2 Emission Prediction by Cars."</b> The aim was to predict the amount of Carbon Dioxide (CO2) a car would emit based on its data. I gathered information about different cars and their CO2 emissions. Using this data, I made use of advanced techniques to build a Machine Learning model that could accurately estimate CO2 emissions. This project not only showcased my skills in Data Analysis and Machine Learning but also aimed to contribute to understanding and reducing vehicle-related environmental impacts.</p>

# Description of The Project:

<h3><b>Business Objective of the project</b></h3>

- The primary objective of the project is to develop a model that can accurately predict CO2 emissions based on different engine features of cars. 
- The goal is to estimate the amount of CO2 a car will emit using the provided data.

# Description of The Data:

- The data used in the project was collected from the Canadian Government's Official [Website](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6).

## About the Data 📈 

### It includes the following attributes:

- <b>Make:</b> Car brand under study.
- <b>Model:</b> Specific model of the car.
- <b>Vehicle_class:</b> Car body type.
- <b>Engine_size:</b> Size of the car engine in liters.
- <b>Cylinders:</b> Number of cylinders.
- <b>Transmission:</b> Type of transmission (e.g., automatic, manual).
- <b>Fuel_type:</b> Type of fuel used by the car.
- <b>Fuel_consumption_city:</b> City fuel consumption ratings in liters per 100 kilometers.
- <b>Fuel_consumption_hwy:</b> Highway fuel consumption ratings in liters per 100 kilometers.
- <b>Fuel_consumption_comb(l/100km):</b> Combined fuel consumption rating (city and highway) in L/100 km.
- <b>Fuel_consumption_comb(mpg):</b> Combined fuel consumption rating in miles per gallon (mpg).
- <b>Co2_emissions:</b> Tailpipe emissions of carbon dioxide for combined city and highway driving, in grams per kilometer.


# Tools and Technologies:

#### The project was developed using various tools and technologies, including:
- Python programming language
- Libraries such as NumPy, Matplotlib, SciPy, scikit-learn, and Streamlit.
- Linear Regression, Random Forest, K-Nearest Neighbors (KNN), Bagging and Boosting, Logistic Regression, and Ridge, Lasso, Elastic Net Regression models for prediction
- Deployment on the cloud using Streamlit


## How to install these libraries?
### You can install these libraries by using the command.

- You can install all the libraries in your system which I have used in my project by using only one command. 
- You will need Python in your system to use this command. You can use this given link to install Python in your system : [Python](https://www.python.org/downloads/)
- After installation of Python, you need to run this command in your command prompt.

```bash
pip install -r requirements.txt 
```
# Model Building:

- The project involved building and evaluating several machine learning models, including Linear Regression, Random Forest,Logistic Regression,  KNN, Ridge, Lasso, Elastic Net Regression models.
- The Random Forest model yielded the highest accuracy among these models and was selected for deployment.

<p align="center">
<img height="170" width="650" src="![Model Accuracy](https://github.com/RohanKlaus/CO2-emissions/assets/139590571/d072b494-3d76-4906-aa84-2fa95b625997)" alt="ModelBuilding">
</p>

# Deployment:

- The project was deployed using Streamlit, allowing users to interact with the model and make predictions on CO2 emissions based on car engine features.
- The deployment version of the project can be accessed through a provided link :[Project](https://co2-emissions-mqnffnz7ka5rnzpyqjmyae.streamlit.app/)

# Running the Project:

- To run the project locally, one can install the required libraries using the provided command in the command prompt. Use the below Streamlit command to launch the application.
```bash
streamlit run app.py 
```

## The project not only demonstrates technical skills but also contributes to Environmental awareness and Sustainable practices. It effectively combines Data Analysis, Machine Learning, and Software Development to address real-world challenges.

---
<p align="center">
<b>Thank You</b>❤
</p>
