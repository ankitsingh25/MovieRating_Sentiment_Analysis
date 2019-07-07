# MovieRating_Sentiment_Analysis

The basic Natural Language Processing (NLP) project with the Rotten Tomatoes Dataset.

The dataset originally contained about 4,80,000 reviews of users of various movies which 
was extracted from their site.

In this project, I reduced the size of dataset to 50,000 reviews and trained:tested my classifer
using only 1600:400 reviews.Former was done so as easily upload dataset to github w.r.t < 25MB
limit while latter was done to achieve results in less time.It is obvious that more data will 
lead to more accuracy but demands huge amounts of resources not available with me as well as 
sometimes it surpasses google colab resources too.I intend to create a memory efficient model in future.

The nltk library is used in this project.

Accuracy achieved is 66.5% with a training size of only 1,600. 
