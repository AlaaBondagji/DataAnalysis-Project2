## Project Title
Naive Bayes Classifier with Iris Dataset
## Project Overview
This project implements a Naive Bayes classifier to predict the species of flowers from the Iris dataset. The Naive Bayes algorithm is based on Bayes' Theorem and is well-suited for classification tasks involving categorical or continuous input features.

The Iris dataset is a famous dataset for machine learning, containing 150 samples from three species of Iris flowers (Iris-setosa, Iris-versicolor, and Iris-virginica), with four features: sepal length, sepal width, petal length, and petal width.
## Libraries Used

To run the code successfully, the following Python libraries are required:

 - pandas: For data loading and manipulation.
 - scikit-learn (sklearn): For building and evaluating the Naive Bayes model.
 - numpy: For handling numerical operations.
 - matplotlib or seaborn: For data visualization (optional, if required for plotting).
## How to Run the Code
Step 1:
 - Download the project files or clone the repository to your local machine.

 Step 2:
 - If using an external CSV, ensure that the dataset file iris.csv is placed in the project folder. If using the built-in dataset from sklearn, this step is not needed.

Step 3: Run the Python Script
Run the provided Python script to apply the Naive Bayes classifier on the Iris dataset. The script will:
 - Load the dataset from sklearn.datasets or a local CSV file.
 - Preprocess the data by splitting it into training and testing sets.
 - Train a Naive Bayes classifier using the training data.
 - Evaluate the classifier on the test data and display the accuracy.

Step 4: View Results
 - After running the script, the output will display the accuracy of the classifier on the test set.
You can customize the split ratio, model parameters, or display additional metrics like confusion matrix or precision/recall.

## How the Dataset Was Used
1- Data Preprocessing:
   - The dataset was loaded and the features (sepal length, sepal width, petal length, and petal width) were used to train the classifier.
  - The target variable (species) was encoded into numerical values for classification.
  - The dataset was split into training (80%) and testing (20%) sets.

2- Model Training:
  - A Naive Bayes classifier (GaussianNB) was applied to the training data to create the model.
  - The model was trained on the training data to learn the relationships between features and species.

3- Model Evaluation:
  - The trained model was evaluated on the test set, and the accuracy score was printed.
  - Additional metrics like confusion matrix can be added for more detailed analysis.

4- Analysis Goal:
 - The analysis aimed to classify iris flower species based on their features and evaluate the performance of the Naive Bayes classifier. The model can be used to explore how well Naive Bayes performs in simple classification tasks
