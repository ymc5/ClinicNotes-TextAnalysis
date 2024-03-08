# ClinicNotes-TextAnalysis
Text analysis activities conducted on MIMIC dataset

---

# MIMIC-III Discharge Notes Word Tokenization

This script performs word tokenization on the clinical notes in the MIMIC-III discharge dataset, calculates the average number of tokens before and after data cleaning, and adds the results to the dataframe.

## Description

The script utilizes the NLTK library for word tokenization and data cleaning. 

1. **Load Data**: Load the MIMIC-III discharge notes dataset into a pandas dataframe.

2. **Word Tokenization (Before Cleaning)**: Tokenize the clinical notes text for each patient and calculate the number of tokens. Add a new column called "num_of_tokens" to the dataframe to store this information.

3. **Word Tokenization with Data Cleaning (After Cleaning)**: Perform word tokenization similar to the previous step but with additional data cleaning steps. Remove punctuations, stopwords, and numbers from the tokenized text. Calculate the number of cleaned tokens and add a new column called "num_of_cleaned_tokens" to the dataframe.

4. **Calculate Averages**: Calculate the average number of tokens before and after data cleaning.

---

