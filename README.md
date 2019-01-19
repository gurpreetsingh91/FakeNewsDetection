# Political Fake News Detection

- This is my Masters Project which I recently completed.

- Intro - In the age of digital news, the sensationalist news has been spreading in the huge amount and has generated bulk of misinformation, best example being the presidential elections of the United States conducted in 2016, during which a significant amount of the false or modified information was circulated before the voting. This definitely provided an upper hand to Donald trump over the rival candidate Hilary Clinton. It is the modern day trend to make the news sensational to get the focus of the users online with the motive of generating money online whether through ads or getting the support from the political parties. Hence, it is very important to categorize the news into Sensationalist and Objective. Sensationalist news is written in the format with the intention of attracting the focus of the user. It might not be 100% fake but is definitely modified a lot compromising the real facts. While Objective news is the one which is delivered without any manipulation of the content and solely based on the facts. This project explores the usage of natural language processing techniques for classifying the news as Sensationalist or Objective. Using the dataset from the politifact.com which is extracted and cleaned by the Computational Linguistics Research Group at the University of Antwerp, we apply the term frequency-inverse document frequency (TF-IDF) and DictVectorizer of multiple text statistic features to a corpus of around 12000 articles. We test the two classification algorithms – Support Vector Machine and Bernoulli Naive Bayes on the test set. Using TF-IDF of multiple features and feeding them to the SVM helps in achieving the accuracy of 92% to classify the news as Sensationalist or Objective


# Tools & Libraries Used:-

1. IDE - Spyder
2. Python 3
3. Numpy, Scikit Learn, Pandas


# Steps to run the Classifier

1. Clone the project

2. Change the path of the dataset at line 189 of ObjectiveSensational_SVMClassifier by adding the right path to train_path.

3. Run the code

# Output generated

1. Accuracy of the classifier

2. Confusion Matrix 

3. ROC Curve 

4. AUC 

5. Classification Report

### The Results can be found in the Final Project here in the repository.
### Final Model chosen - SVM 


