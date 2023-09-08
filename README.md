# car_price_predictor

 ## Overview
This project aims to create a car price predictor model using the linear regression method. The model predicts the selling price of a car based on three key features: the car's model, mileage, and age. The car's model is categorized into three options: BMW X5, Audi A5, and Mercedes Benz C class.

## Features
 Car Model: This feature represents the make and model of the car, with three categories: BMW X5, Audi A5, and Mercedes Benz C class.

 Mileage: Mileage refers to the number of miles the car has been driven. This feature plays a crucial role in determining the car's price, as a higher mileage typically leads to a lower selling price.

 Age of the Car: The age of the car is measured in years. As a general trend, older cars tend to have lower selling prices compared to newer ones.

## Dataset
The dataset used for this project contains information on various cars, including their model, mileage, age, and the actual selling price. This dataset serves as the foundation for training and testing the linear regression model.

## Model Training
The linear regression model is trained on the dataset to learn the relationship between the selected features (car model, mileage, and age) and the selling price. The goal is to create a model that can accurately predict the selling price of a car based on these features.

## Trends
The analysis of the dataset reveals some general trends:

 Age vs. Price: There is a negative correlation between the age of the car and its selling price. As the car gets older, its selling price tends to decrease.

 Mileage vs. Price: Similarly, there is a negative correlation between mileage and selling price. Cars with higher mileage tend to have lower selling prices.

## Visualization
To better understand these trends, graphical visualization is performed using scatterplots. The scatterplots are created using the Matplotlib library, allowing for a visual representation of the relationship between age, mileage, and selling price.

## Usage
To use this car price predictor model:

Ensure you have the required libraries installed, including NumPy, Pandas, Scikit-Learn, and Matplotlib.

Load your dataset or use the provided sample dataset.

Train the linear regression model using the selected features.

Utilize the trained model to predict the selling prices of cars based on their features.

Visualize the relationships between features and selling prices using scatterplots.

## Dependencies
NumPy
Pandas
Scikit-Learn
Matplotlib
## Credits
This project was created by Harsh kumar.
