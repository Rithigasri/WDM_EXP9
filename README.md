# EXPERIMENT 09: PREPROCESSING ON TWITTER DATA USING RAPIDMINER
## DATE: 13.04.2024
## AIM: 
To implement preprocessing technique on Twitter Data using Rapidminer.
## DESCRIPTION: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

## PROCEDURE:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


## OUTPUT:
![image](https://github.com/Rithigasri/WDM_EXP9/assets/93427256/12a869f4-1ae7-4f99-aa62-d4dc5f57c789)
![image](https://github.com/Rithigasri/WDM_EXP9/assets/93427256/f0a6f9a9-5000-424d-b42c-2661ad97fc1c)
![image](https://github.com/Rithigasri/WDM_EXP9/assets/93427256/efa23b8a-e9fd-41cb-ac62-7744260907fc)
![image](https://github.com/Rithigasri/WDM_EXP9/assets/93427256/db96ca88-18ee-48a7-84df-c0fe22f916bb)

## RESULT:
Thus, the preprocessing technique on Twitter Data using Rapidminer is implemented successfully.
