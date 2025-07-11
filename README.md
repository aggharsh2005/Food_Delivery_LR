# Food Delivery Time Prediction

## Project Overview

This project aims to predict food delivery time by considering various factors such as distance, weather conditions, traffic, the delivery person's experience, etc. The project involves data analysis, preprocessing, and the use of a machine learning model.

## Dataset

This project uses the `Food_Delivery_Time_Prediction.csv` dataset, which includes the following columns:

* `Order_ID`
* `Customer_Location`
* `Restaurant_Location`
* `Distance`
* `Weather_Conditions`
* `Traffic_Conditions`
* `Delivery_Person_Experience`
* `Order_Priority`
* `Order_Time`
* `Vehicle_Type`
* `Restaurant_Rating`
* `Customer_Rating`
* `Delivery_Time`
* `Order_Cost`
* `Tip_Amount`

## Installation

To run this project, you need to install the following libraries:
pip install -r requirements.txt'''

## How to Run

1.Clone this repository:
git clone <repository_url>

2.Navigate to the project directory:
cd <repository_directory>

3. Install the dependencies:
pip install -r requirements.txt

4.Run the Python script:
python food_delivery.py

## Analysis and Model
 Data Cleaning: Null values have been handled.

Feature Scaling: Distance and Delivery_Time have been scaled using MinMaxScaler.

 Label Encoding: Categorical features like Order_Priority, Weather_Conditions, etc., have been converted to a numerical format using LabelEncoder.

 Descriptive Statistics: The mean, median, mode, and variance of the data have been calculated.

 Correlation Analysis: The correlation between features and Delivery_Time has been analyzed.
