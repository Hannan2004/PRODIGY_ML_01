# House Price Prediction Model

This project implements a machine learning model to predict house prices based on certain features.

## Overview

The primary algorithm used for this project is Linear Regression. However, during the development and testing phase, alternative algorithms were also considered. After careful evaluation, it was found that while Linear Regression was implemented in the final model, Support Vector Machine (SVM) showed promising results, producing the most effective predictions among the tested algorithms.

## Implementation

The main notebook for the project is `housePricePredictionModel.ipynb`. It contains the implementation of the house price prediction model using the Linear Regression algorithm.

## Instructions

1. Open the notebook `housePricePredictionModel.ipynb` to view the code.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the notebook to train and evaluate the model.

## Dependencies

- Python 3.10.12
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- seaborn

## Why Google Colab?

Google Colab was chosen as the integrated development environment (IDE) for this project due to its cloud-based nature and the following advantages:

- Free Access to GPUs: Google Colab provides free access to Graphics Processing Units (GPUs), which can significantly accelerate the training of machine learning models.
- Collaborative Editing: Multiple users can collaborate in real-time on the same Colab notebook, making it a convenient choice for teamwork and knowledge sharing.
- Integrated with Google Drive: Colab is seamlessly integrated with Google Drive, allowing easy access to datasets and the ability to save and share work directly in the cloud.

## Evaluation

The model's performance was assessed using the Mean Absolute Percentage Error (MAPE) metric:

- Linear Regression:
  - MAPE: 0.187416838

- Support Vector Machine (SVM):
  - MAPE: 0.18705129

- Random Forest Regression:
  - MAPE: 0.1929469

## Conclusion

While the primary implementation utilizes Linear Regression, it is worth noting that SVM demonstrated superior performance in terms of MAPE during testing. The decision to deploy Linear Regression was made based on various factors, including interpretability and simplicity. The project provides a foundation for house price prediction, and future work may involve further optimization or exploration of advanced techniques.
