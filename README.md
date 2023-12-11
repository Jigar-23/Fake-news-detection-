# Fake-news-detection-
It included data cleaning that is done with the help of pandas library functions like read_csv ,
by the help of describe we can describe the dataframe that we have imported . Other functions like drop ,
dropna are used to drop the columns and the null values respectively . 
reset_inedx is used to reset the index after cleaning the irrelevant values .
iloc can be used to form separate dataframes for the text and label respectively .
Furthermore,
Now that we have created two separate dataframes ,after this we
created two functions to remove thepunctuations and stopwords with
the help of NLTK library and regex library functions . After that we
use train_test_split to separate the training data from the testing
data . We can also declare the size of the testing data here . Now 
from the sklearn.feature_extraction.text we have imported TfidfVectorizer 
.Thereafter we have fit the train and testing data with the help of the object
of Tfidfvectorizer . After that we have imported the DecisionTreeClassifier
form sklearn.tree . From the help of its object we can fit the training data
and can predict the outcome of the testing data . After all these , we have
imported accuracy_score from sklearn.metrics to find the accuracy score of
the model that we have just created . The accuracy comes out to be 89.3122% .
 
