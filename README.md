# Customer Churn Prediction App
This is a simple interactive web application built with **Streamlit** that predicts the probability of a customer churning (leaving a service). The app uses a pre-trained **TensorFlow** model and pre-processed data encoders for prediction.

## Features
- Interactive form to input customer details  
- Real-time churn prediction using a trained deep learning model  
- Uses pre-fitted:
  - `LabelEncoder` for gender  
  - `OneHotEncoder` for geography  
  - `StandardScaler` for feature scaling  

##  Tech Stack

- Streamlit for frontend UI  
- TensorFlow / Keras for loading the prediction model  
- Scikit-learn for encoding and scaling  
- Pandas and NumPy for data manipulation  

## File Structure
├── app.py # Streamlit application
├── model.h5 # Trained TensorFlow model
├── label_encoder_gender.pkl # LabelEncoder for gender
├── onehot_encoder_geo.pkl # OneHotEncoder for geography
├── scaler.pkl # StandardScaler for input normalization

## Inputs
The app takes the following inputs:

Geography (country name)

Gender

Age

Credit Score

Balance

Estimated Salary

Tenure (number of years with the bank)

Number of Products (used by the customer)

Has Credit Card (0 or 1)

Is Active Member (0 or 1)

## Output
Displays Churn Probability (0 to 1)

Displays Interpretation: Whether the customer is likely to churn or not

