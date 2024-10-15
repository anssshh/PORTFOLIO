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
