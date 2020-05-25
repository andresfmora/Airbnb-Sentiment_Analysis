# Libraries used

1) Anaconda Distribution  of Python 3

2) TextBlob for sentiment Analysis. https://textblob.readthedocs.io/en/dev/

3) langdetect for language identification. https://pypi.org/project/langdetect/

# Project Purpose

   I've always been interested to implement a off the shelf sentiment analysis package to see how well it would work. Text sentiment analysis is really interesting to me in two contexts: Customer Reviews, and politics. The AirBnB dataset, as part of the Udacity nanodegree program, gave me a great opportunity to explore the validity of using text sentiment analysis on reviews and some of the possible business cases this would drive. Please see the blog post here for this analysis.
    
https://medium.com/@mora07801/sentiment-analysis-is-cool-88a9bd4bd6b

# Files in Repository

1) This ReadMe.md File

2) AirBNB.ipynb jupyter notebook

3) Datasets folder containing Boston and Seattle Listings/Reviews Datasets

# Summary of Results

1) The TextBlob sentiment analysis worked great. It could clearly identify positive reviews and negative reviews based on checking a sample of the output.

2) TextBlob could not parse reviews written in other languages so I used the langdetect package to identify them and filter non-english speaking for the purpose of this analysis.

3) I did some correlation analytics on the numeric ratings that customer left and the sentiment scores. While there is some vague positive correlation between the sentiment score and the overall rating of the listing, it is not very strong. Has a Pearson R score of only .37. This brings up other questions to explore on why this would not match up.

# Acknowledgement and Thanks

Want to thank the two awesome packages I mentioned up above, TextBlob and langdetect, for easy of use and well documented packages. 

Also thanks to AirBnB for making these datasets public through Kaggle.

https://www.kaggle.com/airbnb/seattle