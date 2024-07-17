# Fish Species Prediction

This project predicts fish species based on various measurements using machine learning models.

## Project Structure
- `app.py`: Flask application for serving the model and UI.
- `model.py`: Script for training and saving the machine learning model.
- `static/`: Folder containing CSS files.
- `templates/`: Folder containing HTML templates.
- `data/`: Folder containing the dataset.
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and evaluation.

## Getting Started

### Prerequisites
- Python 3.7+
- Flask
- scikit-learn
- pandas
- Jupyter Notebook

### Render platform deployment
- Log in to Render.com
- Create a new web service and connect your GitHub repository
- Set the build command to pip install -r requirements.txt
- Set the start command to python app.py
- Deploy the service

## Render URL: https://fishdataprediction.onrender.com/
