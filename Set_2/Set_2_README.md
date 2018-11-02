# Data Filteration and Pre Processing

The follwing dataset is a unstructured data, common in Big Data realm.

You need to do the Following in this assignment:

1. Download [Dataset](set2_dataset.txt)
2. Clean the Dataset (for each sentence)
    * remove blank lines from the dataset
    * remove one or multiple special characters from each sentence.
3. Remove stop words from all the sentences in the dataset without using any library.
   
   In computing, stop words are words which are filtered out before or after processing of natural language data (text) Example (the, is , and ,..). 
   
   Refer [wiki](https://en.wikipedia.org/wiki/Stop_words)

   Refer [What are Stop Words](https://searchmicroservices.techtarget.com/definition/stop-word)

Find a list of common stop words from 
```
["i", "me", "my", "myself", "we", "our", "ours", "ourselves", "you", "your", "yours", "yourself", "yourselves", "he", "him", "his", "himself", "she", "her", "hers", "herself", "it", "its", "itself", "they", "them", "their", "theirs", "themselves", "what", "which", "who", "whom", "this", "that", "these", "those", "am", "is", "are", "was", "were", "be", "been", "being", "have", "has", "had", "having", "do", "does", "did", "doing", "a", "an", "the", "and", "but", "if", "or", "because", "as", "until", "while", "of", "at", "by", "for", "with", "about", "against", "between", "into", "through", "during", "before", "after", "above", "below", "to", "from", "up", "down", "in", "out", "on", "off", "over", "under", "again", "further", "then", "once", "here", "there", "when", "where", "why", "how", "all", "any", "both", "each", "few", "more", "most", "other", "some", "such", "no", "nor", "not", "only", "own", "same", "so", "than", "too", "very", "s", "t", "can", "will", "just", "don", "should", "now"]
```

Example 

```
Line: This is a sample line, in some dataset reperesenting meaningful text.

Expected output:
fltrd_line: sample line some dataset representing meaningful text
```
1. Get count of all word frequency in the dataset.
    
2. Word should contain atleast four characters.
   
3. Show top 5 words having maximum frequency.
   
4. Plot a bar graph with top 5 words.
   
5. Plot a pie chart with top 5 words.


### Library Reference

For Charts :
-   https://plot.ly/python/

For Data Structures
- https://www.w3schools.com/python/python_dictionaries.asp
- https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python