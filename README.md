# Heart Disease Prediction using Logistic Regression

This project aims to predict whether a person has heart disease based on various medical attributes.This project is intended for learning purposes and demonstrates how to preprocess the data, train a model, evaluate its performance, and interpret the results.

## Dataset

The dataset used in this project contains information about patients, such as age, sex, cholesterol levels, resting blood pressure, and more. It also includes a target variable indicating whether the person has heart disease (1) or not (0).

### Features:
- **age**: Age of the patient
- **sex**: Gender of the patient (1 = male, 0 = female)
- **cp**: Chest pain type
- **trestbps**: Resting blood pressure
- **chol**: Serum cholesterol
- **fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (1 = yes, 0 = no)
- **oldpeak**: Depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment
- **ca**: Number of major vessels colored by fluoroscopy
- **thal**: Thalassemia

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/heart-disease-prediction.git
    ```

2. Navigate to the project folder:
    ```bash
    cd heart-disease-prediction
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once the dependencies are installed, you can run the project script to train the logistic regression model:

```bash
python heart_disease_model.py
