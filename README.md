# Gender-calssification-
Aryaf Almusaiteer 

# Abstract
With the rise of social media in recent years, there has been a interest in automatically identifying users based on their informal content. the goal of the project is to clasifier the gender based on random tweet and the bio. 
This will help to know more words for each gender or brand to know people with fake accounts causing incitement or insulting and criticizing political matters. It will make it easier to classify them and therefore they will be treated

# Design 
The data show us the most frequent words based on gender 

#  Data
The Data has been extracted from Kaggle. The dataset consists of 20050 rows and 26 columns. Among 26 columns there are 25 predictor variables and 1 target variable which is gender in this case.
The link to the data source is given below.
Link- https://www.kaggle.com/crowdflower/twitter-user-gender-classification/

#  Algorithms 
### Feature Engineering:
* Cleaning the text by converting the chars to lower case, removing all special chars, removing stop words, and applying lemmatization.
* Label the data Female = 0 , male = 1 , brand = 3. 
* Display the most frequent words based on gender or brand, then display the common words between the three categories

### Models:
* Naïve bayes 
Accuracy:0.22
* Logistic regression
Accuracy: 0.55
* Random forest
Accuracy:0.54
* MultinomialNB
Accuracy:56.20 

MultinomialNB is the high accuracy 

# Tools 
*Pandas and numpy 
*For the text (Nltk for stopwords, re , CountVectoizer) 
*Matplotlib and Seaborn for plotting
* Power BI for interactive visualizations

# Communication 

