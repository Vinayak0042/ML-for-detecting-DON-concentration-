# Machine Learning Model for Predicting Vomitoxin Levels

## Overview
This project aims to build and evaluate multiple machine learning models to predict vomitoxin levels in crops based on various features. The models include linear regression, neural networks, ensemble methods, and a stacking regressor. The project also employs data preprocessing techniques such as scaling, feature engineering, and PCA.

## Repository Structure
```
├── colab/                # python code model
├── data/                 # dataset files
├── best_model.pkl/       # pickel file for best models
├── pca.pkl/              # pickel file for PCA
├── poly.pkl/             # pickel file for polynomial
├── scaler.pkl/           # pickel file for scaler
├── README.md             # Project documentation
```

## Setup Instructions

### 1. Clone the Repository
```sh
git clone <repository_url>
cd <repository_folder>
```

### 2. Install Dependencies
Install dependencies manually:
```sh
pip install pandas numpy matplotlib seaborn sklearn shap
```

### 3. Download and Place Data
Download the data named as 'MLE-Assignement'. Update the path in `ImagoAI | MLE Assignment.ipynb` if necessary.

## Running the Code
Execute the main script using your compiler


### Expected Workflow
1. Load dataset
2. Perform exploratory data analysis
3. Scale features
4. Apply PCA for dimensionality reduction
5. Perform feature engineering
6. Train multiple models including Random Forest, Neural Networks, Gradient Boosting, and a Stacking Ensemble
7. Evaluate models and select the best one based on R² score
8. Interpret the best model using SHAP

## Model Interpretation
SHAP (SHapley Additive exPlanations) is used to interpret the best-performing model by visualizing the impact of features on predictions.

## Logging
The script logs events and errors during execution, ensuring easy debugging and performance monitoring.

## Contact
For any issues or inquiries, please reach out via email or the project's issue tracker.

