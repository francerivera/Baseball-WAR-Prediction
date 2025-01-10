# Baseball Next Season Wins Above Replacement (WAR) Prediction

## Project Overview

This project aims to predict a baseball player's Wins Above Replacement (WAR) for the upcoming season. We'll utilize `pybaseball` to download historical season data, clean and prepare it for machine learning, and then employ feature selection and ridge regression to build a predictive model. Finally, we'll evaluate the model's performance and explore for improvement. Through this process, you'll gain a model capable of predicting next season WAR, along with insights into further enhancing its accuracy.

## Project Steps

1. **Data Download and Cleaning:** Download historical baseball season data using `pybaseball` and preprocess it for machine learning tasks. This may involve handling missing values, converting data types, and potentially creating new features relevant to WAR prediction.

2. **Feature Selection:** Employ a sequential feature selector to identify the most statistically significant and informative features that contribute to predicting future season WAR. This helps focus the model on the most relevant aspects of a player's performance.

3. **Model Building and Evaluation:** Train a ridge regression model to predict next season WAR based on the selected features. We'll then assess the model's accuracy using appropriate metrics and explore techniques to improve its predictive capabilities.

4. **Model Improvement:** Explore various strategies to further refine the model's performance. This may involve incorporating additional data sources, trying different machine learning algorithms, or fine-tuning hyperparameters.

## Code

The code for this project is available in this repository.

### File Overview:

* `next_war.ipynb`: This Jupyter notebook contains the code for downloading baseball season data, feature selection, building the prediction model, and evaluating its performance.

## Getting Started

To run this project, you'll need Python and the following libraries:

* `pybaseball`
* `pandas`
* `scikit-learn` (specifically for ridge regression and potentially other machine learning models)

You can install these libraries using pip:

```bash
pip install pybaseball pandas scikit-learn
