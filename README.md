# Text-Classification
Here we are going to perform a classification of text using NLP and ML algorithms

### Data(epinion.csv)
This is a csv file having 2 columns namely class and text

The class has two classes(auto and camera) which matches the text. This text has previously marked by the users and is correct.

Now we need to label the classes using ### LabelEncoder 
The other steps are as follow:-

1 - Preprocess the text(remove non alphabets and stopwords)

2 - Use CountVectorizer to convert the text into vector

3 - Train-test-split the data

4 - Define a model with Random Forest

5 - Fit the model

6 - Find the confusion Matrix

8 - Plot the ROC Curve
