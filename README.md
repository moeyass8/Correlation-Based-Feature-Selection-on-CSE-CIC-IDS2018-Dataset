# Correlation-Based-Feature-Selection-on-CSE-CIC-IDS2018-Dataset
This python code will process the CFS algorythm on CSE-CIC-IDS2018 Data set, you just need to input the dataset path in your environment and a dictionary (JSON file) to enter the datatype of each row 

- The CFS.py will get the column types from the dictionary.txt and choose the correct correlation type to perform using a "def" function. 
- the file will compute the merit of each set (you need to look at the algorithm at wikipedia to know how it computes the merit)
- Best First Search is used to seach for feature set

Along the processing the program will print the best feature sets, the last feature set (when finish is printer) will be the most correlated set. 
