# Analysis
Here are the key insights from the EDA and preprocessing steps:
- Large dataset with nearly one million observations and numerous features
- Highly imbalanced classes: 98.74% non-fraud vs 1.26% fraud transactions
- No missing values in the training dataset
- Presence of approximately 400,000 duplicate observations with different labels
- Normalized variables (pc0-pc16) show minimal variation and narrow distributions
- High multicollinearity among variables, with some showing perfect correlation (e.g., pc4 with pc9, pc8 with pc6)
- Potential overfitting risk due to high multicollinearity
- Difficulty in removing correlated variables due to intentional obfuscation for anonymity
- Removal of duplicates in non-fraud (label 0) data to address class imbalance
- Identification of specific patterns in non-borrower user data, leading to consideration of their removal

Here are the key insight from modeling:
- Logistic Regression is used because of its simplicity and interpretability, LR is highly effective in fraud detection, particularly for understanding predictor relationships and predicting unknown or multi-labeled data points.
- The use of regularization (L1/L2) addresses multicollinearity, improving the model's stability and performance
- Logistic Regression outperformed other models (LightGBM, FA-CNN, RLS) with a significantly higher average precision score of 0.8138, compared to other models' performance.

# Conclusion
Logistic Regression proved to be an optimal choice for detecting financial fraud in the given dataset due to its efficiency in handling unknown labels and multicollinearity. The model's superior performance in comparison to more complex models demonstrates its reliability, particularly when preprocessing techniques like regularization are applied. Despite challenges like large datasets and class imbalance, LR emerged as a robust and effective model for the task at hand.
