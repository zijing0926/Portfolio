# Portfolio
Zijing's data science project portfolio

# [News Setiment and Topic Analysis on WTI Crude Oil Future Prices](https://github.com/zijing0926/News-Sentiment-and-Topic-Analysis)
* Web scriped over 6000 crude-oil related news articles using urls provided by Bloomberg
* Applied text mining algorithms to [preprocess news articles](https://towardsdatascience.com/a-step-by-step-tutorial-for-conducting-sentiment-analysis-a7190a444366)
* [Transformed cleaned text data with TFIDF Vectorizer](https://towardsdatascience.com/a-step-by-step-tutorial-for-conducting-sentiment-analysis-9d1a054818b6), [utilized Logistic Regression](https://towardsdatascience.com/a-step-by-step-tutorial-for-conducting-sentiment-analysis-cf3e995e3171), LDA, and K-means to conduct sentiment and topic analysis
* Deployed the trained and evaluated machine learning model at [Heroku](https://news-analysis-crude-oil.herokuapp.com/)
* [Academic paper descriping the project in detail](https://www.dropbox.com/s/drj3y7quabgg7r7/news_analysis.pdf?dl=0)

Positive Words             | Negative words
:-------------------------:|:-------------------------:
<img width="300" height="300" src="images/w3.png"> | <img width="300" height="300" src="images/w4.png">

# [High-Speed Railway(HSR) Network Growth and Labor Reallocation](https://github.com/zijing0926/Chinese-High-Speed-Railway)
* Conducting casual inference between employment and transportation cost across cities and industries using fixed effect panel regression with R
* Constructed a instrument variablea conducting spatial analysis with angular corrdinates to compute geographic distances among over 200 cities
* Created graphs with Matplotlib and Seaborn for data visualization. and designed geographic maps with GeoPython.
* [Academic paper descriping the project in detail](https://www.dropbox.com/s/7i95i4u2enn5kz6/Chapter2_HSR.pdf?dl=0)

First HSR in 2008          |  HSR Network in 2018
:-------------------------:|:-------------------------:
<img width="300" height="300" src="images/hsr_2008.png"> | <img width="300" height="300" src="images/hsr_2018.png">

<img width="600" height="400" src="images/image.png">

# [New York Elite Social Network](https://github.com/zijing0926/New-York-Social-Graph)
* Web scraped over 100,000 photo captions from [New York Social Diary](https://web.archive.org/web/20150913112557/http://www.newyorksocialdiary.com/) and extracted names using Regex and spaCy. 
* Built New York Elite social network using Networkx with the assumption that people in the same picture know each other. 
* Utilized the New York elite social network to find the most popular socialites, most influential people and the most tightly coupled pairs.

# [Distributed Computation: Using Pyspark to Analyze Stack Overflow Posts](https://github.com/zijing0926/Spark)
For a dataset as large as 10GB with stack overflow posts, using RDD, this project:
* filtered out the bad XMLs;
* aggregated posts by the number of favorite counts, and finds the average score for each number of favorites;
* for 99 users with the highest reputation, calculated these users answer percentage by calculating answers/(answers+questions), and the average answer percentage for all users;
* found number of days between account creation and first question for 100 users with the highest reputation;
* identified the veterans for users that has answered or asked a questions between 100 and 150 days after account creation; defined the rest of the users brief users;
* presented the differences in average score, views, number of answers and number of favorites between veterans and brief users and veterans have better stats for all measurements here

Using PySpark DataFrame, this project:
* applied word2vec as an vectorizer for text data, and finds the top 25 closest synonyms to 'ggplot2' and their similarity scores.
* built a machine learning pipeline, takes the body text as the features to predict whether a question contains one of the top ten most common tags
* removed stopwords, tokenized the texts, used HashingTF as the transformer and logistic regression as the estimator; used cross validation to tune hyper parameters.

<img width="400" height="600" src="images/word2vec.PNG">

