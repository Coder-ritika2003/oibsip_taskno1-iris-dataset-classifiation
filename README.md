This repository contains the code for training a machine learning model to classify Iris flowers based on their measurements. The Iris flower dataset consists of three species: Setosa, Versicolor, and Virginica, each having distinct measurement characteristics. The goal is to develop a model that can accurately classify Iris flowers based on their measurements.

Dataset
The dataset used for this project is the famous Iris flower dataset, which is commonly used for classification tasks. It includes measurements of sepal length, sepal width, petal length, and petal width for 150 Iris flowers, with 50 samples for each species. The dataset is available in the repository as iris.csv.

Dependencies
The following Python libraries are used in this project:

NumPy
Pandas
Seaborn
Matplotlib
Model Training
The code for training the classification models can be found in the iris_classification.ipynb Jupyter Notebook. Three different models are trained:

Support Vector Machine (SVM)
Logistic Regression
Decision Tree Classifier
Each model is trained using the Iris flower dataset and evaluated for its accuracy
Testing
After training the models, a new test dataset is used to assess their performance. The test dataset contains measurements of Iris flowers with unknown species. The trained models predict the species of these flowers, and their accuracy is evaluated.
