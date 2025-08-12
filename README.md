# FITBALL

## Overview:

This project explores predicting the outcomes of English Premier League matches using machine learning and deep learning models. After evaluating baseline results, XGBoost proved to be the most effective, and we fine-tuned it to improve accuracy. The work highlights both the potential and the challenges of sports prediction, especially in forecasting draws.


<p align="center">
  <img src="Images/images.jpg" alt="Model Architecture" width="350"/>
</p>


## Repository Structure
- **data:** This directory contains raw datasets and the filtered dataset.
- **code:** Source code for the prediction model implementation is located here.


## How to Use
1. **Clone the Repository:** Clone this repository to your local machine.
   ```python
      git clone https://github.com/milleral1/FitBall-Predict-football-game-winner.git
   ```
2. **Install Dependencies:** Ensure all necessary dependencies are installed.
   ```python
    pip install numpy pandas scikit-learn xgboost scipy matplotlib seaborn tensorflow
    ```
3. **Prepare Data:** If using custom data, format it appropriately and replace the existing dataset.
4. **Run the Model:** Execute provided scripts in the `code` directory.
5. **Evaluate Results:** Examine predictions and evaluate model performance.



## Hyperparameters

Below are the hyperparameters used for our best XGBoost model after tuning:

colsample_bytree = 0.6595  
gamma = 4.2244  
learning_rate = 0.01698  
max_depth = 4  
min_child_weight = 3  
n_estimators = 716  
reg_alpha = 0.4960  
reg_lambda = 1.8858  
subsample = 0.6742  
window size = 5 (number of past matches considered when calculating features)   


## Authors:

* Alon Miller
* Hay Sayada
