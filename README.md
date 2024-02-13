
## Dataset

The dataset includes a wide range of features related to customer and quote information. It is split into a training set (65000 entries) and a test set (173836 entries), with features like geographic information, coverage details, and customer characteristics.

## Methodology

1. **Data Preparation**: Loaded the datasets, handled categorical variables, and applied feature engineering to select the top 100 features based on variance.
2. **Exploratory Data Analysis**: Visualized the distribution of the target variable and analyzed feature importance.
3. **Model Training and Evaluation**: Trained Decision Tree, Random Forest, MLPClassifier, and KNN models. Evaluated their performance using accuracy and confusion matrix. Applied SMOTE to address class imbalance.
4. **Ensemble Learning**: Implemented stacking with multiple base models to improve prediction accuracy.
5. **Hyperparameter Tuning**: Used RandomizedSearchCV to optimize the MLPClassifier parameters.
6. **Prediction**: Made predictions on the test dataset and prepared a submission file for Kaggle.

## Results

The project demonstrates the effectiveness of ensemble methods and hyperparameter tuning in improving model performance. Random Forest and MLPClassifier with optimized parameters showed promising results.

## Usage

The project is structured as a Jupyter Notebook, making it easy to follow the analysis and model training process. You can clone the repository and run the notebook in Google Colab or your local Jupyter environment.

## Conclusion

This project highlights the importance of feature engineering, model selection, and hyperparameter tuning in the context of insurance quote conversion prediction. Ensemble methods, particularly stacking, significantly contributed to the accuracy of the predictions.

## Future Work

Further improvements can be explored through more advanced models like XGBoost or LightGBM, deeper hyperparameter tuning, and more sophisticated feature engineering techniques.
