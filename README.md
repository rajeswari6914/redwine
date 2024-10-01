# Red Wine Quality Prediction

This project is a machine learning model that predicts the quality of red wine based on various physicochemical features. The model is deployed using a Flask web application to make predictions through a user-friendly interface.

## Project Overview

The main goal of this project is to predict whether the quality of a red wine is good or bad based on a set of input features. This prediction helps wine producers assess quality control and determine which batches of wine are most likely to be successful. The model was trained using the **Wine Quality** dataset and uses physicochemical properties (such as acidity, sugar content, pH, etc.) to classify wine quality.

## Dataset

The dataset used for this project is the **Wine Quality Dataset**. It contains information about different physicochemical attributes of red wines and their quality scores (rated between 0 and 10).

The dataset used in this project is provided in the file: `winequality-red.csv`.

## Dependencies

To run this project, you will need the following Python libraries:

- Flask
- pandas
- scikit-learn
- joblib
- numpy
- Jinja2 (for HTML templating)

## File Structure
- `app.py`: The Flask web application file that handles the routes and functionality for predicting wine quality.
- `model.joblib`: The pre-trained machine learning model saved using joblib.
- `redwine_prediction_raji.ipynb`: Jupyter notebook for data analysis, feature engineering, model training, and evaluation.
- `winequality-red.csv`: Dataset used for training the model.
- `templates/`: Folder containing HTML files for rendering the web interface.
- `README.md`: This README file describing the project.
## How to Run the Project
### 1.Clone the repository:
First, clone the repository to your local machine using the following command:
```sh
git clone <repository_url>
```
```sh
cd red-wine-quality-prediction
```
### 2.Run the Flask app:
To install all the required Python libraries, run:
```sh
pip install Flask pandas scikit-learn joblib numpy Jinja2
```
### 3.Run the Flask app:
Start the Flask server by running:
```sh
python app.py
```
You should see output similar to:
```sh
* Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
### 4.Open the web application:
Open your web browser and navigate to http://127.0.0.1:5000 to use the web application.
### 5.Use the application:
- Enter the physicochemical details of a red wine sample, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, pH, etc.
- Click the Predict button to get the predicted quality of the wine.
  
The application will display whether the wine is of Good Quality or Bad Quality.


https://github.com/user-attachments/assets/7faf7e94-f309-415e-b4b9-2ab5fae20757

