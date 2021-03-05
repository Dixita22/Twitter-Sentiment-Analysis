# Twitter-Sentiment-Analysis

## SENTIMENT ANALYSIS OF TWITTER (AMAZON INDIA, FLIPKART, SNAPDEAL)

### SENTIMENT ANALYSIS: 

Sentiment analysis is a text analysis method that detects polarity (e.g. a positive or negative opinion) within text, whether a whole document, paragraph, sentence, or clause.
Understanding people’s emotions is essential for businesses since customers are able to express their thoughts and feelings more openly than ever before. By analysing customer feedback, from survey responses to social media conversations, brands are able to listen attentively to their customers, and tailor products and services to meet their needs.

It is the process of finding out the sentiment of a particular sentence/paragraph/text. 
Examples:
- This mayor has done a really good job in his tenure (positive sentiment) 
- The product I have received is red in colour (neutral sentiment) 
- I had a bad experience during this cab ride (negative sentiment).

The data sources for sentiment analysis includes the following:
- Twitter tweets 
- Facebooks comments 
- Online reviews 
- SMS/emails/messages 
- Novels, books 
- Any other text-based sources like books/newspapers/magazines/etc.

### TWITTER DATA:
Twitter is an online microblogging tool that disseminates more than 400 million messages per day, including vast amounts of information about almost all industries from entertainment to sports, health to business etc. One of the best things about Twitter — indeed, perhaps its greatest appeal — is in its accessibility. It’s easy to use both for sharing information and for collecting it. Twitter provides unprecedented access to our lawmakers and to our celebrities, as well as to news as it’s happening. Twitter represents an important data source for the business models of huge companies as well.
All the above characteristics make twitter a best place to collect real time and latest data to analyse and do any sought of research for real life situations.

### WORDCLOUD:
A Word cloud is a visual representation of text data, typically used to depict keyword metadata (tags) on websites, or to visualize free from text. This format is useful foe quickly perceiving the most prominent terms and for locating a term alphabetically to determine its relative prominence.
Word clouds (also known as text clouds or tag clouds) work in a simple way: the more a specific word appears in a source of textual data (such as a speech, blog post, or database), the bigger and bolder it appears in the word cloud

##### 1. DATA GATHERING:

Data was collected for 3000 tweets for ‘AmazonIndia’, ‘Flipkart’ and ‘Snapdeal’.

i. Create twitter application  
ii. twitteR - Provides an interface to the Twitter web API
iii. ROAuth - R Interface For OAuth
iv. Create twitter authenticated credential object, It is done using consumer key, consumer secret, access token, access secret.  
v. During authentication, we are redirected to a URL automatically where we click on Authorize app as shown in the image below and enter the unique 7-digit number to get linked to the account from which feeds are being taken.

##### 2. DATA PRE-PROCESSING:

The tweets are cleaned in R by removing:
- Extra punctuation 
- Stop words (Most commonly used words in a language like the, is, at, which, and, on,.)
- Redundant Blank spaces
- Emoticons 
- URLS  

##### 3.LOADING WORD DATABASE:

A database, created by Hui Lui containing positive and negative words, is loaded into R. This is used for Lexical Analysis, where the words in the tweets are compared with the words in the database and the sentiment is predicted.  
For movie tweets, Naive Bayes Machine Learning Algorithm is used. AFINN is a list of English words rated for valence with an integer between minus five (negative) and plus five (positive). 

##### 4.SENTIMENT ANALYSIS:

Sentiment analysis (sometimes known as opinion mining or emotion AI) refers to the use of natural language processing, text analysis, computational linguistics, and biometrics to systematically identify, extract, quantify, and study affective states and subjective information.

#### Conclusion:

![Screenshot](img.png)

![Screenshot](hist.png)
