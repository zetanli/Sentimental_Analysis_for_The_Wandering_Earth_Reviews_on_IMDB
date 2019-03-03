# <center>Sentimental Analysis for The Wandering Earth Reviews on IMDB  </center>

**Description**  

During Chinese New Year, an unprecedented Chinese Sci-Fi movie released. It's box office gross is more than 4 billion CNY(that is about $70,000,000 dollars) in China. On this analysis, I scraped audience reviews from IMDB. Then applied sentimental analysis on the data we scraped.

**EDA**

Please see the code directly, which is not hard to read.

**Data Preparation**

I follow the belowing steps to do data preparation.  

```        
* remove characters like punctuation, numbers, other characters.  
* tokenize  
* lematize  
* remove stop words  
* vectorize  
```  

**Regression**

In this part, I seem the full dataset as training data. Apply GBDT to the dataset and compute mean absolute percentage error.

**Next Step**

In next steps, I will scrap more data from the imdb website. Use 2-bigram for regression and implement cross validation as well as tunning some parameters. 
