# Customer-Churn-Prediction-App-Gradio
This repository contains code for a customer churn prediction app. The app is built using Gradio, a Python library that allows developers to quickly build customizable interfaces for machine learning models.
The app takes in data from the user about a customer and predicts whether that customer is likely to churn or not. The model used in this app is a random forest classifier that was trained on a customer churn dataset.

## Dependencies
* Gradio
* Pandas
* Numpy
* Pickle

## Usage
1. Clone the repository to your local machine
2. Install the dependencies using pip install -r requirements.txt
3. Run the app using python app.py
4. Follow the instructions in your console to launch the app in your web browser

## Files
* app.py: The main file that runs the Gradio app
* data.csv: The customer churn dataset used to train the model
* rf_model.pkl: The trained random forest classifier model
* encoder.pkl: The trained encoder used to encode categorical variables
* scaler.pkl: The trained scaler used to scale numerical variables

## How It Works
The app takes in data about a customer, including their gender, age, monthly charges, contract type, and more. This data is then used to make a prediction about whether or not the customer is likely to churn.

To make this prediction, the app uses a trained random forest classifier model. The model was trained on a dataset of customer churn data, which included features such as customer demographics, services used, contract details, and more. The model was then saved using the Pickle library, so that it could be loaded and used by the app.

The app also uses a trained encoder and scaler to preprocess the user input data. Categorical variables are encoded, and numerical variables are scaled, to ensure that the data is in the correct format for the model to make predictions.

## Conclusion
The customer churn prediction app built in this repository is a great example of how machine learning can be used to make predictions about real-world scenarios. By using a trained random forest classifier model and Gradio's easy-to-use interface building tools, developers can quickly create a user-friendly app that can help businesses make better decisions about their customers.

