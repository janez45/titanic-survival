## Kaggle's marquee titanic competition. Leverages real-world passenger data to predict survival of others.
#### Process:
- Data Analysis: Visualization using **matplotlib**, examining correlations and similar groupings
- Cleaning and preprocessing the data **(Pandas)**:
  - Filled missing values via research and highly correlated fields
  - Extracted information of higher value from the existing data via feature engineering
  - Preprocessed data via standard scaling
- Fitting the model: Trained and tuned a RandomForestClassifier model from **scikit-learn**, using KFold Cross Validation and GridSearchCV

### Achieved up to 88.27% accuracy on train test split and 91.01% accuracy on KFold Cross Validation.
