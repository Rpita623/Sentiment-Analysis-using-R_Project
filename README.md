# Sentiment Analysis using R: Project
## Aim of Project
Building a sentiment analysis model to categorize words based on their sentiment. That is, whether the words are positive or negative and further analysis. 

## Developing Sentiment Analysis Model in R
Dataset/Package: ```janeaustenR```

First, I made use of the ```tidytext``` package that consists of sentiment lexicons present in the dataset of ```sentiments```.

Among the various lexicons, I have retrieved the ```bing``` lexicon, which classifies the sentiments into a binary category of negative or positive. 

I imported the libraries ```janeausten```, ```stringr``` and ```tidytext```. The ```janeaustenr``` package which provided me with full texts for Jane Austen's 6 completed novels, ready for text analysis. These novels are "Sense and Sensibility", "Pride and Prejudice", "Mansfield Park", "Emma", "Northanger Abbey", and "Persuasion".```tidytext``` allowed me to perform efficient text analysis on the data. 

After performing the tidy operation on the text such that each row contains a single word, I used the book 'Emma' and derived its words to implement the sentiment analysis model.

I then segregated the data into separate columns of positive and negative sentiments. After that, using ```mutate()```, I calculated the total sentiment, that is, the difference between positive and negative sentiment.

**First visualisation:** the words present in the book “Emma” based on their corrosponding positive and negative scores. I counted the most common positive and negative words that are present in the novel.

**Second visualization:** sentiment score. I plotted the scores along the axis that is labeled with both positive as well as negative words. 

**Final visualization:** I created a wordcloud that described the most recurring positive and negative words. 
