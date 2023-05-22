# CODEBREAK 1.0 - NLP with Disaster Tweets

Project Description

This project utilizes a pipeline-based approach to classify text data into two categories: "Disaster" and "Not Disaster." The pipeline consists of a TF-IDF vectorizer for text preprocessing and a logistic regression classifier for the prediction task. The project involves loading datasets, exploring the data, splitting it into training and validation sets, training the pipeline on the training data, evaluating the model on the validation set, generating classification reports and confusion matrices, calculating precision, recall, F1-score, and support metrics, applying the pipeline on the test data, and preparing a submission file.

## Usage

To use this project, follow these steps:

1. Make sure you have the required libraries installed: pandas, numpy, scikit-learn.

2. Download the following files and place them in the same directory as this script:
   - train.csv: the training dataset containing text and target columns.
   - test.csv: the test dataset containing text column.
   - sample_submission.csv: a sample submission file.

3. Run the script in a Python environment.

## Results

After running the script, you will see the following results:

### Pipeline

The pipeline consists of two steps: TF-IDF vectorization and logistic regression. This section displays the pipeline's structure.

### Classification Report

This section presents the classification report, including precision, recall, F1-score, and support metrics for each class (Not Disaster and Disaster) on the validation set.

### Confusion Matrix

The confusion matrix illustrates the performance of the model by showing the number of true positives, true negatives, false positives, and false negatives on the validation set.

### Results

This section provides a summary of the precision, recall, F1-score, and support metrics for each class (Not Disaster and Disaster) on the validation set.

### Submission

The submission dataframe is displayed, showing the predicted target values for the test dataset.


## Contact

For any questions or suggestions, please feel free to contact [Taaran Jain](mailto:taaranjain16@gmail.com).
