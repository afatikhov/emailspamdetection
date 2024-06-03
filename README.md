# Email Spam Detection
This project aims to create a machine learning model for email spam detection using a Kaggle dataset. The dataset consists of emails categorized as either "ham" (not spam) or "spam". The model utilizes a Multinomial Naive Bayes classifier for prediction.

## Content
The project covers the following steps:

### Understanding Data: Initial exploration of the dataset to comprehend its structure and characteristics.
### Data Processing: Preprocessing steps including converting labels to numerical values, handling duplicates, and converting text to lowercase.
### Data Visualization: Visualizing the distribution of email categories and exploring word frequencies using a word cloud.
### Creating Dataset for Model: Preparing the dataset for model training using TF-IDF vectorization.
### Creating Model: Training various machine learning models including Bagging Classifier, Extra Trees Classifier, Gradient Boosting Classifier, XGBoost, Support Vector Classifier (SVC), Multinomial Naive Bayes, Decision Tree Classifier, Logistic Regression, Random Forest Classifier, and AdaBoost Classifier.
### Interpretation of Results: Analyzing model performance and selecting the best-performing model for further use.
## Usage
## To use this project:

### Clone this repository.
### Install the necessary libraries mentioned in the requirements.txt file.
### Run the provided Jupyter notebook email_spam_detection.ipynb.
### Follow the step-by-step instructions in the notebook to explore the dataset, preprocess the data, train the models, and interpret the results.
## The Support Vector Machines (SVC) model has demonstrated the best performance with 99% accuracy on validation data, suggesting its suitability for deployment in real-world scenarios.
