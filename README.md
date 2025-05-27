# ML-Model
Global Tech University Admissions Optimizer 

This project addresses a real-world regression case study for **Global Tech University (GTU)**, a research-focused institution seeking to improve the speed and accuracy of its admissions and merit scholarship decisions through machine learning.

Topics Covered:

1. Problem Framing
Real-world context: International student admissions and merit scholarship allocation.

Business goal: Support fast and accurate admit decisions under time and budget constraints.

2. Exploratory Data Analysis (EDA)
Data structure understanding.

Summary statistics of features like GRE, TOEFL, CGPA, SOP, LOR, etc.

Correlation matrix to detect linear relationships and potential multicollinearity.

Visualizations (scatter plots, histograms, heatmaps).
 3. Regression Modeling
a. Multiple Linear Regression
Predicts “Chance of Admit” using academic and subjective features.

Helps identify impact of individual features (like GRE or CGPA).

VIF analysis for multicollinearity handling.

4. Decision Tree Regressor
Interpretable model showing decision paths.

Useful for “what-if” scenarios.

Hyperparameter tuning (max_depth, min_samples_split, min_samples_leaf) using GridSearchCV.

5. Random Forest Regressor
Ensemble method for higher accuracy and robustness.

Handles nonlinear interactions between variables.

Hyperparameter tuning using RandomizedSearchCV for:

n_estimators

max_depth

min_samples_split

min_samples_leaf

max_features

6. Feature Selection
Used feature_importances_ from Random Forest to rank features.

Retrained models using only top 5 features to simplify models.

Compared performance with full-feature models.

 7. Handling Multicollinearity
Variance Inflation Factor (VIF) used to detect collinearity in linear regression.

Removed redundant features for more reliable coefficients.

8. Model Evaluation
Metrics like Mean Squared Error (MSE) used to compare model performance.

Train/test split for validation.

Summary table of model performance under different feature sets.

9.Sample Inference
Predicted admit chances for a test applicant profile (e.g., GRE 322, TOEFL 111, CGPA 8.9).

Interpreted Decision Tree prediction path.

