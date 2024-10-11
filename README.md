**k-Nearest Neighbors (kNN) Classifier**

Overview: This project implements a k-Nearest Neighbors (kNN) Classifier to classify different species of organisms based on a provided dataset. The objective is to evaluate the accuracy of the kNN classifier as the value of k (number of neighbors) varies from 1 to 1000.

Dataset: The dataset used in this project contains information about various organisms and their classifications, including genus, family, and species. The goal is to predict the genus of an organism based on the other features provided.

1) Dataset Details: The dataset consists of multiple features including 'Family' and 'Species', which are removed before model training.
2) Target Variable: Genus. The remaining columns are used as features for the kNN classifier.

Tasks

Data Preprocessing: Load the dataset and drop unnecessary columns (Family, Species). Convert the features into a NumPy array. Split the dataset into training and testing sets (80% training, 20% testing).

kNN Implementation: Implement a kNN classifier using the KNeighborsClassifier from sklearn. Vary the value of k from 1 to 1000 and compute the accuracy for each value of k on the testing set.

Visualization: Plot the accuracy of the classifier as a function of k to analyze the effect of different values of k on model performance.

Dependencies

This project requires the following Python libraries:

i) numpy
ii) pandas
iii) matplotlib
iv) sklearn

To install the dependencies, run: pip install numpy pandas matplotlib scikit-learn

Instructions to Run

Load the Dataset: Ensure the dataset (Q1Data.csv) is available in the working directory.

Preprocess the Data: The notebook includes code to drop irrelevant columns and prepare the data for training.

Run the kNN Classifier: The classifier will be trained and tested for various values of k from 1 to 1000. The accuracy for each value of k will be calculated and stored.

Plot the Results: The accuracy values are plotted against the values of k to visualize how the choice of k affects the classifier's performance.

Results 

A graph showing the accuracy of the kNN classifier for different values of k will be displayed. This helps to understand the optimal value of k for this classification task.
