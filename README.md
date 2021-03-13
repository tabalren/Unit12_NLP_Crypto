### Unit 12_Natural Language Processing - Crypto Sentiment 
#### There's been a lot of hype in the news lately about cryptocurrency. The attached .ipnyb file contains our code which will look at the latest news headlines related to Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin. Natural Language Processing techniques will be used to understand factors involved with the coin prices, such as common words and phrases and entities mentioned in the articles. 

#### 1. Sentiment Analysis
Using the newsapi, the latest news about Bitcoin and Ethereum have been pulled for further analysis of the sentiment scores for each coin. Please refer to .ipynb file for detailed code. A summary of the analysis can be found below.

### Anaylsis:
#### Q: Which coin had the highest mean positive score?
A: Ethereum had the highest mean positive score of 7.47%.

#### Q: Which coin had the highest compound score?
A: Ethereum had the highest compound score of 20. 

#### Q. Which coin had the highest positive score?
A:Ethereum had the highest positive score of 20. 

#### 2. Natural Language Processing - Tokenizer & Word Clouds
Using NLTK and Python, the text for Bitcoin and Ethereum has been tokenized to make sure each word is lowercase, remove punctuation and remove
stopwords and word cloud visualization has been used to summarize the news for Bitcoin and Ethereum. 

#### BTC Word Cloud 
![](images/btcword.jpeg)

#### ETH Word Cloud 
![](images/ethword.jpeg)

#### 3. Named Entity Recognition 
Now we have built a named entity recognition model for both Bitcoin and Ethereum and then visualized the tags using SpaCy.

#### BTC NER
![](images/btcner.jpeg)

#### ETH NER
![](images/ethner.jpeg)
