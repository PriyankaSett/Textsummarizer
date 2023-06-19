## Text Summarizer 

- In this task, we have taken a text data file (which can be .pdf/.txt/.docx)and summarized the content using `NLTK library` and `Genism library`. 

- To do this, first the foremost we need to count the number of occurances of each word in the text and then find their relative frequencies. On the basis of this the a score is assigned to every sentences by adding up relative frequencies of the words that occur in that particular sentence. 

- We also obtain a mean score for the whole document. Now, to get the summary, we choose those sentences for which the sentence score is 1.2 times of the mean score. This '1.2' can be adjusted as required. We have found that this '1.2' factor works best for us. With this value we do not loose significant information inside small sentences. As this value increases the summary consists the information from big sentences.  