Machine Learning Prediction App

This is a simple Flask web application that uses a pre-trained machine learning model to make predictions. The app provides a user-friendly interface to input features, which are then passed to the model to generate a result.

Features

Model Integration: Loads a serialized machine learning model (model.pkl) using Python's pickle library.

Web Interface: A simple and clean web form for user input.

Prediction Endpoint: A Flask route to handle form submissions, process the input data, and return a prediction.

Error Handling: Includes a try/except block to gracefully handle potential errors during prediction.

Project Structure
app.py: The core Flask application file. It's responsible for loading the model, defining the web routes (/ for the input form and /predict for the prediction), and rendering the HTML templates.

model/: This directory should contain your trained machine learning model, saved as model.pkl.

templates/: This directory is expected to hold your HTML files:

index.html: The main page with the input form.

result.html: The page that displays the prediction result.


<img width="1366" height="768" alt="Screenshot (75)" src="https://github.com/user-attachments/assets/132a0487-005c-435f-ba7f-3c04c57e3419" />
<img width="1366" height="768" alt="Screenshot (76)" src="https://github.com/user-attachments/assets/0b9f8ee9-8dcf-4bf7-a52b-f12679e758c4" />
