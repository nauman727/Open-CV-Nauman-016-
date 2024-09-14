# Open CV
 repository of computer vision projects 
 IN THIS REPOSITORY YOU WILL FIND A PY FILE FOR SEVERAL MACHINE LEARNING ALGORITHMS AND THEIR COMPARISON ALONG WITH A FOLDER OF 
 STOCK IMAGES WHICH CONSIST A BUNCH OF TRAFFIC IMAGES 
 THIS REPOSITORY IS A TUTORIAL REPOSITORY OF 
 MUHAMMAD NAUMAN 
 FROM AI 6A 
 01-136221-016


 DESCRIPTION:
 The code starts by importing essential libraries for data manipulation, machine learning, and visualization. It then loads the Iris dataset from sklearn. This dataset is converted into a dataframe for easier handling. The next step involves splitting the data into training and testing sets, with 70% used for training the model and 30% reserved for testing its performance. To ensure that the data is on a comparable scale the features are standardized.

Four different classification models are then applied to the dataset. Decision Tree classifier is used first which builds a tree like model of decisions based on the feature values and is evaluated for accuracy and detailed performance metrics. Following this, a Random Forest classifier is trained, which combines multiple decision trees to improve accuracy and reduce overfitting. The Naive Bayes classifier is next which uses probabilistic methods based on Bayes Theorem to make predictions. Finally, the K Nearest Neighbors (KNN) classifier is employed, which classifies data points based on the majority class of their nearest neighbors.

After training and making predictions with each model, the code evaluates their performance by calculating accuracy and generating detailed classification reports. To visually compare the performance of each classifier, confusion matrices are plotted. These matrices show how many predictions were correct versus incorrect, providing a clear picture of each model’s strengths and weaknesses.

