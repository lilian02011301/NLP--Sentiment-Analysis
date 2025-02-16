# NLP--Sentiment-Analysis
This project implements a text classifier to identify sentiment in a dataset of approximately 27,000 entries, split into 80% training and 20% testing. The classifier is trained using LinearSVC and evaluated through cross-validation and error analysis.

# Data Preprocessing
- Modify parse_data_line() and pre_process() to clean and tokenize text.
- Use print statements to verify the output.

# Feature Extraction
- Implement a function to return word-based feature dictionaries.
- Avoid creating a global dictionary with all words.
- Validate feature extraction using print(train_data[0]).
# Cross-Validation
- Manually implement k-fold cross-validation inside the provided loop.
- Train and evaluate on different training subsets.
- Compute precision, recall, f-score, and accuracy.
# Error Analysis
- Generate a confusion matrix and adjust function calls if necessary.
- Extract and analyze False Positives & False Negatives for the FAKE label.
- Save errors to a file rather than printing in the notebook.
- Provide insights on error patterns and potential improvements.

# Improving Preprocessing & Feature Extraction
- Start with a new notebook based on previous work.
- Experiment with different preprocessing techniques.
- Justify marginal improvements in accuracy/f-score.
- Avoid data leakage by ensuring test data is not used in training.

# Expected Outcome
A trained LinearSVC classifier that can classify sentiment with improved accuracy through iterative feature engineering and preprocessing enhancements.
