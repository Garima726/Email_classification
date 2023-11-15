# Email_classification

Here, the dataset is downloaded from Kaggle. After downloading it, the first setp is data preprocessing.

Data preprocessing is done by NLTK library of machine leraning.

In this data processing, data was freed from all the punctuations, stopwords. 

After removing the stopwords and punctuations, vectorization was done and Tfidfvectorizer was the best method between tfidfvectorizer, Countvectorizer.

Then, the models were built. Algorithms were used in this model building were LogisticRegression, RandomForestClassifier, GradientBoostingClassifier,
AdaBoostClassifier, DecisionTreeClassifier, KNeighborsClassifier, SVC, XGBClassifier, MultinomialNB, GaussianNB.

The model which performed best and gave 96.42% accuracy was LogisticRegression.

Afer building the model, the model was deployed using pickle. Here, the user can give any message, and the model will predict whether that message is spam or not.
