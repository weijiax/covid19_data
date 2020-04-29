<h1> Covid19 Data Collection </h1>

The purpose of this repository is to document Covid19 related data collections hosted at TACC. 

## Twitter Data Collection
The data collcetion including data collected Mar.25 2020. Information about Tweets are summaized on daily basis including IDs, and top n-grams. A "day" is defined as a calendar day of US central time. 

* **Keywords Logs**
  * 2020-03-24-16-01 "COVID","coronavirus","Chinese virus"
  * 2020-03-26-14-00 "COVID","Coronavirus","Chinese virus","school closure","school closed" 
  * 2020-04-02-10-00 "COVID","Coronavirus","Chinese virus","school closure","school closed","Food scarcity","Water contamination"
  * 2020-04-23-10-30 "COVID","Coronavirus","Chinese virus","school closure","school closed","Food scarcity","Water contamination","reopen business"


* **Tweets IDs** The IDs of collected tweets are archived in tweet_id folder. The IDs of all tweets collected on that day are stored in the file with "all" prefix. In addition, there is a seperate list of IDs without re-tweets stored in the file with "
noRT" prefix.  

* **n-grams** Top 1000 n-grams from each day are stored in the n-grams folder. The results exlcudes all re-tweets. Both English and Spanish stopword lists from NLTK packages are used to remove stop words. Here we included top 1000 1-grams, 2-grams and 3-grams.  
<p align="center">
    <img src="https://github.com/weijiax/covid19_data/blob/master/tweets/img/1-grams.gif" width="30%"/>
    <img src="https://github.com/weijiax/covid19_data/blob/master/tweets/img/2-grams.gif" width="30%"/>
    <img src="https://github.com/weijiax/covid19_data/blob/master/tweets/img/3-grams.gif" width="30%"/>
    <br> <b>Top 20 1,2,3-grams from daily original tweets</b>
</p>


This is an ongoing collection and we will keep adding new data and processed results. 
