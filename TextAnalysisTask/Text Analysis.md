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
1. Data Preprocessing:
 - Text Cleaning: The raw text in the dataset was cleaned by converting it to lowercase, removing URLs, special characters, punctuation, and numbers. This step ensures that only meaningful words are kept for analysis.
 - Stop Words Removal: Common English stop words (e.g., 'the', 'and', 'is') were removed from the text to reduce noise and focus on more important words.
 - Frequent Words Removal: The most frequent words that occur in the text were identified and removed. These words may appear too often and provide little value for distinguishing between sentiments (spam or ham).
 - Lemmatization: Words in the dataset were lemmatized using the NLTK WordNetLemmatizer to convert them to their base form (e.g., 'running' becomes 'run'). This reduces the complexity of the dataset and helps create better features for the model.
2. Sentiment Analysis:
 - Classification: Sentiment analysis was applied to the preprocessed text using the Naive-Bayes Classifier to identify whether each message is spam or ham. The classifier was trained to recognize patterns in the text to accurately predict the sentiment.
 - Visualization: Word clouds were generated to visually explore the most frequent words in spam and ham messages. Bar charts were also used to show the top 10 most common words in each category.
3. Analysis Goal:
 - The goal of the analysis was to detect and categorize text messages as spam or ham based on their content. This classification can help in filtering unwanted messages, improving user experience in messaging services, and preventing spam.

