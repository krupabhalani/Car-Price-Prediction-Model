# Car-Price-Prediction-Model

Description: Developed a regression model to predict the prices of used cars based on listing attributes, focusing on extensive data cleaning, categorical encoding, and pipeline-based automation for consistent preprocessing and prediction.

Loaded raw car listing data into a pandas DataFrame and performed data cleaning to handle missing, inconsistent, and noisy user-entered records.

Split the dataset into training (80%) and testing (20%) subsets for model evaluation.

Applied OneHotEncoder to categorical features (name, company, fuel_type) using make_column_transformer to selectively encode columns while preserving numerical data.

Built a scikit-learn pipeline combining preprocessing and a Linear Regression model for streamlined fitting and prediction.

Trained and tested the model, achieving an R² score of 0.7011 (~70.1%) on the test set, indicating strong predictive performance on unseen data.

Serialized the final model using pickle for future deployment and reuse.

Tech Stack: Python, pandas, scikit-learn, OneHotEncoder, Pipeline, pickle
