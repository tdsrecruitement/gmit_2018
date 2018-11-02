# Sentiment Analysis

Sentiment Analysis is the process of computationally identifying and categorizing opinions expressed in a piece of text, especially in order to determine whether the writer's attitude towards a particular topic, product, etc. is positive, negative, or neutral.

In this assignment you are given with a dataset, containing text/reviews/conversation.

You need to do the following:

1. Download [Dataset](sentiment_dataset.txt)
2. Given below is a Sentiment array
   
   ```
   Positive Keywords
   [happy, joy, contentment, pleasure, contentedness, love, awesome, amazing, cool, crazy, jaw-dropping, phenomenal]

   Negative Keywords
   [unhappy, sorrowful, unsatisfactory, regretful, depressed, downcast, miserable, poor, bad, worse, hell, disgusting, waste]
   ```
3. Frequency of Positive keywords in a sentence
4. Freq of Negative keywords sentence
5. Based on Frequency count calculate  for positive sentiment
```
	text : "This product is really awesome, I'm loving it. Awesome Build quality. Poor delivery time."

	Positive Keywords: [Awesome, Loving]

    Negative Keywords: [Poor]

	Positive Weight: 
    frequency of (awesome) + frequency of (loving) = 2 + 1 = 3

    Negative Weight: frequency of (poor) = 1
```
6. Find the Sentences having Positive Weight greater than 5
   
7. Find the Sentences having Negative Weight greater than 5
   
8. Plot Bar chart for positive (X: Keywords, Y: Frequency count of keywords)
		find all the frequency of positive keywords in the dataset
		plot the top 5 keywords with their frequncy

9. Plot Bar chart for negative (X: Keywords, Y: Frequency count of keywords)
		find all the frequency of positive keywords in the dataset
		plot the top 5 keywords with their frequncy

### Library Reference

For Charts :
-   https://plot.ly/python/

For Data Structures
- https://www.w3schools.com/python/python_dictionaries.asp
- https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python