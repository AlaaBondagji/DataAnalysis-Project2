## Project Title
Spam Emails
## Dataset Overview
This project involves applying Sentiment Analysis to a dataset that contains messages categorized as either spam or ham (not spam). The analysis involves several preprocessing steps such as cleaning, removing frequent words, and lemmatization, which help prepare the data for a sentiment classifier. The goal is to identify patterns in the text that can distinguish spam from ham and to visualize the most frequent words in each category.
## Dataset
  - Dataset Name: (spam)
  - Source:(https://drive.google.com/file/d/19Yz5vBQ3T174xeSOOqVzw3rWWm39stsf/view)
  - File Format: CSV
## Libraries Used
 - pandas: For handling the dataset and data manipulations.
 - matplotlib: For creating visualizations.
 - wordcloud: For generating word clouds from text data.
 - nltk: For natural language processing, including stop words and lemmatization.
 - plotly: For interactive visualizations such as bar charts.
 - collections: To count and work with word frequency.
 - sklearn: Machine learning algorithms (Naive Bayes classifiers) and metric
## How to Run the Code
   Step1: Clone the Repository Clone the repository to your local machine.

   Step 2: Place the Dataset: Ensure that the file (spam_Emails_data.csv) is placed in the project folder.

   Step3: Open the Jupyter notebook named main_code.ipynb and run all cells to execute the code. This will include:
    
    - Loading the dataset using the pandas library.
    - Preprocessing the data by cleaning the text and removing unnecessary words.
    - Applying the Naive-Bayes classification model to determine whether the messages are Spam or Ham.
    - Generating word clouds to visualize the most common words in each category.

 Step4: View the Results
   - After execution, the results will display, including word clouds and the top 10 most common words in each category (Spam and Ham).
## How the Dataset Was Used
1-Data Preprocessing:
  - Text Cleaning:
Convert text to lowercase and remove URLs, special characters, punctuation, and numbers to retain meaningful words.
  - Stop Words Removal:
Filter out common words that don’t add value (e.g., “the,” “and”).
  - Frequent Words Removal:
Remove high-frequency words that are not relevant for classification.
  - Lemmatization:
Standardize words to their root forms, reducing vocabulary complexity and improving feature creation.

2-Sentiment Analysis:
   - Classification: Applied Naive Bayes Classifier to categorize messages as spam or ham.
   - Visualization: Generated word clouds to highlight common words in spam and ham messages. Bar charts show the top 10 frequent words in each category.

3-Analysis Goal:
The goal is to classify text messages as spam or ham to filter out unwanted messages, enhancing the user experience in messaging services and reducing spam.

