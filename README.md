# Gen AI - 8138
# Insurance Charges Prediction using Artificial Neural Networks
- Introduction
- Dataset
- Requirements
- Usage
- Results
# Introduction
This project aims to predict insurance charges using artificial neural networks (ANNs). The dataset used contains information about insurance applicants including age, sex, BMI, number of children, smoker status, and region. The goal is to build an ANN model that accurately predicts insurance charges based on these features.
# Dataset
The dataset used in this project is stored in insurance.csv. It contains the following columns:
* age: Age of the insurance applicant.
* sex: Gender of the insurance applicant (male or female).
* bmi: Body mass index (BMI) of the insurance applicant.
* children: Number of children/dependents covered by the insurance.
* smoker: Smoking status of the insurance applicant (yes or no).
* region: Region where the insurance applicant resides.
* charges: Insurance charges billed to the insurance applicant.
# Requirements
Make sure you have the following Python packages installed:
* pandas
* numpy
* scikit-learn
* tensorflow
* matplotlib
## You can install them using pip:
pip install pandas numpy scikit-learn tensorflow matplotlib
# Usage
- 1.Navigate to the project directory :
cd insurance-charges-prediction
- 2.Run the Jupyter Notebook insurance_charges_prediction.ipynb to train the ANN model and evaluate its performance :
jupyter notebook insurance_charges_prediction.ipynb
# Results
After training the ANN model, you can expect to see the mean squared error (MSE) on the test set. Additionally, a scatter plot showing the actual vs. predicted charges will be generated for visual inspection of the model's performance.
