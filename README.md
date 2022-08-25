# Multinomial-Naïve-Bayes-Classifier---The-Youtube-Dataset

**Context and Objective:** In this use case, we will explore a database extracted from the Youtube website. This database will be used to build multinomial Naïve Bayes classifier capable of filtering spam messages and ham messages. 

**Datasets:**  
The database contains five CSV files, each with a set of comments from five Youtube videos. Each of the CSV files contains the following columns:  
- COMMENT_ID: Id of the comment.  
- AUTHOR: The author of the comment.   
- DATE: Date of the comment.  
- CONTENT: The text of the comment.  
- CLASS: The class to which the comment belongs. 0 designates a harmless ham comment, while 1 designates a spam. 

Our task is to analyse the data from all five CSV files and train our algorithm to make good predictions on new data.  

**Note:** This code was written on Jupyter Notebook.  
**Language:** Python.  
**Packages:** numpy, pandas, glob, sklearn, matplotlib, seaborn.
 
