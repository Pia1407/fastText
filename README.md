# Use fastText for Bag of Tricks
Libraries used are pandas, re, random

Data Cleaning 
1. Removing all special features and keep only words and spaces.
2. Replacing multiple spaces with a single space
3. Convert to lowercase and strip leading/trailing spaces
4. Save the cleaned data in a new column

Format Conversation
1. Convert the final data into fasttext format __level__
2. Save the converted file into .txt file

Split the txt file into Train and Text to predict and validate the data
1. Train data is splitted into 80% and train and validate are 10% each.
