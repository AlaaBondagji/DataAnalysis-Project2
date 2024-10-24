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
 - Ensure that all required libraries are installed. 

Step 3: Run the Python Script
Run the provided Python script to apply the Naive Bayes classifier on the Iris dataset. The script will:
 - Load the dataset from sklearn.datasets.
 - Preprocess the data by splitting it into training and testing sets.
 - Train a Naive Bayes classifier using the training data.
 - Evaluate the classifier on the test data and display the accuracy.

Step 4: View Results
 - After running the script, the output will display the accuracy of the classifier on the test set.
 - Additional metrics like confusion matrix and F1 score will also be displayed for detailed performance evaluation.
## How the Dataset Was Used
1-Data Preprocessing
   - The dataset is split into training (70%) and testing (30%) sets using train_test_split.
   - The target labels are encoded into numerical values.

2-Model Training
  - The Gaussian Naive Bayes model is trained using the training set.
  - The classifier learns to predict flower species based on the input features.

3-Model Evaluation
  - The model is evaluated using the test set, and the accuracy and F1 score are printed.
  - A confusion matrix is generated to visualize the performance of the classifier across different species.

4- Analysis Goal:
 - The analysis aimed to classify iris flower species based on their features and evaluate the performance of the Naive Bayes classifier. The model can be used to explore how well Naive Bayes performs in simple classification tasks
