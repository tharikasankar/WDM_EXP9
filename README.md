### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 24/08/2024
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
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


### Output:
![Screenshot (150)](https://github.com/user-attachments/assets/3e9965a0-a68f-44bb-ba2b-2c4130e9f367)
![Screenshot (149)](https://github.com/user-attachments/assets/9cdba438-e764-472c-9a09-44bae41a999e)
![Screenshot (151)](https://github.com/user-attachments/assets/43576a90-8fbe-40e7-b2e1-c7a35b76bdf4)
![Screenshot (152)](https://github.com/user-attachments/assets/148fa01f-0836-4c33-93db-4a5d8c923f43)


### Result:

Thus, the preprocessing technique on Twitter Data using Rapidminer is implemented successfully.
