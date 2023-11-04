# Machine-Learning-Project
## Dog Vs Cat Clasification

### Dataset Description:

    Training Images of cats/dogs = 8000
    Testing Images of cats/dogs = 2000

### Results:
    84% accuracy on training data with epochs=15
    82% accuracy on validation data

## Guvi Rating Prediction

   Goal of this project is to predict the ratings given by the learners to the course based on various factors like price, number of suscribers, number of reviews, course 
   subject, content duration
   
### WorkFlow of Project:
     1) Importing Libraries And Loading Dataset:
  
        Importing Necessary libraries to load dataset.
  
     2) Data Preprocessing:
    
        Overcoming Null values
        
        Removing Noise data/Feature
        
        Label Encoding
        
        Handling skewness
        
        All these process are done in Preprocessing of data and analysed.
  
    3) Exploratory data Analysis:
  
       The relationship between Rating and specific Features are analysed by plotting correlation .
  
    4) Model Building
  
    5) Evaluating Model
     
    6) Model Report/Conclusion
       
       * As no features are highly correlated with the target variable Rating,no model fits the data.
        
       * So it is important to add more relative features and increase the dataset size inorder to predict the ratings accurately.
  
       * After applying various regression model, Random Forest model gives comparatively somewhat better accuracy i.e 58%,so considering it.
    
## Twitter Sentiment Analysis

  This project is focused on assisting users in determining whether a given tweet is positive or negative.
  This can be particularly useful for businesses or individuals who want to monitor public sentiment about their brand or a particular topic.
  
### WorkFlow of Project:
    1) Importing Libraries And Loading Dataset:
    
       Importing Necessary libraries to load dataset.

    2) Preprocessing The Dataset:
    
       Preprocessing the dataset like removing url's,#,@,punctuations, Stopwords,and stemming (Porter stemmer) the data to get root word.

    3) Exploratory Data Analysis:
    
       Removing the duplicates from the text and then analysing the data by plotting most frequent Words of the tweet.
       
    4) Feature Extraction:
    
       Extracting Features and converting the string/object Datatype Tweets into Float Matrix/Vector by Count Vectorizer.

    5) Model Building
       
    6) Evaluating Model

    7) Model Report
    
       1. LR - 77.90%
       
       2. tuned LR -  78.00%
       
       3. SVM - 76.95%


      

     





