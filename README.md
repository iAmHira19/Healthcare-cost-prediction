# Healthcare Cost Prediction

This repository contains a project for predicting healthcare costs using a linear regression model. The model is trained on a dataset of medical charges and various features, including age, sex, BMI, number of children, smoker status, and region.

## Dataset

The dataset used for this project is the "Medical Cost Personal Dataset" from Kaggle. It includes the following columns:
- `age`: Age of the individual
- `sex`: Gender of the individual (female or male)
- `bmi`: Body Mass Index
- `children`: Number of children/dependents covered by the insurance
- `smoker`: Whether the individual is a smoker (yes or no)
- `region`: Residential area of the individual (southwest, southeast, northwest, northeast)
- `charges`: Medical costs billed by the insurance company (target variable)

## Project Structure

- `healthcare_cost_prediction.ipynb`: Jupyter Notebook containing the code for loading data, preprocessing, training the model, and evaluating performance.
- `requirements.txt`: List of Python libraries required to run the project.

## Installation

To run this project, you need to install the required libraries. You can do this using `pip`:

```bash
pip install -r requirements.txt
