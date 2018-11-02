# Data Filteration and Pre Processing

The follwing dataset is a unstructured data, common in Big Data realm.

You need to do the Following in this assignment:

1. Download Dataset
2. Clean the Dataset (for each sentence)
    * remove blank spaces from each sentence
    * remove one or multiple special characters from each sentence.
3. Remove stop words from all the sentences in the dataset without using any library.
   
   In computing, stop words are words which are filtered out before or after processing of natural language data (text) Example (the, is , and ,..). 
   
   Refer [wiki](https://en.wikipedia.org/wiki/Stop_words)

   Refer [What are Stop Words](https://searchmicroservices.techtarget.com/definition/stop-word)

Find a list of common stop words from [here](https://gist.github.com/sebleier/554280#file-nltk-s-list-of-english-stopwords)

Example 

```
Line: This is a sample line, in some dataset reperesenting meaningful text.

Expected output:
fltrd_line: sample line some dataset representing meaningful text
```
4. Get count of all word frequency in the dataset.
    
5. Word should contain atleast four characters.
   
6. Show top 5 words having maximum frequency.
   
7. Plot a bar graph with top 5 words.
   
8. Plot a pie chart with top 5 words.


### Library Reference

For Charts :
-   https://plot.ly/python/

For Data Structures
- https://www.w3schools.com/python/python_dictionaries.asp
- https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python