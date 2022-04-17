Hi,
My name is Jeff Ott and I am a graduate student as the USF Masters in Data Science program. During this program we've tackle a large amount of topics and projects. I will post what projects I can, but at the request of the univeristy the code will not be readily avaiable unless by specific request. 

### Data translation pipeline  <br>
Description: In this project we made some pyfiles to translate to different data types from command line <br><br>
<img width="509" alt="image" src="https://user-images.githubusercontent.com/60712345/161851380-3bef0ea3-8560-46c0-b48f-fc1c0e26d7c7.png"> <br>
*Libraries Used: sys, untangle, xmltodict, json*

### Search Engine Implementation <br>
Description: In this project we implimented a search engine with both linear search and hash table search then compared the differences between the two. We then created a local website on flask allow local users to access and use the engine <br><br>
<img width="711" alt="image" src="https://user-images.githubusercontent.com/60712345/161855175-0be40807-edf6-4241-8148-9d1938792bb5.png"><br>
*Libraries Used: Flask, doc2vec, Regex, Codecs, Numpy*

### TFIDF Document Summary <br>
Description: In this project we processed zipped XML data (44M uncompressed, 9164 files), removed the XML and tokenized the remaining strings. We developed a workflow which would calculat TFIDF (Term Frequency. inverse document Frequency) for each of the documents. 
*Libraries Used: nltk, xml.etree.cElementTree, sklearn.feature_extraction.text, collection, zipfile, string

### Recommendation of Articles <br>
In this project I was first introduced to word embeddings in the form of word2vec. I converted all the documents in an into embedding lists and found the centriods of each doucment. I then recomended documents based on eucliedain distance. We then use flask, gunicorn, and jninja to build a scaleable website hosted on EC2 on AWS.<br><br>
![image](https://user-images.githubusercontent.com/60712345/163700421-ac099934-f0f7-4739-b00e-57118db89d7f.png)
*Libraries Used: flask, doc2vec,re,string,numpy, codecs <br>

### Tweet Sentiment Analysis <br>
In this project I learned how to mine twitter data and perform a sentiment analysis to find the users average sentitment through a search. I then hosted this website on EC2 and let users search for average sentitment on any public twitter handle. This introduced me to website api and classifying sentiment from raw text. <br><br>
![image](https://user-images.githubusercontent.com/60712345/163700854-d423e284-d7e2-42c7-8ce4-e2bb6859aff0.png)
*Libraries Used: flask, tweetie,colour,numpy, tweepy, vadarSentiment <br>


## Zillow Housing Prediction (Time Series) <br>
In this project we attempted to predict median housing price in california using the unemployment and Mortgage rate as helper variables. We tried three differnt models on the data ETS, SARIMAX, and FB Prophet. We were able to get a moderatly good prediction with an RMSE of $7720. The methods and result are displayed in the Zillow Housing Prediction PDF. <br><br>
![image](https://user-images.githubusercontent.com/60712345/163701462-0f53bbfc-664f-4f2e-bc1e-146c0ba06792.png)
#Libraires Used: Pandas, Numpy, statsmodels, fbprophet, tqdm, sklearn, pmdarmia, matplotlib

## Linear Models <br>
In this project I implimented OLS, L2 regularization, and logstic regression. I created functions to normalize the data and compute the loss gradient w/ without regularization. I then utilized these function to make LogisticRegression, Linearegression and Ridgeregresison classes.
![image](https://user-images.githubusercontent.com/60712345/163701679-685d81f0-cbc2-4a39-aaf9-a4931e2dc267.png)
#Libraries Used: pandas, numpy 

## Naive Bayes<br>
In this project I built a mulinomial naive bayes classifier to predict whether a movie review was positive or negative. I used Laplace smoothing to deal with missing words and vectorized operation to increase speed. I then used K_fold cross validation class i coded to train the model and compare it against Sklearn. I was able to acheive a 80% accuracy with this model <br>
#Libraries Used: sklearn, numpy, time, codecs, re <br><br>
![image](https://user-images.githubusercontent.com/60712345/163702511-6f5f6740-3063-40fa-9de2-6169b8765109.png)

## Decison Trees<br>
In this project I attempted to recreated Sklearn Decision trees using recusivly constructed trees. I implimented LeafNode, DecsionNodes, Decsion tree classes and split using gini impurity for classficaiton and MSE for regression. I then inherizted these classes in my RegressionTree and ClassifierTree functions. I compared these with the Sklearn implimentations and got with small margin or error. <br>
#Libraries Used: numpy, scipy.stats, lolviz <br><br>
![image](https://user-images.githubusercontent.com/60712345/163702913-a9f92d76-3627-4832-bc5e-f7494939fb56.png)

## Random Forest<br>
Using my decsion tree implimentation from before. I was tasked with combining these trees to build a random forest. I built  RandomForestRegressor and RandomForestClassifier classes. I had to impliment bootstrapping, sub sampling, Out-of-bag error estiamtion and random forest prediction to get comparable accuarcy to Sklearn.
#Libraries Used: numpy, scipy.stats, lolviz <br><br>
![image](https://user-images.githubusercontent.com/60712345/163703319-bb065869-65d4-4513-86ad-1f919d78ac83.png)


## OO hash table implimentation <br>
In this 
Libraries Used:

## Clustering <br>
Libraries Used:

## Feature Importance <br>
Libraries Used:

## Multi Class Logistic Regression Implementation <br>
Libraries Used:

## Feature Engineering <br>
Libraries Used:

## ML Metric Understanding <br>
Libraries Used:

## A/B Testing Netflix Consultation <br>
Libraries Used:

## Gradient Boosted Neural Networks




