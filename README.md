
<h1><center>Bangalore House Price Prediction</h1>

![frame_firefox_mac_dark (1)](https://raw.githubusercontent.com/AdityaSuresh013/Bangalore-House-Price-Prediction/main/.github/BLRHouseprice.PNG) 

A Bangalore House Price Prediction website made using Flask for a College Project

## Overview

This project aims to develop a web application that predicts house prices in Bangalore using machine learning algorithms. The application features a interface built with Flask, allowing input of various parameters of a house and receive a predicted price.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [License](#license)
- [Author](#author)

## Features

- Web interface for inputting house details.
- Predicts house prices based on various features such as location, size, number of bedrooms, etc.
- Visualization of prediction results.
- Responsive design for mobile and desktop devices.

## Technologies Used

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, JavaScript
- **Machine Learning**: scikit-learn, Pandas, NumPy
- **Visualization**: Matplotlib, Plotly

## Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AdityaSuresh013/bangalore-house-price-prediction.git
   cd bangalore-house-price-prediction
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment:**

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Flask application:**

   ```bash
   python app.py
   ```

2. **Open browser and navigate to:**

   ```
   http://127.0.0.1:5000/
   ```

3. **Enter the details of the house and submit to get the predicted price.**

## Data

The dataset used for training the model is sourced from [Kaggle](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data), which includes various features relevant to house pricing in Bangalore, such as:

- Location
- Size (in square feet)
- Number of bedrooms
- Number of bathrooms

## Model Training

The machine learning model is trained using historical house price data. Key steps involved:

1. **Data Preprocessing**: Cleaning and transforming the dataset to make it suitable for training.
2. **Feature Selection**: Selecting the most relevant features that impact house prices.
3. **Data Visualization**: Visualizing the cleaned dataset using Matplotlib
4. **Model Selection**: Implementing various regression models (Linear Regression, Lasso, Decision Trees) to find the best performing model.
5. **Evaluation**: Evaluating the model's performance using metrics like K Fold Cross, etc.

##  License

[MIT](https://choosealicense.com/licenses/mit/) © [Aditya S](https://github.com/AdityaSuresh013)
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- [Aditya Suresh](https://github.com/AdityaSuresh013)
