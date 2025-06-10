# Free_flap_failure
## Free Flap Failure Prediction
## No patient private data within the .ipynb file

This repository contains a Jupyter notebook that trains several machine learning models to predict the risk of free flap failure in reconstructive surgery. The notebook demonstrates data preprocessing, model selection and evaluation using patient demographic information, laboratory results, cancer characteristics and surgical details.

## Repository contents

| File | Description |
|------|-------------|
| `20231020_try_with_HTN_and_smoking.ipynb` | Main notebook that builds logistic regression, random forest, support vector machine, and XGBoost models. It loads the dataset (CSV not included), performs resampling and feature engineering, and compares model performance. |
| `README.md` | Project overview and usage instructions. |

## Usage

1. Install the Python libraries referenced in the notebook (e.g., `pandas`, `scikit-learn`, `xgboost`).
2. Open the notebook with Jupyter or Google Colab.
3. Provide your own dataset with columns similar to those used in the notebook. The dataset should include patient background info, lab data, cancer profiles, and operation details along with a `Failure` target column.
4. Run the cells to train and evaluate the models.

## Background

Free flap procedures can fail due to complications. Predicting failure helps clinicians plan interventions and improve outcomes. This project uses anonymized clinical data to train predictive models. The approach includes oversampling techniques, hyperparameter tuning and cross-validation to evaluate sensitivity, specificity and ROC-AUC.

## Contributing

Feel free to open issues or pull requests if you improve the code or documentation.
