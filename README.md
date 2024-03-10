# Patient Condition Classification Using Drug Reviews

This project aims to classify patient conditions based on drug reviews using machine learning techniques. The dataset contains patient reviews of various drugs along with their corresponding conditions. The goal is to develop models that can accurately predict the patient condition based on the review text.

## Dataset

The dataset used in this project consists of patient drug reviews with the following columns:

- `Unnamed`: Index column
- `drugName`: Name of the drug being reviewed
- `condition`: Medical condition being treated by the drug
- `review`: Patient review text
- `rating`: Rating given by the patient
- `date`: Date of the review
- `usefulCount`: Number of users who found the review useful

## Objective

The main objectives of this project include:

- Performing exploratory data analysis (EDA) to understand the distribution of ratings, conditions, and drugs in the dataset.
- Preprocessing the text data, including tokenization, removing stop words, and vectorizing the text using TF-IDF.
- Building machine learning models to classify patient conditions based on drug reviews.
- Evaluating the models using accuracy metrics and confusion matrices.
- Analyzing model performance to identify potential overfitting or underfitting.

## Models

The following machine learning models are used for classification:

- MultinomialNB
- Naive Bayes
- Random Forest
- Support Vector Machine (SVM)


## Evaluation Metrics

The models are evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score

## Instructions

1. Install the required libraries specified in the `requirements.txt` file.
2. Run the Jupyter Notebook `classification.ipynb` to execute the code.
3. Follow the step-by-step instructions in the notebook to preprocess the data, train the models, and evaluate their performance.
4. Analyze the results and conclusions drawn from the model evaluations.

## Results

The results of the model evaluations are presented in the notebook along with visualizations such as confusion matrices and classification reports.

## Conclusion

Based on the model evaluations, conclusions are drawn regarding the effectiveness of the models in classifying patient conditions using drug reviews. Recommendations for further improvements or analysis may also be provided.
