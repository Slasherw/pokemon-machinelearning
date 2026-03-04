🔴⚪Legendary Pokémon Classification
This project focuses on building and evaluating Machine Learning models to predict whether a Pokémon is "Legendary" based on its combat stats and physical characteristics.

Key Highlights:

Robust Preprocessing: Handled missing values, applied label encoding, and standardized features to prevent data leakage and dominant feature bias (e.g., dropping base_experience).

Advanced Feature Selection: Utilized XGBoost Gain, Permutation Importance, and Nested Cross-Validation (Outer/Inner CV) to extract the top 5 optimal features.

Model Tuning: Trained and optimized KNN, XGBoost, and Neural Network (MLP) using GridSearchCV.

Results: Both XGBoost and Neural Network achieved an outstanding 98% Accuracy and 100% Precision, demonstrating perfect reliability in identifying Legendary Pokémon.
